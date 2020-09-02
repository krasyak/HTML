pipeline {
    agent {
        docker { image 'node:14-alpine' }
    }
    stages {
        stage('Test') {
            steps {
                sh "pwd"
                sh "ls -la"
                sh 'node --version'
            }
        }
        stage('Stage-2') {
            steps {
                sh "pwd"
                sh "ls -la"
                sh 'node --version'
            }
        }
    }
}