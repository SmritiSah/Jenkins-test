pipeline {
    agent {
        dockerfile {
            filename 'Dockerfile'
            dir './'
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
