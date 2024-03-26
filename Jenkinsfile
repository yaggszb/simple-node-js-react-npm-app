pipeline {
    agent any
    stages {
        stage('Check Version'){
            steps {
                sh 'node -v'
                sh 'npm -v'
            }
        }
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}