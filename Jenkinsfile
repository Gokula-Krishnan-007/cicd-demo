
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
                bat '"C:\\Users\\Gokul\\AppData\\Local\\Programs\\Python\\Python313\\python.exe" -m pip install pytest'
                bat '"C:\\Users\\Gokul\\AppData\\Local\\Programs\\Python\\Python313\\python.exe" -m pytest'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                bat '"C:\\Users\\Gokul\\AppData\\Local\\Programs\\Python\\Python313\\python.exe" app.py'
            }
        }

    }
}
