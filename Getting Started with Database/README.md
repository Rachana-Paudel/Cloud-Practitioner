### Databases

####    Why databases?
A computer need to store the information, before that the information can be reference or changed . A computer also need to find the right information at the right time A database is logically organized collection of information designed in such a way the information with them can be accessed for later used by a computer program.
<img src="assets/database.PNG" alt="database" style="height:100%; width:100%">    

####    Data models and structure   
Data model is the logical structure of the database and determine the rules for how information can be organized an used. The data model you choose is influenced by the structure of your data. Data structure in three different ways:
1.      Structured data:
    It is stored as a series of data values in related tables. This data is highly structured. This means it is formatted so that it owner can be made accessible for most effective processing and analysis. The data is also able to be used for highly complex queries.

2.      Unstructured database  
    +   Stored as files
    +   Lacks predefined structured
    +   Special tools to catalog and query

3.      Semi structured data
    +   Highly flexible
    +   Changed as needed
    +   Analyzed    

<img src="assets/data model and structure.PNG" alt="data model" style="height:100%; width:100%">   

####    Database terms and concepts
1.      Schema
    A database schema is the blueprint of the database. The schema outlines the relationships within the database and the constraints of the database.
    There are two main types of schemas: schema-less and semi-structured or fixed schema.
    +   A schema-less database maanges information without the need for a blueprint.
    +   Semi-structured data doesnot follow the format of a tabular data model or relational databases because it does not have fixed schema.

2.      Read/Write
    Reading and writing to a database is just what it sounds like.
    +   When you complete actions that read from the database you are accessing the data for a particular purpose.
    +   When complete actions that write to the database you are putting new data into the database or changing data that is already existing.
    knowing if you workload will have more read operations or write operations will help you to design a database that is optimized for speed and efficiency.  

3.      Input/output operations per second
    IOPS is the measure of performance of reads and writes to a storage location like a database.
    Databases are IOPS intensive because they are continuously reading from the database and modifyinf the pages. Given this aspect of database, it is important to consider the impact of your performance when selecting IOPS.
    To improve latency and rea/write throughput, provision more IOPS when configuring the databse. Limiting the IOPS may cause the database to hit the threshold and reduce performance. Over provisioning of IOPS will result in higher costs for the instance.

4.      ACID and BASE compliance
<img src="assets/acid and base.PNG" alt="ACID" style="height:100%; width:100%"> 

<img src="assets/acid.PNG" alt="ACID" style="height:100%; width:100%"> 

<img src="assets/base.PNG" alt="BASE" style="height:100%; width:100%"> 

5.      OLTP/OLAP
<img src="assets/oltp and olap.PNG" alt="oltp" style="height:100%; width:100%">     

6.      Indexes
<img src="assets/indexes.PNG" alt="indexes" style="height:100%; width:100%">     

7.      SQL query language
<img src="assets/SQL.PNG" alt="indexes" style="height:100%; width:100%">     

####    Types of database
1.  Relational database
+   Structured data

2.  Nonrelational database
+   Unstructured and semi structured data

<img src="assets/types of database.PNG" alt="database" style="height:100%; width:100%">  

####    Relational database tables
<img src="assets/database example.PNG" alt="database" style="height:100%; width:100%">  

####    Relational databases benefits
+   Ease of use for structure data
+   Data integrity controls and accuracy
+   Common shared query language
+   Reducing redundancy and overall data storage.

<img src="assets/database benefits.PNG" alt="database" style="height:100%; width:100%"> 

####    Use case of Relational database
<img src="assets/use case of database.PNG" alt="database" style="height:100%; width:100%"> 

####    Nonrelational database
<img src="assets/non relational database.PNG" alt="database" style="height:100%; width:100%"> 


####    Non relational database benefits
+   flexibility
+   Scalability
+   High performance
+   Highly funcional APIs

####    Non relational database use case
<img src="assets/use case of non relational database.PNG" alt="database" style="height:100%; width:100%"> 

