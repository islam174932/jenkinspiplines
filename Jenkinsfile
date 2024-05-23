pipeline {
    agent {
        docker {
            image 'jenkins/slave'
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

