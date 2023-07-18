pipeline {
  agent {
    label{
      label "built-in"
      
    }
  }
    
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
