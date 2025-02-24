pipeline {
  agent {
    docker {
      image 'node:16-alpine'
      args '-v /var/jenkins_home:/var/jenkins_home'  // Mount Jenkins home properly
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
