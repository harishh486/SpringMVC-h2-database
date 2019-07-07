    
pipeline{	
    agent any
 	
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
