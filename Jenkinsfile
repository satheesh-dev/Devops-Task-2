pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo '📦 Building the application...'
            }
        }
        stage('Test') {
            steps {
                echo '🧪 Testing the application...'
                powershell 'python app.py'
            }
        }
        stage('Deploy') {
            steps {
                echo '🚀 Deploying the application...'
            }
        }
    }
}
