Download Link: https://assignmentchef.com/product/solved-cmis-320-project-3
<br>
In this assignment you will perform the <strong>physical</strong> design and implementation using SQL Data Definition Language (DDL) and proceed with <strong>populating</strong> the Mom and Pop Johnson Video Store database via Data Manipulation Language (DML) SQL commands.

For each of the steps below you may create a separate SQL script file and SPOOL file or you may want to put the SPOOL output for several steps, from the same SQL script file, in the same file.  Be sure your SPOOL file(s) contains your SQL statements along with the Oracle responses and/or displayed results.  Do NOT submit your SQL script files.  Only submit your output SPOOL files.

<strong>Assignment Details:</strong>

<ul>

 <li><strong>Create Oracle database tables</strong> using SQL Data Definition Language (DDL) for each table listed in the metadata of Project 2. You may need to use a combination of DROP TABLE, CREATE TABLE, and ALTER TABLE SQL statements.  Make sure that entity and referential integrity are enforced by declaring a <strong>primary</strong> key for <strong>each</strong> table (these may be composite keys) and declaring <strong>all</strong> appropriate <strong>foreign</strong> Your CREATE TABLE and ALTER TABLE statements (if desired) must show integrity constraints, as appropriate, for NOT NULL, UNIQUE, PRIMARY KEY, FOREIGN KEY, REFERENCES, and CHECK constraints. Be sure to save your SQL script file used to create these tables with a .sql extension and your output SPOOL file with a .lst or .txt extension.  You should rerun and test your SQL script file until it runs without any errors (this is why you’ll want to include DROP TABLE statements).  Submit your SPOOL file showing that all SQL in your SQL script file worked properly.</li>

 <li>Populate each of your tables with at least five <strong>valid</strong> rows of data each and show the SQL INSERT statements as you executed them. Populate other tables in your database, as necessary, to satisfy referential integrity. Save your SQL script file and SPOOL file with the correct extensions. You should test and rerun your SQL script file until it runs without any errors.</li>

</ul>

Submit your SPOOL file showing that all SQL in your SQL script file worked properly.

<ul>

 <li>Develop an SQL script file to perform the following queries and updates. You should test your SQL script file until it runs without any errors.

  <ul>

   <li>Retrieve all of your customers’ names, account numbers, and addresses (street and zip code only), sorted by account number.</li>

   <li>Retrieve all of the videos rented in the last 30 days and sort in chronological rental date order. o Produce a list of your distributors and all their information sorted in order by company name.</li>

   <li>Update a customer name to change their maiden name to a married name. You can choose which row to update. Make sure that you use the primary key column in your WHERE clause to affect only a specific row.  You may want to include a ROLLBACK statement to undo your data update.</li>

   <li>Delete a customer from the database. You can choose which row to delete. Make sure that you use the primary key column in your WHERE clause to affect only a specific row. You may want to include a ROLLBACK statement to undo your data deletion.</li>

  </ul></li>

</ul>

Submit your SPOOL file(s) showing that all SQL in your SQL script file worked properly.  Show the actual SQL statements executed and the results the SQL produced below the code by making sure that you have a SET ECHO STATEMENT in your SQL script file(s).

<strong>Do NOT submit your .sql SQL script files. </strong>




<strong>Grading rubric </strong>

<table width="636">

 <tbody>

  <tr>

   <td width="155"><strong>Attribute </strong></td>

   <td width="198"><strong>Meets </strong></td>

   <td width="282"><strong>Does Not Meet Expectations </strong></td>

  </tr>

  <tr>

   <td width="155">CREATE TABLE and ALTER TABLE SQL statements </td>

   <td width="198"><strong>30 points </strong>All SQL statements are syntactically correct and execute without errors; all integrity constraints are properly declared;</td>

   <td width="282"><strong>0 points </strong>Many SQL statements fail due to syntax errors or SQL is missing</td>

  </tr>

  <tr>

   <td width="155">INSERT SQL statements </td>

   <td width="198"><strong>25 points </strong>All SQL statements are syntactically correct and execute without errors.</td>

   <td width="282"><strong>0 points </strong>Many SQL statements fail due to syntax errors and/or integrity constraint violations or SQL is missing</td>

  </tr>

  <tr>

   <td width="155">SELECT SQL statements</td>

   <td width="198"><strong>20 points </strong>All SQL statements are syntactically correct and execute without errors.</td>

   <td width="282"><strong>0 points </strong>Many SQL statements fail due to syntax errors or SQL is missing</td>

  </tr>

  <tr>

   <td width="155">UPDATE and DELETE SQL statements</td>

   <td width="198"><strong>10 points </strong>Statements execute without errors based on primary key column in WHERE clause</td>

   <td width="282"><strong>0 points </strong>Statements fail due to syntax or other errors</td>

  </tr>

  <tr>

   <td width="155">SQL script file and SPOOL file</td>

   <td width="198"><strong>15 points </strong>Demonstrates full ability to create and use an Oracle SQLscript file and output SPOOL file</td>

   <td width="282"><strong>0 points </strong>Many errors setting up and using an SQL script file with SPOOL file or no attempt made at all</td>

  </tr>

 </tbody>

</table>




<strong> </strong>