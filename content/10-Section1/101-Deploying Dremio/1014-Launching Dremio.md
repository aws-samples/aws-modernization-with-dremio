+++
title = "Launching Dremio and Setting up a Dremio Project"
chapter = true
weight = 1014
+++

<div style="text-align: justify">
    <center><h2>Launching Dremio and Setting up a Dremio Project</h2></center>

   <br/><br/>
       
     
  After clicking on the IP Address under Outputs you will be brought to Dremio’s AWS Edition.  Dremio will automatically look for any projects that are already available before having you set up your own project. 
       <img src="../../images/dremio11.png" style="margin:15px 0px; border:1px solid black"/>
       <img src="../../images/dremio12.png" style="margin:15px 0px; border:1px solid black"/>
             <ol>
           <li> Authenticating your AWS Instance: </li>
  
           <b>(This is only applicable if you have existing project, else skip to "Create a  Project")</b>   </br>
           On the Authentication Screen (pictured above) Dremio will need to verify the EC2 instance ID that you are using.  Dremio will automatically add your Instance ID.  Once your Instance ID has populated, press Authenticate.

   <br/>
  <li> Creating a Project:</li>
   Dremio allows users to create Projects which are separate instances of Dremio that do not share any data or resources.  Projects can be managed independently of each other.  Dremio allows for multiple Projects to be created within a single AWS account.  
           
    Under the “Create a Project” screen, click <b>“Create Project”</b>
     
   <img src="../../images/dremio13.png" style="margin:15px 0px; border:1px solid black"/>
   
   <li>Setting up your project</li>
           </br>
           For this page, fill in the necessary information to create a Dremio Project:
<br/>
<ul>
<li>Under Project Name input: Dremio Modernization Workshop</li>
<li>Under Initial Engine Configuration: Leave the default of Medium (4 nodes)</li>
<li>Enable Automatic Backups: Turn off </li>
<li>IAM Role: Default</li>
</ul>
 <br/>
Your inputs should look like the image below:
<img src="../../images/dremio14.png" style="margin:15px 0px; border:1px solid black"/>

Once complete, click <b>Create</b>


<li> Creating Project Environment </li>

Dremio will automatically create your Project Environment by deploying the EC2 Instances, connecting the Instances to a S3 bucket and allocating the EBS & EFS storage.  This step should take no more than 5 minutes to complete.  You will see green check marks appear as each step is completed.


<img src="../../images/dremio15.png" style="margin:15px 0px; border:1px solid black"/>

      
      
<li>Registering for your Dremio Account & Project</li>
<br/>
Once the setup is complete, you will need to accept Dremio’s License and Services Agreement by clicking <b>“I Accept”</b>
<img src="../../images/dremio16.png" style="margin:15px 0px; border:1px solid black"/>
<br/>
Next you will need to create your Admin Account in Dremio by filing out the Admin Account Information. 
       <img src="../../images/dremio17.png" style="margin:15px 0px; border:1px solid black"/>
       <br/>
       Once you have filled out all the information, click Next to be taken do the Dremio User-Interface. 
       </ol>

   




</div>
