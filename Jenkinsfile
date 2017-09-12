pipeline {
    agent {
        docker { image 'python' }
    }
    stages {
        stage('Test') {
            steps {
                python --version
            }
        }
    }
}
