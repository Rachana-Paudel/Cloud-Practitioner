##  Introduction to Cloud 101

### Module 1
#####   Why learn about the cloud

+   Demand for cloud skills is increasing
+   Cloud computing skills are relevant for all IT professionals
+   Cloud certification validates knowledge and skills

### Module2
#####   Objectives
+   Define cloud computing
+   Describe the basics of cloud computing
+   Discuss the benefits of cloud computing
+   Identify cloud service models and cloud deployment models

#####   Why cloud computing?
+   It assests as programmatic resources to quickly set up and tear doen resources
+  Access resources dynamically for agility and flexibility to meet customer needs
+   Pay-as-you-go to test and use the system without being fully commited 

#####   Who uses AWS?
<img src="who_use.PNG" alt="AWS" style="height::100%; width: =100%;">

#####   History
<img src="history.PNG" alt="history" style="height::100%; width: =100%;">

#####   Client Server model
Model computing is based on the client-server model
+   A client can be web browser or desktop application that a person interacts with to make requests to computer servers.
+   A server can be services such as Amazon Elastic Compute Cloud(Amazon EC2), a type of virtual server.

##### Six benefis of cloud computing

1. Trade upfront expense for variable expense
2. Stop spending money to run and maintain data centers
3. Stop guessing capacity
4. Benefit from massice economies of scale
5. Increase speed and agility
6. Go global in minutes
<img src="benefit.PNG" alt="benefits" style="height::100%; width: =100%;">

#####   Deploying to the cloud
Cloud service and deployment methods provide different levels of control, flexibility and management.

Deployment method include
+   `Infrastructure as a service (IaaS)`: IaaS contains the basic building blocks for cloud IT. It typically provides access to networking features, computers(Virtual or on dedicated hardware), and data storage space. Infrastructure as a servive provides the highest levl of flexibility and management cinrol over your IT resources.
+   `Platform as a service (Paas)`: Itremoves the need for organizations to manage the underlying infrastructure. They can focus on the deployment and management of applications. These tools give developers the ability to be more efficient because they dont need to worry about resource procurement, capacity planing, software maintenance, and patching

+   `Software as a service(Saas)`: It is a completed software product that the service provider runs and manages. With a SaaS offering, you donot have to think about how the service is maintained or how the underlying infrastructure is managed. Yu only must think about how you wil use that particular piece of software.

Deplyoment(models) strategies include
+   <u>Cloud</u>: you can migrate existing applications to the cloud, or you can design and build new application in the cloud. You can build hose application on low-level infrastructure that requires your IT staff to manage them. Alternatively, you can build them by using higher-level services tha reduce the management, architecting, and scaling requirements of the core infrastructure.

+   <u>Hybrid</u>: In this, cloud-based resources are conneced to on-premises infrastructure. You can integrate cloud-based resources wih legacy IT application. You migh want to use this approach in a number of situations. For example, you have legacy appliacations that are better maintained on premises, or goverment regulations require your bussiness o keep certain records on premises.
+  <u> On-premises</u>: It is also known as private cloud deployment. In this model, resources are deployed on premises by using virualization and resource management tools, Increase resource utilization by using application management and virtualizatuon technologies.

#### End of module2

### Module3
<u>Objectives</u>
1.  Discuss the history of AWS cloud computing
2.  Describe the AWS global infrastructure
3.  Discuss the customer and AWS parts of the shared responsibility model
4.  Describe the Well-Architected Framework and discuss how to apply the pillars
5.  Define the total cost of ownership and billing considerations

####    AWS offerings

<img src="aws_offering.PNG" alt="aws_offering" style="height::100%; width: =100%;">

#### AWS benefits
+   On-demand access to over 175 services cloud-based services
+   pay-as-you-go pricing
+   No upfront capital expenses or commitements
    +   The ability to try a lo of experiments
    +   Not having to live with the collateral damage of failed experiments.
+   Tool box of high-end services

####    Brief history of AWS
<img src="awshistory.PNG" alt="aws_history" style="height::100%; width: =100%;">


