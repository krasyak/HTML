pipeline {
    agent {
        docker { image 'node:14-alpine' }
    }
    stages {
        stage('Test') {
            steps {
                sh "pwd"
                sh "la -la"
                sh 'node --version'
            }
        }
    }
}