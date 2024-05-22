pipeline {
    agent {
        docker {
            image 'jenkins/slave'
            args '-w ${pwd()}'
        }
    }
    stages {
        stage('Hello') {
            steps {
                sh 'echo "Hello, World!"'
            }
        }
    }
}
