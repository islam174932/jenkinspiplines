pipeline {
    agent {
     docker {image 'node:16-alpine'}
    }
    stages {
        stage('Hello') {
            steps {
                sh 'java -version'
                echo "Get working directory"
                sh 'pwd'
            }
        }
    }
}
