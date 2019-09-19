pipeline {
    agent { label 'windows'}
    stages {
        stage('Example Build') {
            steps {
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
