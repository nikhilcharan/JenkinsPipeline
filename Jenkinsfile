pipeline{
    agent any
    stages{
        
        stage("clone"){
            
            steps{
            echo "Hello world"
                
             def ticketVal=input message: 'Enter JIRA ticket', parameters: [string(defaultValue: '', description: '', name: 'ticket'), string(defaultValue: '', description: '', name: 'date')], submitter: 'root'
             echo(ticketVal['date'])
                
            }
            
            
              post{
                  
                  echo "Post"
            
        }
        
            
            
            
            
            
        }
        
      
        
    }
    
    
    
}
