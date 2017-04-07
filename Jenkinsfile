pipeline {
  agent {
    docker {
      image 'ticketfly/node-chromium-webgl'
    }
    
  }
  stages {
    stage('info') {
      steps {
        sh 'npm -version'
      }
    }
  }
}