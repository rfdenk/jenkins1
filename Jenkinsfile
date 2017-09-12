pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'echo "OK"; exit 0'
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
