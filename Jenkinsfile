pipeline {
  agent {
    docker {
      image 'node:16-alpine'
      args '-v /c/ProgramData/Jenkins/.jenkins/workspace:/workspace -w /workspace'
    }
  }
  stages {
    stage('Test') {
      steps {
        bat 'node --version'
      }
    }
  }
}
