pipeline{
    agent any
    stages{
        stage('checkout'){
            steps{
                echo "checkout from main"
            }
        }
        stage('build'){
            steps{
                echo "building pipeline from main"
		echo "execute from main"
	    }	
        }
	stage('test'){
	     steps{
		echo "testing pipeline from main"
	     }
	}
    }
}
