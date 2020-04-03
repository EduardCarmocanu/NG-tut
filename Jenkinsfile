pipeline {
    agent { 
        docker { 
            image 'node' 
        }
    }
    stages {
        stage('install') {
            environment { HOME="." }
            steps {
                sh 'npm install'
            }
        }
        stage('build') {
            steps {
                sh 'npm run build'
            }
        }
        stage('Deployment') {
            steps {
                sh 'echo deployment environment not created yet, please stay tuned'
                sh 'exit 0'
            }
        }
    }
}