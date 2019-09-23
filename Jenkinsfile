pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
      exho 'Running Build Automation'
      sh './gradlew build --no-daemon'
      archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
