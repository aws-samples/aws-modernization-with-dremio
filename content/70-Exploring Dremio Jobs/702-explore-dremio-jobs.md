+++
title = "Exploring Dremio Jobs "
chapter = true
weight = 702
+++

<div style="text-align: left">
   <ol>
<li>
In Dremio, click on the Jobs icon at the top of your screen.  Dremio will ask you if you want to save any changes, click <b>“Leave”</b> . 

</li>

<img src="../../images/dremio52.png" style="margin:15px 0px; border:1px solid black"/>

<br/>
The Dremio Jobs page shows the jobs that Dremio has completed or are currently being run.  The left provides a list of jobs and the right shows detailed information about the selected job.  
<br/><br/>
If you look at your jobs in Dremio you will see the jobs that have been passed down from Tableau as well as the jobs that you have run in Dremio.  In the list of jobs on the left you see that each job shows the Dataset, User, Start Time, Duration and End Time.  Notice that the duration of your jobs both in Tableau and Dremio are <1 second.  When you created a count of records in Tableau, a query was passed down to Dremio and Dremio performed that query on S3 and passed back the results.  All in less than a second!
<br/><br/>
You will notice that next to some Duration values, you will see a flame.  The flame identifies that the query performed was accelerated by a Dremio reflection.  
<br/><br/>
As you continue to create visualizations in Tableau, reference back to the Jobs Page to see how fast Dremio is returning the response.  

 </ol>
</div>
