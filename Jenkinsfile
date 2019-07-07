    
pipeline{	
    agent any
     tools {
        maven 'Maven 3.6.1'
        jdk 'java8'
    }
 	
    stages{	
        stage('Build'){	
            steps{	
                echo "setting current build to unstable"
                sh 'mvn clean install'	
               	
            }	
        }	
        stage('Deploy'){	
            steps{	
                echo "deploy is running"	
            }	
        }        	
    }	
}
