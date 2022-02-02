pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'build project'
             bat "npm install"
                
            }
        }
        stage('test') {
            steps {
                echo 'test project'
                bat "npm test"
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
