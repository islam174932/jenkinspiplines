pipeline {
    agent {
        docker {
            image 'jenkins/slave'
            args '-v /jenkins/workspace:/jenkins/workspace -w /jenkins/workspace'
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
