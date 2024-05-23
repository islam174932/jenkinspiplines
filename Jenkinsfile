pipeline {
    agent {
        docker {
            image 'jenkins/inbound-agent'
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

