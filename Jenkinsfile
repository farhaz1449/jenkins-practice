pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello, Jenkins!'
            }
        }

        stage('List Files') {
            steps {
                sh 'ls -l'
            }
        }

        stage('Print Date') {
            steps {
                sh 'date'
            }
        }

        stage('Goodbye') {
            steps {
                sh 'ping -c 4 www.google.com'
                echo 'Pipeline completed successfully!'
            }
        }
    }
}
