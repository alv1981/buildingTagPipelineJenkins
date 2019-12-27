pipeline {
    agent any
	
    stages {
        stage('Build') {
		
			when {
				changeset glob: "*jenkinsfile", caseSensitive: true
			}
		
            steps {                
                echo 'Hello change jenkinsfile'
            }
        }
    }
}
