pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                // Checkout the code from the GitHub repository
                git 'https://github.com/umarqazii/mlops-task3.git'
            }
        }
        stage('Build') {
            steps {
                // Build step
                sh 'echo "Building the app"'
            }
        }
        stage('Test') {
            steps {
                // Test step
                sh 'echo "Testing the app"'
            }
        }
        stage('Deploy') {
            steps {
                // Deploy step
                sh 'echo "Deploying the app"'
            }
        }
    }
}
