pipeline{
    
    agent {
         
         label{
                label "built-in"
                customWorkspace "/mnt/mavendeploybypipeline"
         }
     
    }
    
    stages{
        stage("MAVENBUILDBYPIPELINE"){
            steps{
                cleanWs()
                sh " mvn clean install "
                
                
            }
        }
    }
}
