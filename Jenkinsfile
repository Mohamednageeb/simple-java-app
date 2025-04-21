pipeline {
    agent any
       
    stages {
        stage('build') {  // ✅ Stage names should ideally be lowercase or kebab-case
            steps {
                script {
                    echo "build in progress"
                }
            }
        }
    
        stage('test') {
            steps {
                script {
                    echo "test in progress"
                }
            }
        }
    }  // ✅ Correctly closes `stages` block
}      // ✅ Correctly closes `pipeline` block