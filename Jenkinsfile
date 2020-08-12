//DECLARATIVE
pipeline {
	//agent any
	agent { docker 'maven:3-alpine' } 
	stages {
		stage('Build') {
			steps {
				echo  "build"
			}
		}

        stage('Test') {
			steps {
				echo  "Test"
			}
		}

		stage('Integration Test') {
			steps {
				echo  "Integration Test"
			}
		}
	
	}
	post {

        always {
			echo 'Im awesome.I run always'
		}
		success {
			echo 'I run when you are successful'
		}
		failure {
			echo 'I run when you fail'
		}


	}

	
}
