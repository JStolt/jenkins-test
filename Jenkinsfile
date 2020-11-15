node {


    stage('Info') {
	// List branch here
	echo "${env.WORKSPACE}"
	}
    stage('Unit Test') {
    	echo('Running Unit Tests...')
	sh('pytest ${env.WORKSPACE}/python/test_exponential.py')
    }

    stage('Deploy') {
        // Deploy to s3
    }

}
