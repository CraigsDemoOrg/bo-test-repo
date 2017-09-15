pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'mvn -v'
      }
    }
    stage('') {
      steps {
        readMavenPom(file: 'pom.xml')
      }
    }
  }
}