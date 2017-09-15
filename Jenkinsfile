pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'mvn -v'
      }
    }
    stage('Read Pom File') {
      steps {
        readMavenPom(file: 'pom.xml')
      }
    }
  }
}