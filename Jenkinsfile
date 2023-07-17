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
                sh " clean install /mnt/mavendeploybypipeline "
                
                
            }
        }
    }
}
