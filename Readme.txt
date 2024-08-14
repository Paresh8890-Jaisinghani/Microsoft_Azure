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