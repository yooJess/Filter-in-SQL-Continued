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
<b>2. </b>Notice, that on this first query <b>'>'</b> only gives us the date after, we still need to find and expand the date range to <b>include</b> 2022-05-09 in our search.<br/>
  <br/>
    <img src="https://i.imgur.com/wNnKgXp.png" height="80%" width="80%" alt="Filter by Greater than or Equal to Filter"/>
<br/>
<br/>
<b>3. </b>With the <b>>=</b> greater-than-or-equal, we get the date range specified to include the dates of 2022-05-09. Now let's focus the search.<br/>
  <br/>
    <img src="https://i.imgur.com/SHGzQ0v.png" height="80%" width="80%" alt="Filter by BETWEEN and AND"/><br/>
  <br/>
    Note:<br/>Notice the format of the argument is different, you can type out the entirity of the argument in one-line, as long as you close it out with a ';'!
  <br/>
  <br/>
<b>4. </b>Now let's investigate logins that were made at certain times. Let's write a query that returns us a login period between '06:00:00' and '07:00:00'.<br/>
 <br/>
    <img src="https://i.imgur.com/TNsFkQ6.png" height="80%" width="80%" alt="Filtering BETWEEN and AND"/><br/>
<br/>
<br/>
<b>5. </b>We can also look at event logs, let's check for how many logins were made, by their 'event_id'.<br/>
  <br/>
 <br/>
    <img src="https://i.imgur.com/yICKqWJ.png" height="80%" width="80%" alt="Event ID"/><br/>
<br/>
<br/> 
<b>6. </b>Now let's look at the 'event_id' between 100 through 150.<br/>
<br/>
    <img src="https://i.imgur.com/OioKejX.png" height="80%" width="80%" alt="Event ID 100-150"/><br/>
<br/>
<br/>
  <br>This is continuation project on applying more filters in SQL utilizing BETWEEN and AND, and also the greater/less than symbols!
  <br/>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
