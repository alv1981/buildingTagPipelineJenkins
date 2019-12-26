pipeline {
    agent any
	
    stages {
        stage('Build') {
		
			when{
				changeset pattern: "*/*jenkinsfile", caseSensitive: true 
			}
		
            steps {                
                echo 'Hello World building tag'
            }
        }
    }
}
