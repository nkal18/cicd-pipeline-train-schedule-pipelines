pipeline {
agent any

  stages {

    stage ('Build') {
      steps {
      
        echo 'running the build'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      
      }
    
    }

  }

}
