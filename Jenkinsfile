pipeline{
	agent any
	stages{
		stage('Build'){
			steps{
				echo 'Building...'
			}
		stage('Unit Test'){
			steps{
				echo 'Running the unit test.....'
			}
		stage('Integration Test'){
			steps{
				echo 'Running the integration test..'
			}
		stage('Deploy to Prod'){
			steps{
				input('Do you want to deploy to prod')
			}
			steps{
				echo 'Deploying...'
			}		
	}
}
