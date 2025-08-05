pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "📦 Building the application..."
                bat 'echo Build completed' // or real build logic
            }
        }

        stage('Test') {
            steps {
                echo "🧪 Testing the application..."
                bat 'python app.py' // or run test cases
            }
        }

        stage('Deploy') {
            steps {
                echo "🚀 Deploying the application..."
                bat 'echo Deployed!' // or deployment logic
            }
        }
    }
}
