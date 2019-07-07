pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        powershell 'powershell mvn package'
      }
    }
  }
}