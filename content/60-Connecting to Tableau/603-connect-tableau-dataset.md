+++
title = "Connecting to your Dataset"
chapter = true
weight = 603
+++

<div style="text-align: left">
 Now that you have quickly connected Dremio to Tableau you can start to explore different tables without having to copy any of the data into Tableau.  After a successful connection has been made Tableau will direct you to the <b>“Data Source”</b> tab in your new workbook.
    <ol>
       <li> From the Data Connections tab in your Tableau workbook, select the following from the dropdown menus
</li>
<ul>
     <li>  Under  “Database”, select “DREMIO”</li>
       
       <li>Under “Schema”, enter the name of your Dremio Homespace (where you saved your VDS)</li>
     

<li>Under Table, enter the name of the VDS (NYC_Taxi) that you saved in Dremio</li>
</ul>
<br/>

        <li>  Drag the NYC_Taxi table from the left side under “Connections” to the center of the workbook where it says “Drag Tables Here”
  <img src="../../images/newdremio40.png" style="margin:15px 0px; border:1px solid black"/>
        </li>
        Now that you have connected Dremio to Tableau and selected the Table to analyze, you can now start creating visualizations.  Click on “Sheet 1” in the bottom left corner of your Tableau Workbook.  Your screen should look like this:
       <img src="../../images/dremio50.png" style="margin:15px 0px; border:1px solid black"/>
        
         
 </ol>
</div>
