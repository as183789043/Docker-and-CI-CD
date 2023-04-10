pipeline {
  agent any
  stages {
    stage('Stage Init') {
      parallel {
        stage('Stage Init') {
          steps {
            sh 'TZ=\'Asia/Taipei\'; export TZ'
            echo 'change time zone'
          }
        }

        stage('Stage AAA') {
          steps {
            sh 'DATE=$(date "+%H-%M-%S")'
          }
        }

      }
    }

  }
}