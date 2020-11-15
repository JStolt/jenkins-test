node {

    stage('Info') {
	// List branch here

	}
    stage('Unit Test') {
    	echo('Running Unit Tests...')
	echo('python --version')
	sh('python -m install pytest')
	echo('pytest --version')
	echo('python -m pytest --version')
	sh('python -m pytest python/test_exponential.py')
    }

    stage('Deploy') {
        // Deploy to s3
    }

}
