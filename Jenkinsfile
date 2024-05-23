pipeline {
    agent {
        docker {
            image 'jenkins/slave:latest'
            label 'slave'
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

