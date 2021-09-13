+++
title = "Reviewing count of records by Date"
chapter = true
weight = 751
+++

<div style="text-align: left">
    </div>
    <ol>
       <li> Navigate back to your Tableau Online Workbook which should still show the count of NYC_Taxi records. 

</li>
     <li> Count the records by pickup date by dragging the pickup_date dimension to the column bar.  Tableau is now showing the count of records for each year in the dataset.  

</li>
<img src="../../images/dremio54.png" style="margin:15px 0px; border:1px solid black"/>
        
        
 <li>Let’s get a little more granular with the data by examining the data by month.  Hover over the blue YEAR(pickup_date) and click the dropdown arrow.  Tableau provides many different options for how to represent that data.  Click on the first <b>Month</b> option on the list    </li>
         <img src="../../images/dremio55.png" style="margin:15px 0px; border:1px solid black"/>
       Tableau is now showing the data that is grouped based on the month of the record.  This is interesting in showing Taxi usage each month but does not show any relational analysis like month over month.  To do this, Hover over the blue YEAR(pickup_date) and click the dropdown arrow.  Click the second month option that has the Month & Year listed and notice the difference.  

  </ol>
  <img src="../../images/dremio56.png" style="margin:15px 0px; border:1px solid black"/>
   <img src="../../images/dremio57.png" style="margin:15px 0px; border:1px solid black"/>

