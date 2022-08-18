+++
title = "Connect to S3"
weight = 301
chapter = true
+++

<center><h4>Connect to S3 Data Source </h4></center>

<div style="text-align: justify">
  <ol>
          <li>Click “Add Data Lake” from the “Data Connection” pane on the bottom left of the Dremio home screen</li>
     <img src="../../images/newdremio13.png" style="margin:15px 0px; border:1px solid black"/>
     Select the  “Amazon S3” option and input the following information in the “General” tab:
        <img src="../../images/newdremio14.png" style="margin:15px 0px; border:1px solid black"/>
        <br/>
        
        Name: DevDay <br/>
        Authentication Method: Select “Data Source Credentials” <br/>
        Create IAM Role or Access Key: Select “Access Key” <br/>
        Access Key ID: Input your AWS Access Key <br/>
        Secret Access Key: Input your AWS Secret Access Key
        <br/>
        <br/>
        
        
    <b>**Note** </b><br/>
     When you created your lab environment, AWS created a new user called “dremio-user”. <br/> To get your Access Key ID & Access Secret Key, navigate to your AWS console and search <b> “Cloud Shell” </b>service. 
      <br/> 
     <img src="../../images/newdremio14-1.png" style="margin:15px 0px; border:1px solid black"/>
     <br/> Once the “Cloud Shell” terminal is prepared (~2 minutes), enter the following command:  <br/>
     
     <br/> 
     <b> “aws iam create-access-key --user-name dremio-user” </b> and press enter. <br/> <br/> AWS will generate a new Access Key ID & Access Secret Key for you to use. <br/>
     Copy the Access ID and Secret key as part of the json output on <b>Cloud Shell</b> to enter in the Dremio screen below.
     
     
      <img src="../../images/newdremio15.png" style="margin:15px 0px; border:1px solid black"/>
      
      Click <b>Save</b>
      
      Dremio is now connected to an AWS S3 bucket that contains NYC Taxi and Weather Data.  
      
      <li>To verify that Dremio is properly connected to AWS S3, under Data Lakes in the bottom left corner, click on the DevDay data connection.  You will see a list of buckets that you have access to.  Click on the dremio-data-lake-[AccountID] bucket. You should see two folders: one titled “nyc weather” and one titled “trips”. 
        </li>
        
          <img src="../../images/newdremio16.png" style="margin:15px 0px; border:1px solid black"/>
</ol>

              



      
</div>
