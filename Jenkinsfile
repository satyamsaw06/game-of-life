pipeline {
  agent {
    label{
      label "built-in"
      customWorkspace "/mnt/gameoflifewar/"
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
