pipeline {
    agent any
	
    stages {
        stage('Build') {
		
			when{
				changeset glob: "*.js", caseSensitive: false
			}
		
            steps {                
                echo 'Hello World changeset JS'
            }
        }
    }
}
