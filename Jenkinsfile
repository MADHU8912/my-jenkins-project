pipeline {
    agent any

    stages {
        stage('Checkout Info') {
            steps {
                echo 'Pipeline started from SCM'
            }
        }

        stage('Check Files') {
            steps {
                bat 'dir'
            }
        }

        stage('Build Report') {
            steps {
                bat 'echo Jenkins SCM build successful > build-report.txt'
                bat 'type build-report.txt'
            }
        }
    }
stage('Deploy') {
    steps {
        echo 'Deploying application'
    }
}