####    AWS is the leader of cloud computing
<img src="leader_aws.PNG" alt="leader_aws" style="height::100%; width: =100%;">

####    AWS Global Infrastructure

`components`: Regions, Availability zones and Edge Location

####    Planning for failure
+   Storage : When a file is stored in Amazon S3, the file is reduntantly copied into every Availability Zone in that Region. If one Availability Zone goes down, you still have two copies of that available for you to use.

+   Compute : It is a best practice to spread out your computing resources across multiple Availability Zones to guarentee high availability. So if one Avaialability Zones goes down, your architecture is still up and running.
+   Databases : You can configure your database for Multi-AZ deplyoment. If your Availability Zone wih your primary database fails, one of he standby databases in a healthy Availability Zpne automatically becomes your new primary database. Therefore, your architecture is still functioning.

####    AWS Global Infrastructure benefits

1. `Performance` :  AWS Global Infrastructure Offers high-performing, low-latency cloud infrastructure with virtually unlimited capacity, which provides high availability.
2.  `Availability` : Availability zones are designed for physical redundancy and to provide resilience. They provide uninterrupted performance, even in the event of power outages, internet downtime, floods, and other natural disasters.
3.  `Security` : The infrastructure is monitored 24/7 to help ensure the confidentiality, integrity, and available of AWS customers data. Customers can build on the most secure global infrastructure and know that they always own theit data. They can encrypt their data, move it, ad manage retention.
4.  `Relability` : AWS gloabl infrastructure is designed and built for redundancy and reliability, from regions to networking links to load balancers to routers to filmware.
5.  `Scalability` : With the AWS Global Infrastructure, companies can be flexible and take adavantage of the conceptually infinite scalabililty of the cloud. Companies can quickly get resources as they need them, deployinf hundreds or even thousands of servers in minutes.
6. ` Low Cost `: It provides the industry's most extensice data center footprint. As a result, more customers can benefits from cloud economics and reduce the Total Cost of Ownership (TCP) of their overall IT infrastructure.

####    Shared Responsibility
- protect cloud environment
<img src="shared_responsibility.PNG" alt="shared_responsibility" style="height::100%; width: =100%;">

####    AWS Well-Architeced tool

<img src="aws_architect.PNG" alt="aws_architect" style="height::100%; width: =100%;">

The Total Cost of Ownership(TCO) is a financial metric that is used to estimate and compare direct and indirect costs of a product or service. It typically includes the actual costs of:
+   Procurement
+   Management
+   Maintenance
+   Decommissioning of hardware resources

####    Total Cost of Ownership
<img src="owner_cost.PNG" alt="cost" style="height::100%; width: =100%;">

<img src="owner_calc.PNG" alt="calc" style="height::100%; width: =100%;">

<img src="owner_calc2.PNG" alt="calc" style="height::100%; width: =100%;">

####    AWS pricing model
+   Pay-as-you-go 
+   Save when you reserve
+   Pay less by using more

####    AWS Free Tier
Save money as you learn and experiment with AWS Free Tier

+   Always free : donot expire and are available to all AWS customers.
+   12 months free : access to some service for only 12 months.
+   Trials : start from date we activate a particular service and last specific time.

####    AWS Billing Dashboard

<img src="aws_billing.PNG" alt="aws_billing" style="height::100%; width: =100%;">

<img src="aws_billing2.PNG" alt="aws_billing" style="height::100%; width: =100%;">

`Billing example` : 

Amazon EC2 :

 <img src="EC2billing.PNG" alt="S3billing" style="height::100%; width: =100%;">

Amazon S3 :

  <img src="S3billing.PNG" alt="S3billing" style="height::100%; width: =100%;">


AWSLambda :

 <img src="lambdabilling.PNG" alt="lambdabilling" style="height:=100%; width: =100%;">

` End of module3`

### Module4
#####   AWS Core Services

Lets discuss the objective of module4
+   Define the different types of services
+   Identify the main categories of services as par of an architecture
+   Describe each service, its use, features, and benefits.

#####   Monilithic architecture

Application:
+   Transmit data
+   Fulfill request
+   Application code

Components:
+   Server
+   Databases
+   User interface
+   Bussiness logic

