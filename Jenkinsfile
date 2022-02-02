pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'build project'
             sh 'npm install'
                
            }
        }
        stage('test') {
            steps {
                echo 'test project'
                sh './jenkins/scripts/test.sh'
            }
        }
    }
}
