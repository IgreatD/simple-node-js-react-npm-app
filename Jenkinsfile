pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
        stage('Start') { 
            steps {
                sh 'npm run start' 
            }
        }
    }
}
