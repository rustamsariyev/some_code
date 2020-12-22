pipeline {
  agent {
    label "master"
  }
  stages {


    stage('Change Display Name'){
        steps{
            script{
                currentBuild.displayName = "${SOURCEBRANCH}_${BUILD_NUMBER}"
            }
        }
    }  
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
