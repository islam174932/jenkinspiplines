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
            echo "get the driver path$${androiddriver}"
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
  environment {
    androiddriver = 'D:\\Demo\\Android.SauceLabs.Mobile.Sample.app.2.7.1'
  }
}