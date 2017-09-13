pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'echo "OK"; exit 0'
            }
        }
        stage('Check') {
            steps {
                input "Check this to see if it is okay?"
            }
        }
    }    
}
