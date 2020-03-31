node {
	stage('Build') {
		echo "Build"
	}
	stage('Test') {
		echo "Test"
	}
}
pipeline {
	agent {docker {image 'maven:3.6.3'}}
	stages {
		stage('build'){
			step{
				echo "mvn --version"
				echo "build"
			}
		}
	}
}