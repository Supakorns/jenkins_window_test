pipeline{
agent {node {  
	agent {
		label 'windows'
  	}}
 
	def app
	stage('Clone repository') {
		/* Cloning the Repository to our Workspace */

		checkout scm
	}

	stage('copy folder') {
		bat "move . C:\tiramitsu" 
	}
}
}
