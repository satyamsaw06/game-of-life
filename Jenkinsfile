pipeline {
  agent any
  tools {
    maven 'Maven 3.0.5'
  }
  stages {
    stage('Build') {
      steps {
        sh 'mvn clean install'
      }
    }
  }
}
