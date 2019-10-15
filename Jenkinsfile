pipeline {
    agent { label 'windows'}
    stages {
        stage('clone') {
            steps {
            	checkout scm
	    }
	}
	stage('Example Build') {
            steps {
		bat 'C:/Jenkins_Workspaces/workspace/clone_and_copy/jenkins.bat'
            }
        }

        /*
        stage('Example Deploy') {
            when {
                beforeInput true
                branch 'production'
            }
            input {
                message "Deploy to production?"
                id "simple-input"
            }
            steps {
                echo 'Deploying'
            }
        }
        */
    }
}
