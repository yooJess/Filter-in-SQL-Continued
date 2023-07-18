<h1>IN PROG: Filtering an SQL Query (Continued)</h1>

<h2>Description</h2>
In this project, we will be filtering an SQL Query, moreso we'll be utilizing and applying filters to find certain criteria to investigate a security incident.<br/> 

<br/>

<h2>Project</h2>

<p align="left">
  <b>1. </b>Retrieve login attempts after a certain date - Let's look for login attempts made after '2022-05-09'.<br/>
  <br/>
<img src="https://i.imgur.com/NMZwcYB.png" height="80%" width="80%" alt="Filter by Login Date"/>
<br/>
<br/>
<b>2. </b>Based on this first query, we still need to find and expand the date range to <b>include</b> 2022-05-09 in our search.<br/>
  <br/>
    <img src="https://i.imgur.com/wNnKgXp.png" height="80%" width="80%" alt="Filter by Greater than or Equal to Filter"/>
<br/>
  <b>Note: </b>The <b>WHERE</b> clause allows you to filter the results returned by a query by returning only the records that satisfy the condition.<br/>
<br/>
<br/><!--
<b>3. </b>Let's filter the rows returned from department column in the employees table to include only employees from the 'Finance' department.<br/>
  <br/>
    <img src="https://i.imgur.com/kPq9hxW.png" height="80%" width="80%" alt="Finance Department"/><br/>
  <br/> 
  <br/>
<b>4. </b>Prompt: We just got a message that a machine in 'South-109' has an issue. You need to determine which employee uses that computer so you can send them an alert. We got to write a query to identify which employee uses the office in 'South-109'.<br/>
 <br/>
    <img src="https://i.imgur.com/vJ0DlUB.png" height="80%" width="80%" alt="South 109"/><br/>
<br/>
<br/>
<b>5. </b>Prompt: Our team has determined that there is an issue with <i>all</i> the machines in the South building. Offices in the organization are named with the building name, a hyphen, and the office number in that building.<br/>
  <br/>
    Modify the query you used in the previous step so that it returns information on all the employees in the 'South' building. Use the LIKE operator with % in this query.<br/>
 <br/>
    <img src="https://i.imgur.com/AqPhhcF.png" height="80%" width="80%" alt="All South 109"/><br/>
<br/>
<br/> 
  Note:<br/>The LIKE keyword in SQL performs simple string matches. The matching pattern may include the wildcard <i>%</i> to represent a string of any length. This wildcard may be placed both before and after the targeted substring.
  <br/>
  <br/>
  <br> This is my project on applying the 'WHERE' clause, to filter an SQL return and also utilize the 'LIKE' operator to filter and look for patterns!
  <!--
<b>6. </b>Let's organize this chart by 'login_date' so we can read it easier.<br/>
<br/>
    <img src="https://i.imgur.com/ZkH4vrg.png" height="80%" width="80%" alt="Organize by Login Dates"/><br/>
<br/>
<br/>
  <b>7. </b>Let's organize it again, by changing the 'Order by' login_date, and also login_time:<br/>
  <br/>
    <img src="https://i.imgur.com/soVfHzz.png" height="80%" width="80%" alt="Organize by login date and login time"/><br/>
<br/>
<br/>
<br/>
That's about it! We got a quick run down of how to Perform some SQL Queries with some simple 'Select' and 'From' and then also entering some table names! Thank you!
<br/>
<br/>
<br/>
-->


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
