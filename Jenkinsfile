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
                bat 'echo "Build success!"'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                bat 'echo "Tests passed!"'
            }
        }
    }
}
