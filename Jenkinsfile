pipeline{
	agent any
	
	stages {
		stage('Build') {
		  steps {
		sh "echo 'first Build from git'"
			}
		}
		stage('Test') {
		  steps {
		sh "echo 'first Test from git update for hook'"
			}
		}
		stage('Deploy') {
		  steps {
		sh "echo 'first Deploy from git'"
			}
		}
}
}
