pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello world!(v3)' 
                echo 'Jenkinsfile on ${env.BRANCH_NAME}'
                bat 'printmessage.bat'
            }
        }
    }
}
