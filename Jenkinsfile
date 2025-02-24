pipeline {
  agent {
    docker {
      image 'node:16-alpine'
    }
  }
  stages {
    stage('Verify Node Version') {
      steps {
        sh 'node --version'
      }
    }
  }
}
