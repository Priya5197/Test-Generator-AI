pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Priya5197/Test-Generator-AI.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the application...'
                // Add build steps here (e.g., Docker build or Maven build)
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Add test commands here (e.g., run unit tests or integration tests)
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                // Add deployment steps here (e.g., Docker run or Kubernetes deployment)
            }
        }
    }
}
