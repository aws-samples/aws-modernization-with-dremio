+++
title = "Connect to S3"
weight = 301
chapter = true
+++

<center><h4>Connect to S3 Data Source </h4></center>

<div style="text-align: justify">
  <ol>
          <li>From the Dremio Home Screen Click the <b>+</b> icon next to <b>“Data Lakes”</b></li>
    <li> From the <b>“Add Data Lake”</b> box, click Amazon S3</li>
          <li>From the  “New Amazon S3 Source” Add the following information to the General tab:</li>
<ul>
           <li> <b> Name</b>: [AWS S3 Modernization Workshop]</li> 
            <li>  <b> AWS Access Key</b>:Go to IAM console and look for <b>dremio-user</b>,create access key under security credentials tab and use it</li> 
            <li>  <b> AWS Secret Key</b>: Go to IAM console and look for <b>dremio-user</b>,create secret key under security credentials tab and use it </li> 
              </ul>


Click <b>Save</b>.
<br/>
 Dremio is now connected to an AWS S3 bucket that contains NYC Taxi and Weather Data. The name of this bucket will be " dremio-data-lake-AccountID"
<li> To verify that Dremio is properly connected to AWS S3, under Data Lakes in the bottom left corner, you should see dremio datalake buckest listed </li>
</ol>

              



      
</div>
