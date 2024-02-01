pipeline { 
  agents any
  stages {
    stage ('Build') {
      steps {
        echo 'Running build automation'
        sh './grandlew view --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
