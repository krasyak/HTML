pipeline {
    agent { docker {image 'python:latest' }}
    agent any

    stages {
        stage('1-stage') {
            steps {
                echo 'Hello World'
                sh "pwd"
                sh "la -la"
            }
        }
    }
}