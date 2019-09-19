node {  ' slave_node2_WinServe2019'  
	def app
	stage('Clone repository') {
		/* Cloning the Repository to our Workspace */

		checkout scm
	}

	stage('copy folder') {
		bat "move . C:\tiramitsu" 
	}
}
