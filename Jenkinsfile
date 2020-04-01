pipeline{
	agent any
	stages{
		stage('Build'){
				steps{
					echo "Building job is running"
					apt-get update
					apt-get install apache2
					service apache2 start
				     }
			      }	
	     
		stage('Testing'){
				  steps{
					echo " now Testing"
					}
				}
	      
		stage('Run'){
				steps{
					echo "Project is Run"
				      }
			    }
	     }
	}	
