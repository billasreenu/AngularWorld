pipeline { 
    agent any 
     
    stages {
	    stage('Prepare') { 
            steps { 
                npm install
            }
        }
		 
        stage('Build') { 
            steps { 
                npm build
            }
        }
         
    }
}