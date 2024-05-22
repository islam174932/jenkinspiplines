pipeline {
    agent {
        docker {
            image 'jenkins/slave'
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
