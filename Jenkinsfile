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
                echo 'Pipeline completed successfully!'
            }
        }
    }
}
