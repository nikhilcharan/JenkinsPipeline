node
{
stage 'starting'
  
  sh "echo 'hello world'"
  stage 'clone repo'
  git 'https://github.com/sumeshkanayi/JenkinsPipeline.git'
  stage 'list contents'
  sh 'ls'
  
  def approval=input message: 'Please approve', ok: 'Do you approve?', parameters: [string(defaultValue: 'devops-321', description: '', name: 'jira_ticket')], submitter: 'root', submitterParameter: 'approver'
  
  stage 'print the JIRA ticket'
echo(approval['jira_ticket'])
  
  
  }
