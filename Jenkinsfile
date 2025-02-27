pipeline{
    agent any
    stages{
        stage('checkout'){
            steps{
                echo "checkout"
            }
        }
        stage('build'){
            steps{
                echo "building pipeline stage"
				echo "execute"
			}	
            	
        }
		stage('test'){
			steps{
				echo "testing pipeline"
			}
		}
		stage('approval'){
			steps{
				echo "approval needed"
			}
		}	
		stage('deploy'){
			steps{
				echo "deploy"
			}
		}	
    }
}
