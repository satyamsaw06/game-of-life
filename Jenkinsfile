pipeline{
    
    agent {
         
         label{
                label "built-in"
                customWorkspcae "/mnt/mavendeploybypipeline"
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
