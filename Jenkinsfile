pipeline { 
    agent any 
     
    stages {
	    stage('NpmInstall') { 
            steps { 
                npm install
            }
        }
		stage('NpmAuditFix') { 
            steps { 
                npm audit fix
            }
        }
        stage('Build') { 
            steps { 
                npm build
            }
        }
         
    }
}