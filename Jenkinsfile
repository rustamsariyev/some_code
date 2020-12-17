pipeline {
  agent {
    label "master"
  }
  
  triggers {
    cron('H/1 * * * *')
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
