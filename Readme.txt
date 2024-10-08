### Cloud Computing ###
. High availability : provide continues user-exeperience with no apparent-downtime 
. Scalabilty : computing capacity can be increased by adding RAM vertically and horizontally by adding more instances such as more virtual machines
. Elasticity : Different resources at a time
. Agitlity : applications can be deployed quick and changed as requirment changes
. Geo Distribution : applications cna be available across the globe easily
. Disater Recovery : Allow backups , no worries of data lost.



(Udemy Module 2)
### Cloud service Models ###

### Iaas ## (Infrastructure as a service) a cloud provider will keep the hardware up-to-date, but operating system maintenance and network configuration is up to you as the cloud tenant.
Provides 
1. Data Center
2. Networking firewall 
3. Servers and storage

### Paas ### (Platform as a service) The cloud provider manages the virtual machines and networking resources, and the cloud tenant deploys their applications into the managed hosting environment.
Iaas + 
1.Operating systems
2.Develpoment tools

### Saas ### (software as a service) the cloud provider manages all aspects of the application environment, such as virtual machines, networking resources, data storage, and applications. The cloud tenant only needs to provide their data to the application managed by the cloud provider.
Paas + 
1. Hosted applications




### Deployment Models ###
1. Public Cloud : In a public cloud, services are offered over the public internet and available to anyone who wants to purchase them. Cloud resources, such as servers and storage are owned and operated by a third-party cloud service provider and delivered over the Internet.

2. Private Cloud : A private cloud consists of computing resources used exclusively by users from one business or organization. A private cloud can be physically located at your organization's on-site or on-premises data center

3. Hybrid Cloud : hybrid cloud computing environments combine a public cloud and a private cloud by allowing data and applications to be shared between them





### Azure resources and Azure Resource Manager ### 
1.Resource, a manageable item that's available through Azure virtual machines or VM storage accounts, Web APS Databases on virtual networks are examples of Resources

2.Resource Group, a container that holds related resources for an Azure solution. The resource group includes resources that you want to manage as a group. 

3.If you delete a resource group, all resources contained within it are also deleted. Organizing resources by life cycle could be useful in non-production environments where you might try an experiment and then dispose of it

4.Azure Resource Manager commonly referred to his ARM, is the deployment and management service for Azure. It provides a management layer that enables you to create, update and delete resources in your Azure account.



What is App Service?
App Service is an HTTP-based service that enables you to build and host many types of web-based solutions without managing infrastructure. For example, you can host web apps, mobile back ends, and RESTful APIs in several supported programming languages.


What is Azure Marketplace?
Azure Marketplace is an online store that hosts applications that are certified and optimized to run in Azure. Many types of applications are available, ranging from AI and machine learning to web applications.


### Exercise - Create a website hosted in Azure### 
1.Sign in to the Azure portal by using the same account you used to activate the sandbox.
2.On the top of the Azure portal left pane, select Create a resource.
3.In the Search the Marketplace box with the listed application options, enter WordPress. Select the default WordPress option from the list of options available.


### Azure Cosmos db ###
1.Azure Cosmos DB is a flexible database that provides guaranteed single digit milliseconds response times and 99.999% availability backed by comprehensive SLAs
2.Elastic and independent scale throughput and storage on demand.
3.access to multiple data models and APIs for working with your data.
4.ability to globally distribute your data and build highly responsive applications

### Azure Sql database ###
1.Azure SQL Database provides you with a high performance, reliable, fully managed and secure database.
2.it enables you to process both relational data and non relational structures such as graphs, JSON, Spatial and XML
3.Azure SQL (sequel) Database is a platform as a service (PaaS) database engine. It handles most of the database management functions, such as upgrading, patching, backups, and monitoring, without user involvement.
4.You can migrate your existing SQL Server databases with minimal downtime by using the Azure Database Migration Service.


### Exercise - Create an Azure SQL Database ###
1. Sign in to the Azure portal.
2. Select Create a resource > Databases > SQL database
3.Refer Module3 courseera


