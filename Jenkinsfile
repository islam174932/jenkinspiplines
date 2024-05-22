pipeline {
    agent {
        docker {
            image 'slave'
            
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
