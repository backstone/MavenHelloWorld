pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        powershell 'powershell e:\\Frameworks\\apache-maven-3.5.2\\bin\\mvn  package'
      }
    }
  }
}