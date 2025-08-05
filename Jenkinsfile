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
                script {
                    def proc = "python app.py".execute()
                    proc.waitFor()
                    def output = proc.in.text
                    echo output
                }
            }
        }
        stage('Deploy') {
            steps {
                echo '🚀 Deploying the application...'
            }
        }
    }
}
