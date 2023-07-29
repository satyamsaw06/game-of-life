
pipeline {
  agent {
	  label {
		label 'built-in'
		customWorkspace '/mnt'
	  }
  }
  tools {
    maven 'Maven'
  }
  stages {
    stage('Build') {
		steps {
        sh 'mvn clean install'
      }
    }
	stage('Deploy') {
		steps {
		sh 'cp -r /root/.jenkins/workspace/gameoflifewardeploy/gameoflife-web/target/gameoflife.war /mnt/servers/apache-tomcat-9.0.78/webapps/'
		sh 'chmod -R 777 /mnt/servers/apache-tomcat-9.0.78/webapps/gameoflife.war'
		}
	 }	
  }
}
