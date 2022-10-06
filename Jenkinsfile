pipeline {
	agent any
	
	stages {
		stage('Build') {
			steps {
				echo "Build"
			}
		}
		stage('Test') {
			steps {
				echo "Test"
			}
		}
		stage('Integration Test') {
			steps {
				echo "Integration Test"
			}
		}
	} 
	
	post {
		always {
			echo "Finished."
		}
		success {
			echo "Everything is successful"
		}
		failure {
			echo "Failure"
		}
	}
	
}
