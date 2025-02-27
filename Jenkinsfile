pipeline{
    agent any
    stages{
        stage('checkout'){
            steps{
                echo "checkout from main-1"
            }
        }
        stage('build'){
            steps{
                echo "building pipeline from main-1"
		echo "execute from main-1"
	    }	
        }
	stage('test'){
	     steps{
		echo "testing pipeline from main-1"
	     }
	}
    }
}
