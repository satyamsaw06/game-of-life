pipeline {
  agent any
    
  tools {
    maven 'Maven'
  }
  stages {
    stage('Build') {
      steps {
        cleanWs()
        sh 'mvn clean install'
      }
    }
  }
}
