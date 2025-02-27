pipeline{
    agent any
    stages{
        stage('checkout'){
            steps{
                echo "checkout from main1"
            }
        }
        stage('build'){
            steps{
                echo "building pipeline from main1"
		echo "execute from main1"
	    }	
        }
	stage('test'){
	     steps{
		echo "testing pipeline from main1"
	     }
	}
    }
}
