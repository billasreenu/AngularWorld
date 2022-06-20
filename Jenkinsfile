pipeline { 
    agent any 
     
    stages {
	    stage('Prepare') { 
            steps { 
                sh 'npm install' 
                sh 'npm audit fix' 
            }
        }
        stage('Build') { 
            steps { 
                sh 'npm build' 
            }
        }
         
    }
}