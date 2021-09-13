+++
title = "Editing a Virtual Dataset"
chapter = true
weight = 504
+++

<div style="text-align: left">
</div>
    <ol>
       <li> From the Dremio home screen hover over the <b>NYC_Taxi</b> Dataset and click on the edit button.  This will allow you to edit an already existing VDS.

</li>
<li> Notice the fields pickup_datetime & dropoff_datetime include both the date and time as one value. For the purposes of this lab, we just need to keep the date.  
      
</li>
 <li> Dremio provides different ways to separate and remove values from a specific field.  For the purposes of this lab, we are going to convert the data type from a Date & Time field to a Date field.  Click the dropdown arrow next to the pickup_datetime field and select <b>“Convert Data Type”</b>.  </li>
       <li>Under Select Type, select Date and press Apply.  Notice that Dremio replaced the old field with the new field.  
</li>
        <img src="../../images/dremio37.png" style="margin:15px 0px; border:1px solid black"/>
<li>Apply the same process to the dropoff_datetime field and press apply.  After you are done your dataset should look like the screenshot below.  Notice both pickup_datetime & dropoff_datetime now only include the date. </li>
           <img src="../../images/dremio38.png" style="margin:15px 0px; border:1px solid black"/>
    <li>Now that we have removed time, we need to rename the field.  Click the dropdown arrow next to the pickup_datetime field and select Rename.  Rename the field pickup_date.</li>
   <li>Apply the same process for the dropoff_datetime field.
</li>
<li>Save your edited dataset by clicking on the  icon and selecting Save
</li>
    </ol>

