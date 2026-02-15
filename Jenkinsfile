pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Building the application..."
                bat 'echo Build step running on Windows'
            }
        }

        stage('Test') {
            steps {
                echo "Running tests..."
                bat 'echo Test step running on Windows'
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying application..."
                bat 'echo Deployment step running on Windows'
            }
        }
    }
}
