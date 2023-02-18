pipeline {
    agent {
        docker {
            image 'node:10.20.1-alpine3.11'
        }
    }
    stages {
        stage('Install') {
            steps {
               sh "npm install"
            }
        }
        stage('Build') {
            steps {
               sh "npm run build"
            }
        }
    }
}