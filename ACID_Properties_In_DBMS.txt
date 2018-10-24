<h1>ACID Properties in DBMS</h1>

A transaction is a very small unit of a program and it may contain several low level tasks.
A transaction in a database system must maintain <b>Atomicity, Consistency, Isolation, and Durability</b> − commonly known as ACID properties − in order to ensure accuracy, completeness, and data integrity.

<b>Atomicity</b>- This property states that a transaction must be treated as an atomic unit, that is, either all of its operations are executed or none.
There must be no state in a database where a transaction is left partially completed.
<br/><br/>
<b>Consistency</b> - Database must remain in a consistent state after any transaction.
If the database was in a consistent state before the execution of a transaction, it must remain consistent after the execution of the transaction as well.
<br/><br/>
<b>Isolation</b> −In a database system where more than one transaction are being executed simultaneously and in parallel, the property of isolation states that all the transactions will be carried out and executed as if it is the only transaction in the system. No transaction will affect the existence of any other transaction.
<br/><br/>
<b>Durability</b> - After a transaction successfully completes, changes to data persist and are not undone, even in the event of a system failure.
The database should be durable enough to hold all its latest updates even if the system fails or restarts.
