pipeline{
    agent any
    stages{
        
        stage("clone"){
            
            steps{
            echo "Hello world"
                script{
             def ticketVal= input message: 'Enter JIRA ticket', parameters: [string(defaultValue: '', description: '', name: 'ticket')], submitter: 'root'
             echo(ticketVal)
                }
            }
        }
        
        
        
    }
    
    
    
}
