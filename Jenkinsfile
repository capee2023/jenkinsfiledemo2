pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                bat 'echo "Building"'
            }
        }
        stage('Deploy') {
            steps {
                 bat 'echo "Deploying"'
            }
        }
        stage('Test') {
            steps {
                 git branch: 'main', credentialsId: 'f450f79c-443f-4d33-a2b0-23ab81216245', url: 'https://github.com/capee2023/jenkinsfiledemo2'
            }
        }
    }
}
