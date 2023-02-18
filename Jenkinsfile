pipeline {
    agent {
        docker {
            image 'node:10.20.1-alpine3.11'
            args '-v $HOME/.m2:/root/.m2'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
    }
}