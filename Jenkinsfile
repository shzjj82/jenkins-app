pipeline {
    agent {
        docker {
            image 'node:10.20.1-alpine3.11'
        }
    }
    stages {
        stage('install') {
            steps {
               sh "npm install"
            }
        }
        stage('build') {
            steps {
               sh "npm run build"
            }
        }
    }
}