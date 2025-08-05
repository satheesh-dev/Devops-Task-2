pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo '📦 Building the application...'
                bat 'echo Build step running on Windows'
            }
        }

        stage('Test') {
            steps {
                echo '🧪 Testing the application...'
                bat 'python --version'
                bat 'python app.py'
            }
        }

        stage('Deploy') {
            steps {
                echo '🚀 Deploying the application...'
                bat 'echo Deploying... Done!'
            }
        }
    }
}
