+++
title = "Joining the Taxi & Weather Dataset"
chapter = true
weight = 802
+++

<div style="text-align: left">
    <ol>

<li>Click on your NYC_Taxi Virtual Dataset and select the “Graph” tab at the top of the preview window. .   
 <img src="../../images/newdremio52.png" style="margin:15px 0px; border:1px solid black"/>
 Dremio provides the ability to track the lineage of virtual datasets by showing which source the dataset came from, which Physical Dataset was the parent to the virtual dataset and if there are any children virtual dataset.  Because we created a VDS that had a kilometer calculated field we can see that we have one child dataset in the graph. 
<img src="../../images/newdremio53.png" style="margin:15px 0px; border:1px solid black"/>
</li>
<br/>
  

<li>Navigate back to the data tab and click “Join” located under the SQL Runner.   
<img src="../../images/newdremio54.png" style="margin:15px 0px; border:1px solid black"/>
Dremio allows you to join datasets using Inner, Left Outer, Right Outer or Full Outer joins.  Dremio also provides the ability to recommend datasets to join based on past history.  Since this is the first time we are joining a dataset, there are no recommendations.  You will create a join by browsing for a Virtual Dataset.  

</li>
                        


<li> Click Browse and locate your newly created nyc_weather Virtual Dataset.  Once you have found the correct dataset, click Next.

                           <img src="../../images/newdremio55.png" style="margin:15px 0px; border:1px solid black"/>

<li>
We are going to do an Inner join based on date.  Drag Pickup_Datetime from the NYC_Taxi dataset on the left.  Next, drag DATE from the nyc_weather dataset on the right.  Once you have both fields in the join, click Apply
  <img src="../../images/newdremio56.png" style="margin:15px 0px; border:1px solid black"/>
</li>
<li>
Once you click Apply, Dremio will join the two data sets and return a preview of the newly joined dataset.  Scroll through the fields and notice how now you have taxi and weather information.  

</li>

<li>Save the new dataset. Click the arrow next to “Save View”, select “Save View As” in the top right and save as “nyc_taxi_weather” in your Space. 
  <img src="../../images/newdremio57.png" style="margin:15px 0px; border:1px solid black"/>
</li>
   
  </ol>
</div>
