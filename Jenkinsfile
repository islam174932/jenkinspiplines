pipeline {
    agent {
        label 'slaveing'
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
