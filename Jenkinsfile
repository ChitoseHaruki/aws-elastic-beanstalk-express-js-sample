pipeline {
    agent {
       docker {
            image 'node:16-alpine'  
            args '-p 2376：2376' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}
