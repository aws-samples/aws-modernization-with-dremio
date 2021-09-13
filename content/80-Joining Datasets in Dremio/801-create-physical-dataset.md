+++
title = "Creating Physical Dataset"
chapter = true
weight = 801
+++

<div style="text-align: left">

<ol>
 <li> In Dremio, navigate to the Dremio Home Screen and click on your S3 bucket in the bottom left corner of the screen.  Click on the same named <b>“dremio-data-lake-AccountID”</b> in the middle of the screen, then click on "dremioworkshopdata" and notice that you have a folder that says <b>nyc weather</b>.  
</li>
                            <img src="../../images/dremio61.png" style="margin:15px 0px; border:1px solid black"/>

<li>Click on the <b>nyc weather</b> folder and notice one Parquet file.  We are going to convert this to a PDS by clicking <b>“Format File”</b> under Action.   
</li>
     <img src="../../images/dremio62.png" style="margin:15px 0px; border:1px solid black"/>
         <li>The format box will appear, click <b>Save.</b>  </li>
         <li>
          You will now see a preview of the table that shows the different fields in the dataset.  
         </li>
          </ol>
         <br/>
       Click the  save icon to save  the dataset as <b>nyc_weather</b>  to your Dremio Home Space.  Navigate back to your Dremio Home Screen and under your Home Space you should see three different Virtual Datasets. 
   
                          <img src="../../images/dremio63.png" style="margin:15px 0px; border:1px solid black"/>
</div>
