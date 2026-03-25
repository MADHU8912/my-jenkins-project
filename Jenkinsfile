pipeline {
    agent any

    stages {
        stage('Check Files') {
            steps {
                bat 'dir'
            }
        }

        stage('Build') {
            steps {
                bat 'echo Build successful > build-report.txt'
                bat 'type build-report.txt'
            }
        }

        stage('Deploy') {
            steps {
                bat 'echo Deploy successful > deploy-report.txt'
                bat 'type deploy-report.txt'
            }
        }
    }
}