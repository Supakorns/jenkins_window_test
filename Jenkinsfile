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
                bat 'xcopy C:/Jenkins_Workspaces/workspace/clone_and_copy C:/Users/Administrator/Desktop/1234 /O /X /E /H /K'
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
