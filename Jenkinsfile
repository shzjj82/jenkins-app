pipeline {
    agent { any { image 'node:12.16.2' args '-v $HOME/.m2:root/.m2' } }
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
    }
}