In this architecture if a single component is failed, it failed then other application also fails. It is also possible the whole component to be failed.

#####   To maintain application availability if single component fails, we can use Microservices archiecture

In this, component are lossely couple. If single component fails other doesnot stop functioning.

#####   Types of services
1. <i>Managed services</i>: A managed services is a way to describe the services that require you to manage infrastructure managemen tasks like patching, backup, and repair. These services gran you virtual access to the underlying operating sysem and services. With the managed services, you are responsible for scaling and building for high availability.

2. <i>Fully managed services</i> : It is a way to describe the services that automate infrastructure management tasks that AWS handles,like patching, backup, and repair. These services dono grant you any virtual access to he underlying operating system or servers. With a fully managed service, you are still responsible for scaling and building for high availability.

3.  <i>Serverless services </i>: It is a way to describe the services, practices, and srategies that you can use to build more agile applications. In this way, you can innovate and response to change faster. With serverless services, AWS handles infrastructure management tasks like capacity provisioning and patching so that you can focus on building applications ha serve your customers. Serverless services come with automatic scaling, built in high availability, and pay-for-value biling model.

####    Core service architecture

<img src="core_service_arch.PNG" alt="core_service_arch" style="height::100%; width: =100%;">


+   #####   Amazon VPC(virtual private cloud): 
    1.` What does Amazon VPC do?`
    It is a service tha you use to launch AWS resources in a logically solated virtual nework that you define. As a foundational AWS services, Amazon VPC makes it easy to customize your VPC's network configuration. You can create a public-facing subne for your web servers that have access to the internet. You can also use Amazon VPC to place your backend systems, such as daabases or applicatuon servers, in a private-facing subnet with no internet access. With Amazon VPC, you can use multiple layers of security to help control access to Amazon EC2 instances in each subnet. These layers include security groups and nework access control lists(network ACLs).

    2.  `What problem does Amazon VPC solve?`
        It provides features that you can use to increase and monitor the security for your VPC on demand. Therefore, you can create a data center as you need it and terminate it when you no longer need it.

    3.  `Benefits of Amazon VPC`
    +   It provides advanced security features that you can use to perform inbound and outbound filtering at the instance and subnets levels.

    +   With simple setup of Amazon VPC, you spend less time setting up, managing, and validating. Therefore, you can concenrate on building applications that run in your VPCs.
    +    It helps you control your virtual networking environment. By using Amazon VPC, you can choose your own IP Address range, create your own subnets, and configure routr tables to any available gateways.

    4. `How can I architect a cloud solution using Amazon VPC?`
       <img src="arc_cloud_solution.PNG" alt="aws_offering" style="height::100%; width: =100%;">

    5.    `How can I use Amazon VPC?`

    +    Host a simple website
    +  Host multi-tier web applications
    +    Back up and recover
    +    Extend your corporate network   

    6.   `What else should I keep in mind when using Amazon VPC?`

    When you creae a new Amazon VPC, you can have the option to create one by using a template or create one from scratch.
    When you create one from scratch, auomatically it will create a route table, a network ACL, and a security group. Then you configure them according to your needs.
    If you must delete a VPC, be sure to first terminate any EC2 or RDS instances that you have provisioned in the VPC.

    7.    `How much does Amazon VPC costs?`
 <img src="VPC_cost.PNG" alt="VPC_cost" style="height::100%; width: =100%;">
 
