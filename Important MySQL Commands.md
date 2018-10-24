<h1>Important MySQL Commands</h1>

<b>To login (from unix shell) use -h only if needed.</b>
<br/>
<code>[mysql dir]/bin/mysql -h hostname -u root -p</code>
<br/><br/>
<b>Create a database on the MySql server.</b><br/>
<code>mysql> create database [databasename];</code>
<br/><br/>
<b>List all databases on the MySql server.</b><br/>
<code>mysql> show databases;</code>
<br/><br/>
<b>Switch to a database.</b><br/>
<code>mysql> use [db name];</code>
<br/><br/>
<b>To see all the tables in the database.</b><br/>
<code>mysql> show tables;</code>
<br/><br/>
<b>To see table's field formats.</b><br/>
<code>mysql> desc/describe [table name];</code>
<br/><br/>
<b>To return columns and column information.</b><br/>
<code>mysql> show columns from [table name];</code>
<br/><br/>
<b>To delete a database.</b><br/>
<code>mysql> drop database [database name];</code>
<br/><br/>
<b>To delete a table.</b><br/>
<code>mysql> drop table [table name];</code>
<br/><br/>
<b>Load a CSV file into a table.</b><br/>
<code>mysql> LOAD DATA INFILE '/tmp/filename.csv' replace INTO TABLE [table name] FIELDS TERMINATED BY ',' LINES TERMINATED BY '\n' (field1,field2,field3);</code>
<br/><br/>
<b>Dump or export one database for backup.</b><br/>
<code>[mysql dir]/bin/mysqldump -u username -p --databases databasename >/tmp/databasename.sql</code>
<br/><br/>
<b>Dump a table from a database.</b><br/>
<code>[mysql dir]/bin/mysqldump -c -u username -p databasename tablename > /tmp/databasename.tablename.sql</code>
<br/><br/>
<b>Restore database/import (or database table) from backup.</b><br/>
<code>mysql dir]/bin/mysql -u username -p databasename < /tmp/databasename.sql</code>
<br/><br/>

