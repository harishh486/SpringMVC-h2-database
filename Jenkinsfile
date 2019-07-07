    
pipeline{	
    agent any
     tools {
        maven 'Maven 3.6.1'
    }
 	
    stages{	
        stage('Build'){	
            steps{	
                echo "setting current build to unstable"
                sh 'mvn clean'	
               	
            }	
        }	
        stage('Deploy'){	
            steps{	
                echo "deploy is running"	
            }	
        }        	
    }	
}
