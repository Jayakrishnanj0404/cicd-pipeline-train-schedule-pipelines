pipeline{
  agent any
    stages{
      stage ('Build'){
        steps {
          echo 'Running build Automation'
          sh './gradlew build --no-daemon'
          archiveartifacts artifacts: 'dist/trainSchedule.zip'
        }
      }
    }
  }
