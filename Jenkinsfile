pipeline {
    agent {
        docker {
            image 'jenkins/inbound-agent:latest'
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
