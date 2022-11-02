pipeline {
    agent { docker { image 'node:fermium-slim' } }
    stages {
        stage('build') {
            steps {
                sh 'node --version'
            }
        }
    }
}