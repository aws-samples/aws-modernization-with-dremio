+++
title = "Setting Minimum Engine Replicas"
chapter = true
weight = 205
+++

<div style="text-align: justify">
    <center><h2>Setting Minimum Engine Replicas</h2></center>
  

    <ol>
        <li>From your Dremio homescreen navigate to the Dremio Project Settings at the lower left corner
        <img src="../../images/newdremio63.png" style="margin:15px 0px; border:1px solid black"/>

 </li>
 

         <li>   From the Project Settings tab, click the Engines tab on the left navigation pane

        </li>
        In addition to Amazon S3, Dremio Cloud connects to a variety of external sources.

    <li>
     Click on first engine and then click on “edit engine” in the top right corner
     <img src="../../images/newdremio64.png" style="margin:15px 0px; border:1px solid black"/>
    </li>
<li>
      Change Min Replicas from 0 to 1 and click save.  Dremio will automatically ensure that one replica of the engine will always be running.
<img src="../../images/newdremio65.png" style="margin:15px 0px; border:1px solid black"/>
Once you have saved, you can return to the Dremio home screen by clicking on the Narwal at the top left
    </li>
     </ol>
</div>
