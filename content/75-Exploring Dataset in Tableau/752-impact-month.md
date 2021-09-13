+++
title = "How Does Month Impact Surcharge"
chapter = true
weight = 752
+++

<div style="text-align: left">
   <ol>
<li>
Clear your Tableau sheet by pressing the  button on the Tableau toolbar and selecting <b>“Clear Sheet” </b>.  
</li>
<li>Now you are going to examine how each month of the year impacts the surcharge of a taxi ride.  To do this first you are going to drag <b>“Pickup_Date”</b> to the columns bar and select <b>Month</b> from the drop down.  
</li>
<br/>
**Remember we are looking for the sum for each month not a month over month comparison**


<li>Now drag the surcharge measure to the rows bar.  Tableau automatically selects the Sum of the records.  For this lab, we want to see the total amount of Surcharge dollars spent so we will keep it at sum.  
</li>
<br/>
Now that you have a measure and dimension you should see a chart that shows the sum of surcharge by each month.  
                      <img src="../../images/dremio58.png" style="margin:15px 0px; border:1px solid black"/>

<li>Tableau automatically choose the line chart for this visualization but we want to see this as a bar chart. Under the Marks box, click the dropdown menu next to <b>Automatic</b> and select <b>“Bar”</b></li>
                      <img src="../../images/dremio59.png" style="margin:15px 0px; border:1px solid black"/>
Your visualization should look like this:
                      <img src="../../images/dremio60.png" style="margin:15px 0px; border:1px solid black"/>
Which month is the highest for Surcharges?  March


        
</ol>
</div>
