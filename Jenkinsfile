pipeline {
    agent { label 'windows'}
    stages {
        stage('Example Build') {
            steps {
                checkout scm
            }
        }
		stage('copy folder'){
            steps{
                bat "xcopy . C:/Users/Administrator/Desktop/1234 /s /e /y /i"

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
