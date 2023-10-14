pipeline {
  agent {
    sh '/usr/local/bin/docker pull node:16-alpine'
  }
  stages {
    stage('Test') {
      steps {
        sh 'node --version'
      }
    }
  }
}
