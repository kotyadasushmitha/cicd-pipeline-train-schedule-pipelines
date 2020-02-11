pipeline {
  agents any {
    stages {
      stage('Build') {
        steps {
        echo 'Running build automation'
        sh './gradlew build --no-daemon'
        acrviveArtifacts artifact: 'dist/trainSchedule.zip'
        }
      }
    }
  }
}
