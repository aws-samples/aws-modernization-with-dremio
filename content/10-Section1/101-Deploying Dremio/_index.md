+++
title = "How It Works"
chapter = true
weight = 101
autoNav = true
+++

<center><h3>How it works</h3></center>

<div style="text-align: justify">
Before we go ahead and work on deploying Dremio, let us understand what is Dremio and how it works. Dremio is a SQL Lakehouse Platform that delivers fast interactive queries directly on S3 using an Apache Arrow-based engine and end-to-end query acceleration techniques such as columnar caching, transparent materialized views, and vectorized execution. 
 </div>
 </br>
 <div style="text-align: justify">
Data science applications and BI tools can connect to Dremio using Arrow Flight, ODBC, JDBC and REST interfaces. For data science applications in particular, Arrow Flight provides up to a 1000x increase in throughput over ODBC/JDBC using parallel high-speed transfers.
 </div>
 </br>
 <div style="text-align: justify">
  In addition, Dremio offers a semantic layer making it easy to transform and aggregate data from one or more sources into virtual datasets without the need for complex pipelines. The platform provides a combination of role-based access controls, row- and column-level permissions, and data masking to ensure secure and governed access to these datasets.
   </div>
   </br>
  <div style="text-align: justify">
  Data stays in the customer’s AWS account and is stored in open formats, providing the flexibility to use multiple analytic services without vendor lock-in. 
</div>
<img src="../../images/dremio1.png" style="margin:15px 0px; border:1px solid black"/></li>
<div>
  </ul>In this section, we’ll cover the following topics:
    {{% children showhidden="false" %}}
</div>
