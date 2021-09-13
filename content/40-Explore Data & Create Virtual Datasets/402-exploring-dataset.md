+++
title = "Exploring Dataset"
chapter = true
weight = 402
+++

<div style="text-align: left">
    Now that we have selected a dataset to explore, let’s take a look at the different aspects of the <b>Data Preview</b> screen
 <br/>
  
      <img src="../../images/dremio27.png" style="margin:15px 0px; border:1px solid black"/>
<ol> 
<b>5 regions in the image are described below:</b>
<li>
Shows the dataset that is being used</li>
<li>Dremio provides the ability to write specific SQL functions, add or remove columns and join datasets.  We will explore this in greater detail later in the workshop. 
</li><li>Is the preview window to the current dataset and the fields that the dataset contains.  Depending on the size of the dataset, this might only be a sample of the entire dataset that Dremio will query
</li><li>Shows the number of records in the preview and the query response time
<li>Dremio can connect to a variety of the most popular BI and Data Science tools.  Users can create a direct connection directly from the Dremio UI to Tableau and PowerBI

</li>
</ol>
<ul>
        <li> Next to SQL Editor, click the <b>arrow head</b> icon to expand the SQL Editor.  
</li>
      What do you see in the SQL Editor space? SELECT * FROM "Demo Taxi Reflection"

<li>  Explore the different fields in this dataset. You will notice that Dremio has applied a <b>Data Type</b> to each field.  Here are the different <b>Data Types</b>:
</li>
        <img src="../../images/dremio29.png" style="margin:15px 0px; border:1px solid black"/>
        <li>Using the SQL Editor, count the number of records that are in this table by entering SELECT COUNT(*) FROM "Demo Taxi Reflection". </li>
        How many records are in this table? <b>492,111</b>

<li>Return to the Dremio Home Screen by clicking the Dremio Logo in the top left corner of your screen.  It will ask you if you want to leave or save your changes, click <b>“Leave”</b>
            
</li>
</ul>
        
</div>
