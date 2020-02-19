pipeline {
    agent {
        docker { image 'cicd-buzz' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}
