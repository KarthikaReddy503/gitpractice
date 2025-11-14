pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                git 'https://github.com/YourUsername/YourRepo.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building...'
                // If you had code, you could run build commands here
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // If you had code, you could run test commands here
            }
        }

        stage('Success') {
            steps {
                echo 'Pipeline executed successfully!'
            }
        }
    }
}
