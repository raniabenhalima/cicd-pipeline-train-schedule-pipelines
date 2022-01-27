pipline {
  agent any
  stages {
    stage ('build') {
    steps {
      echo "Running build automation"
      sh "./gradlew build --no-deamon"
      archiveArtifacts artifacts "dist/test.zip"  
          }
    }
  }
}
