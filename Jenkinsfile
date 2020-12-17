pipeline {
  agent {
    label "master"
  }
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
