+++
title = "Configuring and Launching  Dremio"
chapter = true
weight = 1012
+++

<div style="text-align: justify">
    <center><h2>Configuring and Launching the Dremio CloudFormation Template</h2></center>

    
    <br/><br/>
    
   <ol>
        <li>From the “Cloud Connection” screen, click “Launch Stack” .</li>
         <img src="../../images/newdremio4.png" style="margin:15px 0px; border:1px solid black"/>
        <li> “Launch Stack” will take you to the AWS cloud formation template. Enter the following: </li>
      <br/>
      Stack Name: Dremio-DevDay <br/>
      VPC: Select the VPC that is associated with dremioWorkshop <br/>
      Subnets: Select the <b>PUBLIC subnet</b> that is associated with dremioWorkshop 
        <img src="../../images/newdremio5.png" style="margin:15px 0px; border:1px solid black"/>
        <img src="../../images/newdremio6.png" style="margin:15px 0px; border:1px solid black"/>
        <br/>
        Check “I acknowledge that AWS CloudFormation might create IAM resources.”
        <br/>
        <br/>
        
        <li>Click “Create Stack” </li>
           At this point, AWS is creating the Cloud Formation template. Click back into your Dremio Cloud tab and you should see Dremio Cloud creating and connecting to the stack.
         <li>Once Dremio successfully connects to AWS, the next step will be to add additional Dremio users to your Dremio Cloud project. For the purposes of this workshop, we will not be adding any additional users. Click “Finish” to create your project.</li>

         <img src="../../images/newdremio7.png" style="margin:15px 0px; border:1px solid black"/>

        
   </ol>

   
</div>
