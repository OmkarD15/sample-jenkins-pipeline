pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out code...'
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Running build...'
                // Replace this with your actual build commands
                sh 'echo "Build success!"'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Replace with your real test command
                sh 'echo "Tests passed!"'
            }
        }
    }
}
