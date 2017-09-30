node {
	stage 'Checkout'
		checkout scm

	stage 'Build'
		sh('sudo docker build .')

	stage 'Test'
		sh('echo "Testing"')

}
