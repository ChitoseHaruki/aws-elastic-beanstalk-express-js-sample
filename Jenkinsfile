pipeline {
    agent {
        docker { image 'node:16' }
    }
    stages {
        stage('Setup') {
            steps {
                sh 'npm install --save'
            }
        }
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}
