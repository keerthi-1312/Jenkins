pipeline{
    agent any
    stages{
        stage('checkout'){
            steps{
                echo "checkout from main2"
            }
        }
        stage('build'){
            steps{
                echo "building pipeline from main2"
		echo "execute from main"
	    }	
        }
	stage('test'){
	     steps{
		echo "testing pipeline from main2"
	     }
	}
    }
}
