pipeline {
    agent {
        docker {
            image 'node:19-alpine3'
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