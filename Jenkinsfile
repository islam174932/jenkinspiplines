pipeline {
    agent {
        docker {
            image 'node:16-alpine'
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
