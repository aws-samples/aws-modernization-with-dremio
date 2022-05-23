+++
title = "Deploying Dremio Workshop Infrastructure"
chapter = true
weight = 100
autoNav = true
+++

<center><h3>Deploying Dremio Workshop </h3></center>
    
   To setup workshop environment, follow these steps: 
## AWS-hosted Live event (workshop)

1. Use the hashcode provided by AWS team and enter it into to your AWS account. <a href="https://dashboard.eventengine.run/dashboard" target="_blank" />Event Engine - Team Dashboard <
1. Pick Email One Time Password OPT, accept the terms, and login.
1. Check your email for a one-time password to login. Afterward, you will see a dashboard.
1. Click on Set your Team Name in the dashboard by entering your name. This will help the workshop support team to help you troubleshoot when you need it.
1. Click on the AWS Console button. This will bring up a popup window AWS Console Login.
1. Click on Open AWS Console. This will log you into the <a href="https://us-east-1.console.aws.amazon.com/console/home?region=us-east-1"/> AWS account. </a> .
1. You will use this account for the entire workshop duration.
1. On the day of the workshop, you will Launch the stack. <a href="https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=dremio-workshop&templateURL=https://s3.amazonaws.com/lk-formation-sk.s3.amazonaws.com/create-dremioworkshop-infrastructure.yml" target="_blank" />launch the stack</a>  needed for the workshop. Click `Next` till the end and then select acknowledgement checkbox. Then click "Create Stack"

    
## Non-AWS-Hosted Event
    

   1. <a href="https://us-east-1.console.aws.amazon.com/console/home?region=us-east-1" target="_blank" />Login </a> to your AWS account.
   1. Launch the stack. <a href="https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=dremio-workshop&templateURL=https://s3.amazonaws.com/lk-formation-sk.s3.amazonaws.com/create-dremioworkshop-infrastructure.yml" target="_blank"  />Click Here</a>

Click `Next` till the end and then select acknowledgement checkbox. Then click "Create Stack"
  
   



