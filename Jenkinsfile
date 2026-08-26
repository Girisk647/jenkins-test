pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                sh 'chmod +x script.sh'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                sh './script.sh'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying to production server!'
            }
        }
    }
}
