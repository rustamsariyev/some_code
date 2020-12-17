pipeline {
  agent any
  stages {
    stage('echo') {
      steps {
        echo 'Hello'
      }
    }

  }
  triggers {
    cron('H/15 * * * *')
  }
}