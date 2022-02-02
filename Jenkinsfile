pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'build project'
             sh "npm install"
                
            }
        }
        stage('test') {
            steps {
                echo 'test project'
                sh "npm test"
            }
        }
       stage('Deploy')
		{
			steps
			{
			
				        echo 'deploy project'
				
			}
		}
    }
}
