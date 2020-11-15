node {

    stage('Info') {
	// List branch here

	}
    stage('Unit Test') {
    	echo('Running Unit Tests...')
	sh('pytest python/test_exponential.py')
    }

    stage('Deploy') {
        // Deploy to s3
    }

}
