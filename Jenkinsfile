pipeline {
    agent any
	    stages {
		    stage('Info') {
		    // List Branch here
			    steps {
			    echo "${env.WORKSPACE}"
			    }
		    } 
		    stage('Unit Test') {
			    steps {
		    		echo "Running Unit Tests..."
		    		sh('pytest ${env.WORKSPACE}/python/test_exponential.py')
			    }
		    }
		    //stage('Deploy') {
		    // Deploy to s3
		    //}
	    }
}
