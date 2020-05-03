pipeline {
	
	agent {
		docker {
			image 'jenkins-test:1.0.0'
                        label 'jenkins-slave'
		}
	}
	
stages{

	stage("Build") {
		steps {
			echo 'Building the application'
		}
	}
	stage("Test") {
		steps {
			echo 'Testing the application'
		}
	}
	stage("Deploy") {
		steps {
			echo 'Building the application'
		}
	}
}
}
