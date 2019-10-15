pipeline {
    agent { label 'windows'}
    stages {
        stage('Example Build') {
            steps {
		bat "cd /Users/Administrator/Desktop/1234"
                checkout scm
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
