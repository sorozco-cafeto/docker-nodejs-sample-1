pipeline {
    agent { docker { image 'node:18.18.2-alpine3.18' } }
    stages {
        stage('build') {
            steps {
                docker compose up -d
            }
        }
    }
}