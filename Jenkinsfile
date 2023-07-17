pipeline{
    
    agent {
         
                label "built-in"  
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
