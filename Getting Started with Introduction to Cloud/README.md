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
Amazon EC2 : <img src="EC2billing.PNG" alt="S3billing" style="height::100%; width: =100%;">
Amazon S3 :  <img src="S3billing.PNG" alt="S3billing" style="height::100%; width: =100%;">
AWSLambda :
 <img src="lambdabilling.PNG" alt="lambdabilling" style="height::100%; width: =100%;">

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

In this, component are lossely couple. If single component fails other doesno stop functioning.

#####   Types of services
1. Managed services: A managed services is a way to describe the services that require you to manage infrastructure managemen tasks like patching, backup, and repair. These services gran you virtual access to the underlying operating sysem and services. With the managed services, you are responsible for scaling and building for high availability.