
pipeline{
	agent {
		label 'windows'
  	}
	stages{
		step('Clone repository') {
			/* Cloning the Repository to our Workspace */

			checkout scm
		}
		step('copy folder') {
			bat "move . C:\tiramitsu" 
		}
	}
}
