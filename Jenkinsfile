pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh 'echo "Hello World"'
            }
        }
        stage('Hello2') {
            agent{
                docker{
                    image 'node:18-alpine'
                }
            }
            steps {
                sh 'echo "Hello World"'
                sh 'npn--version'
            }
        }
        stage('Hello3') {
            steps {
                sh 'echo "Hello World"'
            }
        }
        stage('Bye1') {
            steps {
                sh 'echo "Hello World"'
            }
        }
        
    }
}

