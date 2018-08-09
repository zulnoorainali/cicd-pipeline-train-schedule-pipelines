Pipeline {
  Agent any
  Stages {
   Stage {“build”} {
    Steps {
     Echo “running build automation”
     Sh ‘./gradlew build –no-daemon’
     archiveArtifacts artifacts: ‘dist/trainSchedule.zip’
    }
  }
 }
}
