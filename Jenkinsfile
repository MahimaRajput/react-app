pipeline {
    agent any
    stages {
       stage('Checkout') 
		{
			steps 
			{
				git branch: 'master',
				credentialsId: '0f5a239d-86ca-4a61-bad1-a36f80b67ac6',
				url: 'https://github.com/MahimaRajput/react-app'
				
				stash includes: '**', name: 'builtSources'
			}
		}
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
    }
}
