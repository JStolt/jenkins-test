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
		    		sh('pytest ./python/test_exponential.py')
			    }
		    }
		    stage('Deploy') {
			    steps{
			    sh('aws s3 ls --endpoint http://localhost:8000/ s3://localhost/mybucket')
			    }
		    }
	    }
}
