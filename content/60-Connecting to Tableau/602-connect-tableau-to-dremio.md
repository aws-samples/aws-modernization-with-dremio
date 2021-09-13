+++
title = "Connecting Tableau Online to Dremio"
chapter = true
weight = 602
+++

<div style="text-align: left">
    <ol>
<li>From the Tableau Home Screen click <b>“Explore” </b> found on the left side of the screen
</li>
       <img src="../../images/dremio43.png" style="margin:15px 0px; border:1px solid black"/>
<li> From the “New” Drop down click “Workbook”
        <img src="../../images/dremio44.png" style="margin:15px 0px; border:1px solid black"/>

</li><li>In your new workbook, you will immediately see a <b>“Connect to Data” </b> pop-up.  From here you can connect to data already uploaded onto Tableau Online, files and data sources.  For this lab, we are going to establish a connection to Dremio by clicking on <b>“Connectors” </b>
        <img src="../../images/dremio45.png" style="margin:15px 0px; border:1px solid black"/>
<li>From the connectors tab, select Dremio.  Another pop-up will appear asking for the Dremio server information to establish a connection.  Enter the following information:
</li>
        <img src="../../images/dremio46.png" style="margin:15px 0px; border:1px solid black"/>
<br/>
<b>Server:</b> IP Address of your Dremio instance. This will be part of <b>Output</b> tab when you ran Cloudformation from Marketplace as part of "DremioPublicEndpoint" string. You will have to parse the IP address from the string. When you navigate to the Dremio UI, you will see this in the URL Bar.  *NOTE* Only input the IP address do not include HTTP or the Port.  
<br/>
<b>Port:</b> Leave the default port of 31010
<br/>
<b>Username:</b>  The Dremio username that you created earlier in the lab.  If you do not know your username, you can find it in the top right corner of your Dremio instance
<br/>
<b>Password:</b>  The Dremio password that you created earlier in the lab
<br/>
<b>SSL:</b> Leave unchecked
<br/>
Once you have entered the correct information, press <b>“Sign-In”</b>
        <img src="../../images/dremio47.png" style="margin:15px 0px; border:1px solid black"/>
   
     

        
 </ol>
</div>
