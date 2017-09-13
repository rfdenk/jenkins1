pipeline {
    agent {
        docker { image 'node:7-alpine' }
    }

    stages {
        stage('Check version') {
            steps {
                sh 'node --version'
            }
        }
    }    
}
