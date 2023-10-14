pipeline {
  agent {
    docker { image 'node:16-alpine' }
  stages {
    stage('Test') {
      steps {
        sh '/usr/local/bin/docker pull node:16-alpine'

        sh 'node --version'
      }
    }
  }
}