+   #####   Amazon Elastic Compute Cloud EC2 : Public subnet

    1. `What does Amazon EC2 do?`
    <p> It is a web service that provides secure, resizable compute capacity in the cloud. It is designed to make web-scale cloud compuing easier for developers. You can use the simple web interface of Amzaon EC2 to obtain and configure capacity with minimal fricion. It provides you with complete contol of your computing resources, and you can run it on the proven computing environment of amazon.</p><br>

    2. `What problem does Amazon EC2 solve?`
    It solves the problem of predicting upfront needs. Therefore, you dont need to know how much compute capacity or how much hard drive volume you will need when you set up your architecture. You can 
    scaleup and down as you need to.   

    3.  ` What are the benefits of Amazon EC2?`
    +   You can provision an EC2 instance in as little as 5 minutes. It gives you the options to select the right CPU,storage, and operating system for your specific needs.

    +   With Amazon EC2, you can cgange the volume size and the instance type without terminating the insance.  

    +   You can use Amazon EC2,you can change the volume size and the instance type without terminating the instance.

    +   You can use Amazon EC2 to scaleup and scaledown to meet seasonal needs. You dont need to have extra servers on hand that are used for only a few months out of the year.

    4.  `How can I use Amazon EC2?`
    <img src="arc_cloud_soln.PNG" alt="arc_cloud_soln" style="height::100%; width: =100%;">


    5. ` How can I use Amaazon EC2?`
        1.  Host multi-tier applications
        2.  Backup and disaster recovery
        3.  On-demand computing
        4.  Host databses

    6. `What else should I keep in mind when using Amazon EC2?`
 
    <img src="6.PNG" alt="" style="height::100%; width: =100%;"> 

    7.  `How much does Amazon EC2 costs?`
        1.  On-demand instances
        2.  spot instances
        3.  Reserved Instances

+   #####    Amazon RDS : Private subnet

    1.  `What does Amazon RDS do?`
    : Amazon RDS is a distributed relational database managed service. It is cloud-based and designed to simplify the seup, operation, and scaling of relational databases. Administrative process like patching, backing up databases, and enabling point-in-time recovery are managed automatically.

    
    2.  ` What problem does Amazon RDS solve?`
    : It solves the problem of purchasing a database with a capacity that is either too large or too small for your use over time. With Amazon RDS, you can scale up and down based on your database capacity needs. As a result, you are never paying for more database capacity than you need.

    3.  ` Benefits of RDS`
        <img src="benefit_RDS.PNG" alt="benefit" style="height::100%; width: =100%;">

    4.  ` How can I architect a cloud solution using Amazon   RDS?`
        : You can architect a solution to built for fault tolerance by configuring Amazon RDS for Multi-AZ deployment. To accomplish this task, you place your master RDS instance in another Availability Zone. If the primary fails, then the standby automatically becomes he new master and your system remains active.

    5.  ` How can I use Amazon RDS?` 
        1.  Web and mobile applications
        2.  Ecommerce applications
        3.  Mobile and online games      

    6.  ` What else should I keep in mind when using Amazon RDS?`

        <img src="RDS_things.PNG" alt="" style="height::100%; width: =100%;"   >

    7. ` How much does Amazon RDS cost?`
        : Its pricing follows the pay-only-for -what-you-use model. It has no minimum fee. You can play for Amazon RDS by using On-Demand or Reserved Insances, similar to what you learned about the Amazon EC2 options.
         It provides a selection of instance types that are optimized to fit different relational database use case.

+   #####   Amazon Cloud Watch     
    1.  `What does Amazon CloudWatch do?`
        : It is a monitoring and obsercation servicethat is built for Devols engineers, developers, security engineer, and IT managers. CloudWatch provides you with data and actionable insighrs to monitor your applications, respond to system-wide performance changes, and optimize resources utilization. You get a unified view of operational health.

    2. ` What problem does CloudWatch Solve?`
        <img src="cloud_watch.PNG" alt="" style="height::100%; width: =100%;"   >  

    3.  `What are the benefits of Cloudwatch?`
          <img src="benefit_cloudwatch.PNG" alt="" style="height::100%; width: =100%;"   >      

    4.   ` How can I architect a cloud solution using Cloudwatch?`
        <img src="arc_cloudwatch.PNG" alt="" style="height::100%; width: =100%;"   >  

    5.   `  How can I use CloudWatch?`

         +   Infrastructure monitoring and troubleshooting
            +   Proacive resource optiization
            +   Application monitoring

    6.  `What else should I keep in mind when using CloudWatch?`
        <img src="keep_cloudwatch.PNG" alt="" style="height::100%; width: =100%;"   >

    7.  `How much does CloudWatch cost?`
        <img src="cost_cloudwatch.PNG" alt="" style="height::100%; width: =100%;"   >    

