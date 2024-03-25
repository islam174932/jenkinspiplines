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

        stage('Test') {
          steps {
            echo 'test the application '
            echo "get the driver path ${androiddriver}"
          }
        }

      }
    }

    stage('DeplOy') {
      steps {
        echo 'we deploy '
        input(message: 'DO you want deploy?', id: 'ok')
      }
    }

  }
  environment {
    androiddriver = 'D:\\Demo\\Android.SauceLabs.Mobile.Sample.app.2.7.1'
  }
}