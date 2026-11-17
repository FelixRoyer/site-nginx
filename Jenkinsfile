pipeline {
    agent any

    stages {
        stage('Build & Run') {
            steps {
                sh 'docker compose up -d --build'
            }
        }
        stage('Vérification') {
            steps {
                sh 'docker compose ps'
            }
        }
    }
}
