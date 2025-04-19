node {
    git branch: 'main', url: 'https://github.com/Mohamednageeb/simple-java-app.git'
    
    stage('Build') {
        try {
            sh 'echo "build stage"'
        } catch(Exception e) {
            sh 'echo "exception found"'
            throw e
        }
    }
    
    stage('Test') {
        if (env.BRANCH_NAME == "feat") {
            sh 'echo "test stage"'
        } else {
            sh 'echo "skip test stage"'
        }
    }

}