+++
title = "Creating a Virtual Dataset from the Data Lake Storage"
chapter = true
weight = 501
+++

<div style="text-align: left">
    
<ol>
       <li>  From your Dremio Home Screen, click on your AWS S3 Storage Connection labeled “DevDay” on the button on the bottom left corner of your screen.  In the top center portion of your screen you will see a folder titled “dremio-data-lake-[AccountID]”. Click on that folder then click on the “Trips” Folder.  You should now see Parquet files.    
       
</li>
        <img src="../../images/newdremio17.png" style="margin:15px 0px; border:1px solid black"/>
<li>
       In Dremio you can convert a folder of files into a single Physical Dataset (PDS).  Navigate your cursor to the top right of the screen and click on the  icon            to turn the folder of Parquet files into a PDS.
        <br/>
        A pop-up window will appear.  Dremio recognizes specific formats and will structure the table accordingly.  For this table Dremio recognized that the folder it was combining was full or Parquet files.  You do not need to do anything further on this page, click “Save”.
        
        <img src="../../images/newdremio18.png" style="margin:15px 0px; border:1px solid black"/>

</li>

<li>You are now previewing the Physical Data Set in the Dremio Preview Window.  Notice the purple folder denoting a PDS in the top left corner of the screen. </li>
<br/>

  <img src="../../images/newdremio19.png" style="margin:15px 0px; border:1px solid black"/>
          <br/>
         Let’s explore the data set.  How many records are there?  Type SELECT count(*) FROM trips
            into the SQL Runner and press Run. 
            <br/>
            There are 862,736,805 records in this data set.   

 <br/>
        <li> You are now previewing the Physical Data Set in the Dremio Preview Window.  Notice the purple folder denoting a PDS in the top left corner of the screen. 
       
</li>
    
       Let’s explore the data set.  How many records are there? <br/>
        Type <b>SELECT count(*) FROM trips</b>
       into the SQL Editor and press Run. 
        <br/>
       There are 862,736,805 records in this data set.  

        <img src="../../images/newdremio20.png" style="margin:15px 0px; border:1px solid black"/>
        
        Navigate back on your browser to return to the screen with your original query (SELECT (*) FROM trips)
         
 <br/>

Next we are going to save this table as a Virtual Dataset (VDS)  in our Dremio Space. Click the “Save View” button in the top right corner of your screen and save the VDS as NYC_Taxi to the space you created for this lab (in the save screen, this will appear underneath your personal folders).

<img src="../../images/newdremio21.png" style="margin:15px 0px; border:1px solid black"/>
</ol>
 
  

       
    
</div>
