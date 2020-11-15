node {

    stage('Info') {
	// List branch here

	}
    stage('Unit Test') {
    	echo('Running Unit Tests...')
	sh('python -m pytest python/test_exponential.py')
    }

    stage('Deploy') {
        // Deploy to s3
    }

}
