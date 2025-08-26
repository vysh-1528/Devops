pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/vysh-1528/Devops.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the project...'
                sh 'ls -l'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'echo "All tests passed successfully!"'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                // Example: copy files to web server (if Apache/Nginx installed)
                sh 'echo "Files deployed!"'
            }
        }
    }
}
