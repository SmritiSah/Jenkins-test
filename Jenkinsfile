pipeline {
  agent any

  stages {
    stage('Run in Docker') {
      steps {
        script {
          docker.image('node:16-alpine').inside('-v /c/ProgramData/Jenkins/.jenkins/workspace/dj1:/app -w /app') {
            sh 'node --version'
          }
        }
      }
    }
  }
}
