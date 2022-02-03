pipeline {
    agent any
    stages {
        stage('CleanWorkspace') {
            steps {
                cleanWs()
            }
        }
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
    }
}
