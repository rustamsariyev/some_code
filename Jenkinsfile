pipeline {
  agent {
    label "master"
  }
  stages {
    stage('echo') {
      steps {
        echo 'Hello gitpulling'
      }
    }

  }
  triggers {
    cron('H/15 * * * *')
  }
}