+   ####    Amazon SNS(Simple Notification Server)
    1.  `What does Amazon SNS do?`
    <img src="sns1.PNG" alt="" style="height::100%; width: =100%;"   >

    2.  `What problem does SNS solve?`
    : It solves the problem of the appropriate subscribers not getting important information that they should be aware of, as events occur in their applicaions or infrastructure.

    3.  `What are the benefits of Amazon SNS?`

    : <img src="sns_benefit.PNG" alt="" style="height::100%; width: =100%;"   >
    
    4.  `How can I architect a cloud solution using Amazon SNS?`
    : <img src="sns_architect.PNG" alt="" style="height::100%; width: =100%;"   >

    5.  `How can I use Amazon SNS?`
        +   Standard
        +   FIFO

    6.  `What else should I keep in mind when using Amazon SNS?`
     : It cannot automate messages by itself. It must work with a service such as Amazon CloudWatch or AWS Lambda that can monitor what is going on in your architecture. he service must also be able to trigger Amazon SNS to send a notification, based on your system's configurations. 

    7.  `How much does Amazon SNS costs?`
     : It has no upfront fees, no required commitments, and no long-term contracts. You pay only for what you use, based on he type of topic that is used.

+   ####    Identity and Access Management(IAM)

    1.  `What does IAM do?`
     : It is a centralized security management system that is included in every AWS account to control identity access to AWS services. By attaching IAM permission policies to identities, you can manage which services each identity can access and the kinf of actions the identity can perform.
        Identities in IAM are (user, group, role)

    2.  `What problem does IAM solve?`
         <img src="IAM_solve.PNG" alt="" style="height::100%; width: =100%;"   >

    3.  `Benefits of IAM?`
     : It has a simple user interface that makes it easy to gran and control user access to AWS services.
     : It has many system-generated policies that you can use, and you create additional custom policies that meet the needs of your specific requirements.

    4.  `How can I architect a cloud soluion using IAM?`
     :  <img src="IAM_architect.PNG" alt="" style="height::100%; width: =100%;"   >

    5. ` How can I use IAM?` 
      + Fine-grained access control
      + Muli-factore authentication
      + Analyze access
      + Integrate with your corporate directory

    6.  `What else should I keep in mind when using IAM?`
        +   Implicity deny
        +   Explici allow
        +   Explicit deny 

    7.    `How much does IAM cost?` 
        : It is a service in your AWS accoun that is offereed at no additional charge. You are charged only when you access other AWS Services by using your IAM users credentials.

+   #### Amazon Simple Storage Service - S3
    1.  `What does Amazon S3 do ?`
     :  It is a object storage that is built to store and retrieve any amount of data from anywhere at any time. It's a simple storage service that offers industry-leading durability, availability, performance, securiy and virtuality unlimited scalability at low costs.

    2.  `What problem does Amazon S3 solve?`
     :    <img src="S3_1.PNG" alt="" style="height::100%; width: =100%;"   >   

    3.  `What are the benefits of Amazon S3?`
     :  <img src="S3_benefits.PNG" alt="" style="height::100%; width: =100%;"   > 
     
    4.  `How can I architect a cloud solution by using Amazon S3?`
        <img src="S3_benefits.PNG" alt="" style="height::100%; width: =100%;"   > 

    5.  `How can I use Amazon S3?`
        +   Backup and store 
        +   Disaster recovery
        +   Archieve
        +   Data lakes and big data analytics

    6.  `Wha else should I keep in mind when using Amazon S3?`
     :   <img src="keep_S3.PNG" alt="" style="height::100%; width: =100%;"   >   

    6.  `How much does Amazon S3 costs?`
     : With Amazon S3, you pay only for what you use. It has no minimum fee. Some prices vary across Amazon S3 Regions. Biling prices are based on the location of your S3 bucket.  

