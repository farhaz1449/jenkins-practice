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
                sh 'ps aux' 
                echo 'Pipeline completed successfully!'
            }
        }
    }
}
