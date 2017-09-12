pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'echo "FAIL"; exit 1'
            }
        }
    }
    post {
        always {
            mail to: "robertd@aegisgrp.com",
                subject: "FAILED",
                body: "It failed."       
        }
    }
}
