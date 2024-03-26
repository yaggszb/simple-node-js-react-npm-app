pipeline {
    agent any

    tools { nodejs "nodejs" }
    
    stages {
        stage('Check Version'){
            steps {
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