node {
	stage 'Checkout'
		checkout scm

	stage 'Build'
		sh('docker build .')

	stage 'Test'
		sh('echo "Working on Test"')

}
