pipeline{
    agent any
    stages{
        
        stage("clone repo"){
         
            steps{
                
                git url:"https://github.com/sumeshkanayi/Webapp.git", branch:"master", credentialsId:"mygithub"
                
            }
        }
        
        
           stage("build using maven"){
         
            steps{
                
                
                sh 'mvn clean install -f trucks/pom.xml'
                
            }
        }
        
        
        
        
    }
    
    
    
}
