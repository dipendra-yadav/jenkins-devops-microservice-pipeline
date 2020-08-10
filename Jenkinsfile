//SCRIPTED
/*node {
	stage('Build') {
		echo "Build"
	}
	stage('Test') {
		echo "Test"
	}
	stage('IntegrationTest') {
		echo "IntegrationTest"
	}
} */

//DECLARATIVE
pipeline {
	agent any
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

	
}

