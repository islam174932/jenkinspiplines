pipeline {
    agent {
        docker {
            image 'jenkins/slave'
        }
    }
    stages {
        stage('Hello') {
            steps {
                sh 'node --version'
            }
        }
    }
}
