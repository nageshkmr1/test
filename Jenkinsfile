node {
 	// Clean workspace before doing anything
   
      
        stage ('Build') {
		sh "cat README.md"
        	sh "echo 'shell scripts to build project...'"
        }
        stage ('Tests') {
	        sh """
		
		echo 'shell scripts to test to server...'
		
		"""
        }
      	stage ('Deploy') {
            sh "echo 'shell scripts to deploy to server...'"
      	}

	 deleteDir()
    
}
def notifyStarted() {
		emailext (
      subject: "STARTED: Job '${env.JOB_NAME} [${env.BUILD_NUMBER}]'",
      body: "nageshkmr1@gmail.com"
STARTED: Job '${env.JOB_NAME} [${env.BUILD_NUMBER}]':


        
Check console output at "${env.JOB_NAME} [${env.BUILD_NUMBER}]"

""",
      recipientProviders: [[$class: 'DevelopersRecipientProvider']]
    )
    }
