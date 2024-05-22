pipeline {
    agent {
        docker {
            image 'node:16-alpine'
            args '-v /your/host/workspace:/workspace -w /workspace'
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
