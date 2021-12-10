pipeline {
	agent any 
		stages{
			stage('Build'){
				steps{
					echo "This is build Stage";
				}
			}
			stage('Test'){
				steps{
					echo "This is Test Stage";
				}
			}
			stage('Deploy'){
				steps{
					echo "This is Deploy Stage";
				}
			}
		}
	
	post{
		always{
			echo "This is always run";
		}
		success{
			echo "This is always success";
		}
		failure{
			echo "This is always failure";
		}
		unstable{
			echo "This is always unstable";
		}
		changed{
			echo "This is always changed";
		}
	}
}
