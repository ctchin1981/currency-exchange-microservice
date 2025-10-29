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
	}
	post {
		always {
			echo "Always printed"
		}
		success {
			echo "Print when success"
		}
		failure {
			echo "print when failed"
		}
	}
}
