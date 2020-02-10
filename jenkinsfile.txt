pipeline{
	agent any
	stages{
		stage('Build'){
				steps{
					echo "Building"
				     }
			      }	
	      }
	stages{
		stage('Testing'){
				  steps{
					echo "Testing"
					}
				}
	      }
	stages{
		stage('Run'){
				steps{
					echo "Run"
				      }
			    }
	      }
	}	
