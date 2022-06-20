pipeline { 
    agent any 
     
    stages {
	    stage('Prepare') { 
            steps { 
                npm install
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