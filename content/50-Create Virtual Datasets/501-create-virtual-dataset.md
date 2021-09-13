+++
title = "Creating a Virtual Dataset from the Data Lake Storage"
chapter = true
weight = 501
+++

<div style="text-align: left">
    
<ol>
       <li> From your Dremio Home Screen, click on your AWS S3 Storage Connection labeled <b>“AWS S3 Modernization Workshop”</b>  on the bottom left corner of your screen.  In the top center portion of your screen you will see a folder with the name <b>“dremio-data-lake-AccountID”</b>. Click on that folder then click <b>"dremioworkshopdata"</b>  folder and then click on the <b>“Trips”</b> Folder.  You should now see Parquet files.  
       
</li>
        <img src="../../images/dremio30.png" style="margin:15px 0px; border:1px solid black"/>
<li>
       In Dremio you can convert a folder of files into a single Physical Dataset (PDS).  Navigate your cursor to the top right of the screen and click on the  icon (image below) to turn the folder of Parquet files into a PDS.
        <img src="../../images/dremio32.png" style="margin:15px 0px; border:1px solid black"/>

</li>
<br/>
A pop-up window will appear.  Dremio recognizes specific formats and will structure the table accordingly.  For this table Dremio recognized that the folder it was combining was full or Parquet files.  You do not need to do anything further on this page, click <b>“Save”</b>.
        <img src="../../images/dremio31.png" style="margin:15px 0px; border:1px solid black"/>
        <li> You are now previewing the Physical Data Set in the Dremio Preview Window.  Notice the purple folder denoting a PDS in the top left corner of the screen. 
       
</li>
    
       Let’s explore the data set.  How many records are there? <br/>
        Type <b>SELECT count(*) FROM trips</b>
       into the SQL Editor and press Run. 
        <br/>
       There are 862,736,805 records in this data set.  

        
         <li> Notice that now the purple folder denoting a Physical Dataset has been replaced with a green table indicating a Virtual Dataset.  Since Dremio queries data directly on the Cloud Data Lake storage and does not copy data, when Dremio ran your query to count the number of records it automatically created a Virtual Dataset.  
 </li>
 <li> Enter <b>SELECT * FROM trips</b> into the SQL editor and click run. Notice the duration to run the query on the right side of the screen.  
      
</li>
</ol>
 <br/>
Next, we are going to save this VDS in our Dremio Home Space. Click the  save icon and save the VDS as <b>NYC_Taxi</b> to your Home Space. 
 <br/>

**Note your Home Space name will be your Dremio username preceeded with an @.  
  

       
    
</div>
