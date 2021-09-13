+++
title = "Joining the Taxi & Weather Dataset"
chapter = true
weight = 802
+++

<div style="text-align: left">
    <ol>

<li>Navigate back to the data tab and click <b>“join”</b> located under the SQL Editor.   
</li>
<br/>
Dremio allows you to join datasets using Inner, Left Outer, Right Outer or Full Outer joins.  Dremio also provides the ability to recommend datasets to join based on past history.  Since this is the first time we are joining a dataset, there are no recommendations.  You will create a join by browsing for a Virtual Dataset.  

<li>Click search and search for your newly created <b>nyc_weather</b> Virtual Dataset.  Once you have found the correct dataset, click <b>Next.</b> 

</li>
                            <img src="../../images/dremio66.png" style="margin:15px 0px; border:1px solid black"/>


<li>We are going to do an Inner join based on date.  Drag Pickup_Date from the NYC_Taxi dataset on the left.  Next, drag DATE from the nyc_weather dataset on the right.  Once you have both fields in the join, click <b>Apply</b>
                            <img src="../../images/dremio67.png" style="margin:15px 0px; border:1px solid black"/>

<li>
Once you click Apply, Dremio will join the two data sets and return a preview of the newly joined dataset.  Scroll through the fields and notice how now you have taxi and weather information.  

</li>

<li>Save the new dataset by clicking the icon and save as <b>“nyc_taxi_weather”</b> in your Home Space.. 
</li>
   
  </ol>
</div>
