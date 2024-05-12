pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'test message'
          }
        }

        stage('Test2') {
          steps {
            echo 'we test'
          }
        }

      }
    }

  }
  environment {
    androiddriver = 'D:\\Demo\\Android.SauceLabs.Mobile.Sample.app.2.7.1'
  }
}