### Azure SQL Managed Instance ### 
1.Like Azure SQL Database, Azure SQL Managed Instance is a platform as a service Database Engine, which means that your company will be able to take advantage of the best features of moving your data to the cloud in a fully managed environment.
2. Azure SQL Managed Instance makes it easy to migrate your on-premises data on SQL Server to the client using the Azure Database Migration Service, DMS, or native backup and restore.


### Azure Database for MySQL ###
1.Azure Database for MySQL is a relational database service in the cloud, and it's based on the MySQL community edition database engine.
2.you have a 99.99 percent availability service level agreement from Azure, powered by a global network of Microsoft managed data centers. This helps keep your app running 24/7.
3.high availability with no additional cost, predictable performance, and inclusive pay-as-you-go pricing, scale is needed within seconds, ability to protect sensitive data at rest and in motion, automatic backups, and enterprise-grade security, and compliance. 

### Azure Database for PostgreSQL ###
1.Azure database for PostgreSQL is a relational database service in the cloud. The server's software is based on the community version of the open-source PostgreSQL database engine.
2.Built-in high availability compared to on-premises resources. There's no additional configuration, replication, or cost required to make sure your applications are always available. Simple and flexible pricing.


### Azure Synapse Analytics ###
Azure Synapse Analytics is the logical choice for analyzing large volumes of data. Azure Synapse Analytics (formerly Azure SQL Data Warehouse) is a limitless analytics service that brings together enterprise data warehousing and big data analytics. 


### Azure compute services ### 
Azure compute is an on-demand computing service for running Cloud-based applications. It provides computing resources such as disks, processors, memory, networking, and operating systems


What are Virtual Machines? Virtual Machines are software emulations of physical computers. They include a virtual processor, memory, storage, and networking resources. Virtual Machines host an operating system and you can install and run software just like a physical computer.
Virtual Machines provides infrastructure as a service (IaaS) and
can be used in different ways. If you want to provision Linux and Windows virtual machines with the configurations of your choice, you could so in seconds using Azure Virtual Machines services.

what are Virtual Machine Scale Sets? Virtual Machine Scale Sets are an Azure compute resource that you can use to deploy and manage a set of identical Virtual Machines, Azure Virtual Machine Scale Sets lets you create and manage a group of identical load balanced Virtual Machines. Scale Sets allow you to centrally manage, configure and update a large number of Virtual Machines in minutes to provide highly available applications. 


App Service enables you to build and host web apps, background jobs, mobile backends, and RESTful APIs in the programming language of your choice, without managing infrastructure






### Project Description ###

1. Azure CLI
What It Does: Azure CLI is a command-line tool that allows you to manage Azure resources directly from your terminal. It simplifies tasks like creating and managing Azure resources.
How It’s Running: Installed on your local machine, you interact with Azure using commands such as:

az login to authenticate with your Azure account.
az group create --name MyResourceGroup --location eastus to create a resource group.
az functionapp create --resource-group MyResourceGroup --consumption-plan-location eastus --runtime node --name MyFunctionApp --storage-account <StorageAccountName> to create a function app.
Dependencies: It depends on internet connectivity to interact with Azure services and requires authentication via az login.


2.Azure Resource group
These are like folders where you organize and manage all your related Azure services (like storage, databases, or virtual machines) together. It helps keep things organized and easier to manage.


3.Azure resource
These are the individual services or components you use in Azure, like a virtual machine, a database, or storage. Each resource does a specific job within your cloud setup.



4. Azure Functions
What It Does: Azure Functions is a serverless compute service that allows you to run event-driven code without managing any servers. It’s perfect for running small pieces of code (functions) in response to various events, such as HTTP requests, timers, or messages from other Azure services.

How It’s Running: You created a function named "myFunction," which runs in response to a specific trigger, such as an HTTP request. The function is deployed to Azure and is automatically scaled by Azure based on demand.

Dependencies: Azure Functions depends on the Azure infrastructure to execute the code. It can also depend on other Azure services like Azure Table Storage for storing data. Azure Functions can be managed and deployed through the Azure CLI or the Azure portal.
steps:
npm install -g azure-functions-core-tools@4 --unsafe-perm true
Navigate to the directory where you want to create your project.
func init ToDoApp --javascript
cd ToDoApp
func new
func start

5.