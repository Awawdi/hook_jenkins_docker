pipeline {
    agent {
        docker { image 'node:20.10.0-alpine3.19' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
        stage('Test2') {
            steps {
                sh 'node --version'
            }
        }
    }
}
