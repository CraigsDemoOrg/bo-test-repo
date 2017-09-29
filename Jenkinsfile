pipeline {
  agent any
  stages {
    stage('Stage 1') {
      steps {
        parallel(
          "Stage 1": {
            sh 'mvn -v'
            
          },
          "Stage 1a": {
            sh 'java -version'
            
          }
        )
      }
    }
  }
}