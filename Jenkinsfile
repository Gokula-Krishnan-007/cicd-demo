
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building application...'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing application...'
                bat 'python -m pytest'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                bat 'python app.py'
            }
        }
    }
}
