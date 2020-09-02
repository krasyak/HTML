pipeline {
    agent { docker {image 'python:latest' }}
    
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