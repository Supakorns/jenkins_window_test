
pipeline{
	agent {
		label 'windows'
  	}
	stages{
		stage('Clone repository') {
			/* Cloning the Repository to our Workspace */

			checkout scm
		}
		stage('copy folder') {
			bat "move . C:\tiramitsu" 
		}
	}
}
