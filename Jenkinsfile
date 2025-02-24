pipeline {
  agent {
    docker {
      image 'node:16-alpine'
      args '-v /c/ProgramData/Jenkins/.jenkins/workspace/dj1:/app -w /app'
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
