+++
title = "Creating Physical Dataset"
chapter = true
weight = 801
+++

<div style="text-align: left">

<ol>
 <li> In Dremio, navigate to the Dremio Home Screen and click on your S3 bucket in the bottom left corner of the screen.  Click on the “dremio-data-lake-[AccountID]” folder and notice that you have a folder that says nyc weather.</b>.  
</li>
                            <img src="../../images/newdremio48.png" style="margin:15px 0px; border:1px solid black"/>

<li>Click on the <b>nyc weather</b> folder and notice one Parquet file.  We are going to convert this to a PDS by clicking <b>“Format File”</b> under Action.   
</li>
     <img src="../../images/newdremio49.png" style="margin:15px 0px; border:1px solid black"/>
         <li>The format box will appear, click <b>Save.</b>  </li>
         <li>
          You will now see a preview of the table that shows the different fields in the dataset.  
         Click the “Save View” and save the dataset as nyc_weather  to your Space.  
          <img src="../../images/newdremio50.png" style="margin:15px 0px; border:1px solid black"/>
          Navigate back to your Dremio Home Screen and under your Home Space you should see three different Virtual Datasets. 
        <img src="../../images/newdremio51.png" style="margin:15px 0px; border:1px solid black"/>
         </li>
          </ol>
         <br/>
     
</div>
