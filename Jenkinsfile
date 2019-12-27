pipeline {
    agent any
	
    stages {
        stage('Build') {
		
			when {
				changeset glob: "*Jenkinsfile", caseSensitive: true
			}
		
            steps {                
                echo 'Hello change jenkinsfile'
            }
        }
    }
}
