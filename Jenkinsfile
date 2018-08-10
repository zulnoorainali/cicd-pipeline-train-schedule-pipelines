Pipeline {
  agent any
  stages {
   stage {“build”} {
    steps {
     echo “running build automation”
     Sh ‘./gradlew build –no-daemon’
     archiveArtifacts artifacts: ‘dist/trainSchedule.zip’
    }
  }
 }
}
