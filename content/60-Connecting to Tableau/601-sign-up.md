+++
title = "Setting up your Personal Access Token (PAT)"
chapter = true
weight = 601
+++

<div style="text-align: left">

   <ol>
       <li> From your Dremio Cloud Home Screen, click on “Account Setting” in the bottom left of your screen
 <img src="../../images/newdremio59.png" style="margin:15px 0px; border:1px solid black"/>
</li>
      <li> Click on the “Personal Access Tokens” and generate a new token by clicking “Generate Token”
      Enter the following information: <br/>
      
      Label: Tableau Online <br/>
      Lifetime: 90 days <br/>
      
      Click Generate <br/>
      
<img src="../../images/newdremio60.png" style="margin:15px 0px; border:1px solid black"/>

Dremio will create a personal access token for you to use when connecting to Tableau Online.  Copy and save the token.  Once you close this screen you will not be able to retrieve your token again. 
<br/>
<img src="../../images/newdremio61.png" style="margin:15px 0px; border:1px solid black"/>
</li>
 <li>
 Open a new tab in your browser and navigate to the following URL: https://sso.online.tableau.com/

 </li>      
 
 <li>
 From the Tableau Online Sign-up Screen, click “Sign-Up”.  <b>If you already have a Tableau account, feel free to use that account for this lab. </b>
 </li>
        
<li>After clicking sign-up, Tableau will ask if you would like to start a free trial.  Click the Orange <b>“Start Your Free Trial”</b> Button.    </li>
       <li>Enter your information to sign up for the Tableau free trial and press “Request Free Trial”
       </li>
       <img src="../../images/newdremio32.png" style="margin:15px 0px; border:1px solid black"/>
    <li>Follow the on-screen instructions to verify your email with Tableau.  </li>
    
  <li>After activating your Tableau Online instance from your email account, Tableau will direct you to your Tableau Online instance to create a username & password.  For site selection, choose <b>US-West Oregon</b> (Point is to select same region as selected for Dremio deployment in AWS).  Once you click activate, Tableau will automatically direct you to your Tableau Online instance. 
 <img src="../../images/newdremio62.png" style="margin:15px 0px; border:1px solid black"/>
</li>




 </ol>
</div>
