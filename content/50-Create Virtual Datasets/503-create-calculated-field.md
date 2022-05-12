+++
title = " Creating a Calculated Field"
chapter = true
weight = 503
+++

<div style="text-align: left">
 <ol>
       <li>Navigate back to the Data Tab for your NYC_Taxi dataset and look at the different fields in the dataset.  
</li>
     <li>The field titled <b> “trip_distance” </b> is a float field that shows the distance of each trip in miles.  What if someone who wanted to use this dataset wanted to know the trip distance in kilometers?  With Dremio, you can create a calculated field.  Click the downward arrow next to the <b>“trip_distance”</b> field and then click on <b>“Calculated Field”</b>

</li>
        <img src="../../images/newdremio25.png" style="margin:15px 0px; border:1px solid black"/>
       
        
         <li>From the <b> “Add Calculated Field” </b> page you can use SQL functions to create or replace fields in the Dremio Virtual Dataset.  To convert Miles to KM, you will multiply <b> “trip_distance”</b>  by 1.6.  
 </li>
 
       <li>Dremio provides the ability to either replace the existing field with the new calculated field or to create a new field.  Since we want to keep both miles and kilometers, we are going to uncheck the <b>“Drop Source Field”</b>  box and name the field <b> “trip_distance_km”</b> .  Once this is done, press <b> Apply</b> . 
        <img src="../../images/newdremio26.png" style="margin:15px 0px; border:1px solid black"/>
       </li>
       Once you select Apply, Dremio returns to the Data Tab.  Now you can see that there is a new field called <b>“trip_distance_km”</b> as well as the SQL command that Dremio has written. 
<li> Since we have made a modification to the Virtual Dataset, we are going to save this as a new VDS to our Space. Click the arrow to expand the “Save View” menu and click “Save View As”. Name your dataset “NYC_Taxi_KM”, choose your Space, and click “Save”.
 <img src="../../images/newdremio27.png" style="margin:15px 0px; border:1px solid black"/>
  </li>
<li>
Navigate back to the Dremio Home Screen and you will notice two Virtual Datasets in your Home Space: NYC_Taxi & NYC_Taxi_KM.  You will also notice that the tags you created for the NYC_Taxi dataset are visible.  This makes it easy to identify datasets.  
<img src="../../images/newdremio28.png" style="margin:15px 0px; border:1px solid black"/>
</li>
    </ol>
</div>
