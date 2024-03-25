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

        stage('Test2') {
          steps {
            waitUntil() {
              sleep 3
            }

          }
        }

      }
    }

    stage('file') {
      steps {
        archiveArtifacts 'Logfile.txt'
      }
    }

  }
  environment {
    androiddriver = 'D:\\Demo\\Android.SauceLabs.Mobile.Sample.app.2.7.1'
  }
}