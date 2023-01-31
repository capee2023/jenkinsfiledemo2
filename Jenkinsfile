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
                 bat 'call "C:\\Jenkins\\batfiles\\test2.bat"'
            }
        }
    }
}
