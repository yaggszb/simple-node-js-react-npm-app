pipeline {
    agent any

    stages {
        stage('Check Version'){
            steps {
                echo $PATH
                sh 'node --version'
                sh 'npm --version'
            }
        }
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}