####    Why AWS database
+       purpose built
    AWS database service are purpose-built to support what your application is designed to do. Choose databqse service that best matches your workload.

+       performance at scale
    AWS offers databases hat are three to five times faster than popular alternatives, or non-relational databases that give you microsecond to sub-millisecond latency.

+       fully managed
    AWS manages database tasks such as server provisioning, patching, configuration, and backups so you can focus on developing your application.

+       secure and highly available
    AWS database are built for business-critical, enterprise workloads. They offer high availability, reliability, and security with multi-region and end-to-end encryption support.

####    Database deployments and management
+   On-premises database
<img src="assets/on-premises.PNG" alt="database" style="height:100%; width:100%"> 

+   Hosted on Amazon EC2
<img src="assets/hosted on amazon ec2.PNG" alt="database" style="height:100%; width:100%"> 

+   AWS managed    
<img src="assets/aws managed.PNG" alt="database" style="height:100%; width:100%"> 

####    AWS databases
<img src="assets/aws database.PNG" alt="database" style="height:100%; width:100%"> 

+   Relational
<img src="assets/relational.PNG" alt="database" style="height:100%; width:100%"> 

+   key-value
<img src="assets/key value.PNG" alt="database" style="height:100%; width:100%"> 

+   Document
<img src="assets/document.PNG" alt="database" style="height:100%; width:100%"> 

+   Timestream
<img src="assets/timestream.PNG" alt="database" style="height:100%; width:100%">

+   In-memory
<img src="assets/in-memory.PNG" alt="database" style="height:100%; width:100%">

+   Graph
<img src="assets/graph.PNG" alt="database" style="height:100%; width:100%">

+   Ledger
<img src="assets/graph.PNG" alt="database" style="height:100%; width:100%">


+   Key spaces
<img src="assets/keyspaces.PNG" alt="database" style="height:100%; width:100%">

####    Introduction to Amazon Relational Database Service(Amazon RDS)
+   Cost-efficient
+   Automating administration tasks
+   Resizable capacity

####    Amazon RDS engines
<img src="assets/RDS engine.PNG" alt="RDS" style="height:100%; width:100%">

####    Amazon RDS
    It is fully managed relational database service that supports the major relational database engines.

<b>Why move to a fully managed services?</b>

1.  Pass on the burden of repetitive tasks.
such as:

+   Backups and restores
+   Softwate installations and patching
+   Managing hardware

2.  Pass on the responsibility and engineering efforts.
+   scaling servers
+   highly available environments
+   maintenance free migration

####    Amazon RDS benefits
+   Easy to administer
+   Available and durable
+   Highly scalable
+   Fast
+   Secure
+   Inexpensive

####    High availability: Multi-AZ deployments
<img src="assets/multi-az.PNG" alt="az" style="height:100%; width:100%">

####    High availability: Multi-AZ deployments benefits
+       Enhanced durability
    +   Multi-AZ deployments for the MySQL, MariaDB, Oracle, and PostgreSQL engines utilizr sunchronous physical replication to keep data on the standby up to date with the primary.
    +   Multi-AZ deployments for the SQL Server engine use synchronous logical replication o achieve the same result, employing SQL Server-native mirroring technology.
    +   If the storage volume on the primary instance falls, Amazon RDS automatically initiates a failover to the standby.
+       Increased availability
    +   If there is an Availability Zone or primary database failure, your availability impact is limited to the time automatic failover takes to complete-typically under two minutes.
    +   This availability benefit extends to planned maintenance and backups as well.
    +   Upgrades and patches are installed on the standby instance first.
    +   Once completed, a failover is initiated, and the updates or patches are installed on the remaining instance.

+       No administrative intervention
    +   DB instance failover is fully automatic and requires no administrative intervention.
    +   Amazon RDS moniotors the health of your primary and standbys and initiates a failover automatically in response to a variety of failover conditions.