pipeline {
    agent any

    stages {
        stage('Install') {
            steps {
                sh 'node --version'
                sh 'npm --version'
                sh 'npm install'
            }
        }

        stage('Test') {
            steps {
                sh 'npm test || true'
            }
        }
    }
}
