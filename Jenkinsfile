pipeline {
 agent any
  stages {
    stage ('Build') {
      echo 'Running the Build'
      sh './gradlew build --no-daemon'
      archiveArtifacts artifacts: 'dist/traiSchedule.zip'
    }
  }
}
