+++
title = "Deploying Dremio Workshop Infrastructure"
chapter = true
weight = 100
autoNav = true
+++

<center><h3>Deploying Dremio Workshop </h3></center>

<div style="text-align: justify">

    In this section, you will learn how to quickly deploy a Dremio environment on the AWS Marketplace using a CloudFormation Template. You will also run another Cloudformation template to set up infrastructure needed to do the workshop.  
    

    
    To setup workshop environment, follow these steps:
    
<ol>
   <li> Log into AWS account with your credentials. </li>
    
   <li> Launch the stack. <a href="https://console.aws.amazon.com/cloudformation/home?region=us-west-2#/stacks/new?stackName=dremio-workshop&templateURL=https://s3.amazonaws.com/lk-formation-sk.s3.amazonaws.com/create-dremioworkshop-infrastructure.yml" />Click Here</a>
    </li>
   <li>  Click `Next` till the end and then select acknowledgement checkbox. Then click "Create Stack"
    </li>
   <li>While Cloudformation stack is running, go to  <b>Services > EC2 > Network & Security > Key Pairs, and then choose Create Key Pair</b>. Name the key pair <b> "dremioworkshop" and click "Create Key Pair"</b>
    </li>
  <img src="../../images/dremio3a.png" style="margin:15px 0px; border:1px solid black"/></li>
 </li>
</ol>

</div>
