pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo "Running a simple build step..."
                echo "Hello from Jenkins Pipeline!"
            }
        }

        stage('Test') {
            steps {
                echo "Running tests..."
                echo "All tests passed!"
            }
        }
    }

    post {
        always {
            echo "Pipeline completed."
        }
    }
}
