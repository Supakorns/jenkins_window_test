pipeline {
    agent { label 'windows'}
    stages {
        stage('clone') {
            steps {
		bat 'cd C:/Users/Administrator/Desktop/1234'
		bat 'git clone https://github.com/Supakorns/jenkins_window_test.git'
            }
	}/*
	stage('Example Build') {
            steps {
                bat 'xcopy C:/Jenkins_Workspaces/workspace/clone_and_copy C:/Users/Administrator/Desktop/1234 /c /g /d /i /e /r /h /y'
            }
        }*/

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
