pipeline {
    agent { docker { image 'node:14-alpine' } }
    stages {
        stage('verificando') {
            steps {
                sh 'npm --version'
            }
        }
    }
}
