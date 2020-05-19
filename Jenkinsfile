node {
 	// Clean workspace before doing anything
   
      
        stage ('Build') {
		sh "cat README.md"
        	sh "echo 'shell scripts to build project...'"
        }
        stage ('Tests') {
	        sh '''
		
		echo 'shell scripts to test to server...
		'''
        }
      	stage ('Deploy') {
            sh "echo 'shell scripts to deploy to server...'"
      	}
	 deleteDir()
    
}
