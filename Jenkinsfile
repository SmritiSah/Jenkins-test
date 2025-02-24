pipeline {
    agent {
        dockerfile {
            filename 'Dockerfile'
            dir './'
            args '-w /workspace'
        }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --eval "console.log(process.platform, process.env.CI)"'
            }
        }
    }
}
