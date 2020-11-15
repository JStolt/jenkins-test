node {

    def workspace = WORKSPACE

    stage('Info') {
	// List branch here
	echo(${workspace})
	}
    stage('Unit Test') {
    	echo('Running Unit Tests...')
	sh('pytest ${workspace}/python/test_exponential.py')
    }

    stage('Deploy') {
        // Deploy to s3
    }

}
