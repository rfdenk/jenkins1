pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'echo "OK"; exit 0'
            }
        }
        stage('Check') {
            input "Check this"
        }
    }    
}
