pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'here we start the pipeline'
          }
        }

        stage('test') {
          steps {
            echo 'test the application '
          }
        }

      }
    }

    stage('depoly') {
      steps {
        echo 'we depoly '
      }
    }

  }
}