+   ####    AWS Lambda
    1.  `What does AWS Lambda do?`
     : It is a serverless compute service that you can use to run function code withoit provisioning or managing servers. You can use Lambda to run function code for virtually any type of application or backend service. You upload your code, and Lambda takes care of everything that is required to run and scale your code with high availability.

    2.  `What problem does AWS Lambda solve?`
     : AWS lambda removes all administration for application or backend services that can be processed in snippets of code. You upload your code as a .zip file or container image. Then, Lambda automatically and precisely allocates compute power to run your code based on the incoming request or event, for any scale of traffic, You can set up your code to automatically trigger from over 200 services and software as a service (Saas) applications or call it directly from any web or mobile app.

    3.  `What are the benefits of AWS Lambda?`
     :   <img src="benefit_lambda.PNG" alt="" style="height::100%; width: =100%;"   >  
     
    4.  `How can I architect a cloud solution using AWS Lambda?`
      <img src="arc_lambda.PNG" alt="" style="height::100%; width: =100%;"   >   

    5.  `How can I use Amazon Lambda?`
     +  Web applications
     +  Data processing
     +  Real-time file processing
     +  Real-time stream processing

    6.    `What else should I keep in mind when using AWS Lambda?`
     : It has a 15 minute limit on its runtime for each invocation. If your computing needs require more than 15 minutes for runtime, when you would need to use an EC2 instance instead of Lambda.

    7.  `How much does AWS Lambda cost?`
     : <img src="cost_lambda.PNG" alt="" style="height::100%; width: =100%;"   > 

+   #### Amazon Dynamo DB
    1.  `What does Amazon DynamoDB do?`
     :    It is a serverless non-relational database that can store and retrieve any amount of data and serve any level of request traffic. You can scaleyour database tables throughput capacity up or down without downtime. You can use the AWS Management Console to monitor resource utilization and performance metrics.

    2.  `   What problem does DynamoDB solve?`
     : You can use it to offload the administrative burdens of operating and scaling a distributed database. Therefore, you dont need to worry about hardware provisioning, setup and configuration, replication, software patching, or cluster scaling.

    3.  `What are the benefits of DynamoDB?`
       <img src="dynamo_benefit.PNG" alt="" style="height::100%; width: =100%;"   > 

    4.  `How can I architect a cloud solution using DynamoDB?`
      <img src="arc_dynamo.PNG" alt="" style="height::100%; width: =100%;"   > 

    5.  `How can I use DynamoDB?`
    +   Retail
    +   Gaming
    +   Banking
    +   Ad Tech

    6.  `What else should I keep in mind when using DynamoDB?`
    +   Relational Database
    +   Non-relational database

    7.  `How much does DynamoDB cost?`
     : DynamoDB changes for reading, writing, and storing data in your DynamoDB tables, along with any optional features you choose to enable. DynamoDB has two capacity modes(on-demand and provisioned), both of which come with specific billing options for processing reads and writes on your tables.

### Module5
####    Cloud careers
#####   1. `Objectives`
+   Describe the benefits of a cloud career
+   Identify different career pathways into the cloud
+   Discuss flexibility to grow your career in the cloud

#####   2. `Why choose a career in the cloud?`
+   Hundreds of services : basic compute needs to advance machine learning
+   Global operations 
+   Millions of customers
+   create job opportunities in the world

#####   3.`Benefits of a career in the world`
+   Variety of roles
    +   help desk associates
    +   Solutions architect
    +   Machine learning specialist
+   High-paying jobs
    +   Entry level up to $85,000   
    +   Experienced professional upto $200,000
    +   Average cloud salary $150,000
+   Work-life balance
    +   Jobs that require travel
    +   Jobs where you can work remotely
    +   In-office jobs

#####   4.`Basic qualifications`
+   Bachelor degree or equivalence
+   Experience with system administration, network administration, IT security systems architecture or other technical discipline
+   Scripting in a cloud-based language such as Python, Java or .NET
+   AWS Certifications

#####   5.`Solutions architect career pathway`

<img src="solution architect.PNG" alt="" style="height:100%; width:100%">

#####   6.`Cloud Career variety`
+   IT pro
+   Sales
+   Managers
+   Educators
+   Startups

### Module6
####    Final Assesment
The final assesments consists of question answer where numbers of quesions were given and we have to choose right among them.
