![](https://github.com/Manjil-sharma/Microsoft-Azure-Fundamentals/blob/main/Git%20hub/server.jpg)  


# Microsoft-Azure-Fundamentals
I will be studying about Azure Fundamentals by Microsoft and updating daily about my progress and understanding. I will be following SK Singh for Cloud Computing and Andrew Brown for Microsoft Azure Fundamentals.

## Day 1 of #Microsoft Azure Fundamentals
:large_blue_diamond: **Course**: **Microsoft Azure Fundamentals (AZ-900)** <br>

Today I learned what Cloud Computing  is, common terminology, and common components and a little bit of history before the rise of Cloud.<br>

### Cloud Computing
It is the practice of using a network of remote servers hosted on the Intenet to store, manage, and process data, rather than a local server or a personal computer.<br>

### Evolution to Cloud Hosting

#### Dedicated Server
- Dedicated servers are one physical machine dedicated to a single business.<br>
- It only runs single web-app/site.
- It is very expensive and need high maintenancec but has high security.
- But every time we need a new business app/site, We need a new physical server.
- Since only one app/site uses the entire server the resources of the server will not be fully utalized.

### Virtual Private Server
- The Virtual Private Server is also a physical machine dedicated to a single business but the Physical machine is virtualized into sub-machines.
- Due to virtulization multiple web-apps/sites can run on single server.
- Hypervisor is placed on top of the Host Operating System due to which many virtual machines can be created .
- Those VM's runs independently and can runs different Operating System in different VM's.
- By the use of virtualization the resources can be more utalized then Dedicated server.

### Shared Hosting
- In Shared Hosting one physical machine is shared by hundred of business organization.
- It is very cheap but with some limitations.
- Relies on most tenants under-utilizing their resources. It means that if one person is using more resources then other the all other will be affected by it.

### Cloud Hosting
- In Cloud Hosting multiple physical machine act as one system which could be described as a cloud.
- The system is abstracted into multiple cloud services.
- It's flexible, Stable, Secure, Cost-effective and comes with high Configurability.


## Day 2 of #Microsoft Azure Fundamentals<br>

:large_blue_diamond: **Course**: **Microsoft Azure Fundamentals (AZ-900)** <br>

Today I learned about common cloud services for Infrastructure as a service(IaaS).<br>

### Common Cloud Services

A Cloud provider can have hundreds of Cloud Services that are grouped into various types of services. The  four most common types of Cloud Services for Infrastructure as a services(IaaS) would be:<br>

### Compute
Compute in Infrastructure as a Service (IaaS) cloud computing refers to the virtualized computing resources and services provided by the cloud service provider. These resources and services may include:<br>

- Virtual Machines (VMs): Provides customers with virtualized servers that can be used to run applications and services.

- Containers: Offers a way to package and run applications and services in a lightweight, portable, and consistent manner.

- Serverless Computing: Enables customers to run code without having to provision or manage servers, allowing them to focus on writing and running code rather than managing infrastructure.

- Automated Scaling: Automatically increases or decreases the number of virtual machines based on demand, ensuring that resources are always available to meet the needs of the application.

- Resource Management: Offers tools and services for managing computing resources, such as resource allocation, capacity planning, and cost optimization.

In IaaS cloud computing, customers have the flexibility to adapt their compute infrastructure to meet their specific requirements. With a range of compute services and configurations available, customers can quickly and easily deploy and manage their applications and services in the cloud. The scalable and versatile nature of IaaS computing allows customers to efficiently meet the demands of their applications, while optimizing costs and maximizing performance.<br>

### Networking
In Infrastructure as a Service(IaaS) cloud computing, networking refers to the virtual network infrastructure and related services offered by the cloud provider to its clients. These services may include:<br>

- Virtual Private Networks (VPNs): Enables secure connectivity between on-premises and cloud-based resources.

- Load Balancing: Distributes network traffic across multiple servers to optimize performance and ensure availability.

- IP Addressing: Allocates and manages IP addresses for virtual resources.

- Domain Name System (DNS): Resolves domain names to IP addresses, making it easier for users to access cloud-based applications and services.

- Network Security: Includes firewalls, security groups, and other security measures to protect against network-based attacks.

- Network Monitoring: Provides visibility into network performance and usage to help identify and resolve issues.

In IaaS, customers have the ability to configure and manage the network infrastructure according to their needs, and can choose from a range of network services and configurations to meet their requirements. This flexible and scalable approach to networking enables customers to quickly and easily deploy and manage their applications and services in the cloud.<br>



### Storage
In Infrastructure as a Service (IaaS) cloud computing, storage refers to the virtualized storage infrastructure and services provided by the cloud service provider. These services may include:<br>

- Object Storage: Provides scalable, highly available, and cost-effective storage for unstructured data, such as images, videos, and log files.

- Block Storage: Offers low-latency, high-performance storage for applications requiring direct access to block-level data, such as databases.

- File Storage: Provides network-attached storage for file-based applications, such as file servers and home directories.

- Backup and Recovery: Includes solutions for backing up and recovering data, such as snapshots, backups, and disaster recovery.

- Data Management: Offers tools and services for managing data, such as data tiering, data replication, and data protection.

In IaaS cloud computing, customers have the flexibility to tailor their storage infrastructure according to their specific needs. With a range of storage services and configurations to choose from, customers can easily store and manage their data in the cloud, adapting to their evolving requirements over time. This scalability and versatility allow for a more efficient and cost-effective approach to data management in the cloud.<br>



### Database
Databases refer to the virtualized database infrastructure and services provided by the cloud service provider. These services may include:<br>

- Relational Databases: Offers structured data storage for applications, such as SQL databases.

- NoSQL Databases: Provides non-relational data storage for unstructured or semi-structured data, such as document databases and key-value stores.

- In-Memory Databases: Offers high-speed access to data for real-time applications, such as caching and session management.

- Managed Databases: Provides fully managed database services, such as database administration, backup and recovery, and security.

- Database Migration: Offers tools and services for migrating existing databases to the cloud, such as database replication and migration tools.

In IaaS cloud computing, customers have the flexibility to customize their database infrastructure to fit their specific needs. With a variety of database services and configurations available, customers can quickly and easily deploy and manage their applications and services in the cloud. The scalability and versatility of IaaS databases allow for efficient data management, ensuring reliability and performance, while also allowing for seamless integration with existing systems.<br>



## Day 3 of #Microsoft Azure Fundamentals<br>
:large_blue_diamond: **Course**: **Microsoft Azure Fundamentals (AZ-900)** <br>

Today, I gained understanding of the advantages of Cloud Computing and how it addresses challenges faced in traditional methods while delivering reliability, speed, efficiency, and cost-effectiveness.<br>


### Benefits of Cloud Computing<br>

### Scalability

Scalability in cloud computing refers to the ability of a system, network, or process to handle a growing amount of work, or its potential to be enlarged in order to accommodate that growth. In cloud computing, scalability refers to the ability of a cloud-based system to easily increase or decrease its capacity in response to changing demand for computing resources. This means that organizations can quickly and efficiently add or remove resources, such as computing power, storage, or bandwidth, to meet their current needs without having to make significant investments in hardware or infrastructure. Scalability is a key benefit of cloud computing, as it allows organizations to respond quickly to changing business needs and avoid the costs and downtime associated with traditional, hardware-based systems.<br>

For example an e-commerce company uses cloud computing to handle holiday season traffic surges. It can quickly provision additional resources as needed, rather than investing in hardware beforehand, providing a better experience for customers while avoiding excess capacity costs.<br>

### Accessibility

Accessibility in cloud computing refers to the ease with which users can access the cloud-based services and resources they need, from anywhere, at any time. This is made possible by the use of internet technologies and remote access protocols, which allow users to access their data and applications over the internet from any device with an internet connection.<br>

In cloud computing, accessibility is an important feature as it allows organizations to increase mobility and collaboration among their employees, partners, and customers. It also allows organizations to reduce their reliance on physical infrastructure, such as servers and data centers, and instead use remote resources provided by the cloud service provider. This can help organizations save time, reduce costs, and increase efficiency. Additionally, cloud computing provides accessibility by allowing organizations to store and access data and applications securely in the cloud, reducing the risk of data loss or theft, and allowing for business continuity in the event of an emergency or disaster.<br>

### Reliability

Reliability is one of the key benefits of cloud computing. It refers to the ability of a cloud-based system to consistently deliver the desired level of performance and availability, even in the face of failures or other challenges.<br>

Reliability is achieved through the use of redundant systems and processes, such as multiple servers and data centers, that ensure that the data and applications stored in the cloud are always available and accessible to users. The cloud service provider is responsible for maintaining and updating these systems, reducing the burden on organizations to manage their own infrastructure.<br>

Additionally, cloud service providers often have robust disaster recovery and business continuity plans in place, which can help organizations mitigate the risks associated with data loss or downtime. With cloud computing, organizations can experience increased reliability, knowing that their data and applications are always accessible and secure, regardless of the situation. This can help organizations improve their overall efficiency, reduce costs, and increase customer satisfaction.<br>

### Pay-as-you-go

It refers to a pricing model in which organizations only pay for the computing resources they actually use, rather than paying upfront for a set amount of resources.<br>

In cloud computing, this model is made possible by the use of virtualized resources and flexible, on-demand pricing. This allows organizations to adjust their usage as needed, without having to make large upfront investments in hardware or infrastructure. For example, if an organization experiences a temporary spike in traffic or computing needs, it can quickly provision additional resources, and then release them once the demand subsides.<br>

The pay-as-you-go model provides several benefits for organizations, including reduced costs, improved financial flexibility, and the ability to respond quickly to changing business needs. It also allows organizations to avoid the risks associated with overprovisioning or underprovisioning resources, which can lead to increased costs, downtime, and reduced efficiency. Overall, the pay-as-you-go model is one of the key reasons why cloud computing has become so popular, and is a key factor that drives its growth and success.<br>


### Automatic Updates

Automatic updates is another important benefit of cloud computing. It refers to the ability of the cloud service provider to automatically update the software, tools, and other components that make up the cloud environment, without requiring manual intervention or downtime.<br>

Automatic updates provide several key benefits for organizations. First, they help organizations stay up-to-date with the latest features and security patches, reducing the risk of vulnerabilities or attacks. Additionally, they help organizations avoid the time and costs associated with manual updates, and ensure that the cloud environment is always running optimally.<br>

Moreover, automatic updates in cloud computing allow organizations to take advantage of new technologies and capabilities more quickly and efficiently, without having to go through a lengthy procurement and implementation process. This can help organizations stay ahead of the competition and increase their overall competitiveness.<br>

Overall, automatic updates are an important factor in ensuring the reliability, security, and performance of cloud-based systems, and help organizations take full advantage of the benefits of cloud computing.<br>


### Elastic

Elasticity  refers to the ability of a cloud-based system to automatically scale up or down in response to changes in demand, providing users with the necessary resources and capacity to meet their needs. It is achieved through the use of virtualized resources, such as virtual machines and storage, that can be quickly and easily provisioned and de-provisioned as needed. This allows organizations to quickly adjust their resource usage in response to changing needs, without having to make large upfront investments in hardware or infrastructure.<br>

Elasticity provides several key benefits for organizations, including increased agility, reduced costs, and improved efficiency. It also helps organizations avoid the risks associated with overprovisioning or underprovisioning resources, which can lead to increased costs, downtime, and reduced efficiency.<br>


### Conclusion
These are some of the key benefits of cloud computing: scalability, accessibility, reliability, pay-as-you-go pricing, automatic updates, and elasticity. Each of these benefits provides organizations with significant advantages in terms of cost, performance, and efficiency, helping to drive the growth and success of cloud computing.<br>

For example, scalability allows organizations to quickly and easily adjust their resource usage in response to changing demands, helping to ensure that they always have the capacity they need to meet their business needs. Accessibility provides users with secure and convenient access to their cloud-based systems from anywhere, at any time, using any device, making it easier to work remotely or collaborate with others. Reliability helps organizations avoid downtime and minimize the risk of data loss or corruption, while pay-as-you-go pricing allows organizations to avoid the risks associated with overprovisioning or underprovisioning resources. Automatic updates help organizations stay up-to-date with the latest software, security patches, and other features, while elasticity allows organizations to respond quickly to changing demands.<br>

Overall, these benefits make cloud computing a compelling choice for organizations of all sizes and industries, helping them to save time, money, and effort while improving their overall efficiency and competitiveness.<br>


## Day 4 of #Microsoft Azure Fundamentals
:large_blue_diamond: **Course**: **Microsoft Azure Fundamentals (AZ-900)** <br>

Today, I gained insight into the different types of Cloud Computing and their significance. I also discovered the responsibilities associated with each type of Cloud Computing.<br>

### Types of Cloud Computing
There are three main types of cloud computing:<br>


### Software as a service(SaaS)

Software as a Service (SaaS) is a type of cloud computing that delivers software applications over the internet, on a subscription basis. The software is hosted by a third-party provider and is made available to customers over the internet, without the need for them to install or run the application on their own local computers or servers. Examples of SaaS providers are Salesforce, Google Workspace, and Microsoft 365.<br>


### Platform as a Service(PaaS)

Platform as a Service (PaaS) is a type of cloud computing that provides a platform for the development, deployment, and management of applications and services over the internet. PaaS provides a complete development environment in the cloud, including tools, frameworks, and infrastructure resources such as servers, storage, and databases. Developers can build, test, and deploy applications on the PaaS provider's platform, without having to worry about underlying infrastructure management. PaaS is often used for web and mobile application development. Examples of PaaS providers are Google App Engine, Microsoft Azure, and Heroku.<br>

### Infrastructure as a Service(IaaS)

Infrastructure as a Service (IaaS) is a type of cloud computing that provides virtualized computing resources over the internet. This includes virtual machines, storage, and network resources. Customers can rent these resources on an as-needed basis and only pay for what they use, rather than having to invest in and maintain their own physical infrastructure. IaaS provides a scalable and flexible solution for organizations to run their applications and services, without having to invest in and maintain their own physical infrastructure. Examples of IaaS providers are Amazon Web Services (AWS), Microsoft Azure, and Google Cloud Platform.<br>


![](https://github.com/Manjil-sharma/Microsoft-Azure-Fundamentals/blob/main/Git%20hub/cloud%20services.png?raw=true)

### Cloud Computing Responsibilities

The shared responsibility model is a concept in cloud computing that outlines the responsibilities of both the cloud service provider and the customer for various aspects of the cloud infrastructure. The idea is that the cloud service provider is responsible for some parts of the infrastructure and the customer is responsible for others, and the specific responsibilities depend on the type of cloud service model being used (IaaS, PaaS, or SaaS).<br>

The shared responsibility model can be visualized in a table format, where the responsibilities of the cloud service provider and the customer are clearly outlined for various aspects of the cloud infrastructure. By reviewing this table, you can get a clear understanding of what each party is responsible for, including hardware, network, storage, virtual machines, operating systems, and data.<br>

<p align="center">
  <img src="https://github.com/Manjil-sharma/Microsoft-Azure-Fundamentals/blob/main/Git%20hub/cloud-resp.png?raw=true">
</p><br>



## Day 5 of #Microsoft Azure Fundamentals
:large_blue_diamond: **Course**: **Microsoft Azure Fundamentals (AZ-900)** <br>

Today, I gained an in-depth understanding of the various deployment models available on Azure, the cloud computing platform. These deployment models include the Public Cloud, Private Cloud, Hybrid Cloud, and Cross-Cloud, each offering its own unique set of benefits and advantages.

### Azure's Deployment Models

Azure offers a range of deployment models to support different types of computing scenarios:<br>

### Public Cloud

Azure Public Cloud is a cloud computing service provided by Microsoft through its Azure platform. It is a shared computing infrastructure, accessible to the general public over the internet. It provides a range of services and resources, such as virtual machines, storage, databases, and networking, that can be easily provisioned and scaled on demand.<br>

In Azure Public Cloud, the infrastructure, hardware, and underlying resources are owned, maintained, and managed by Microsoft. Customers access these resources via the internet and pay only for what they use. The public cloud model provides a cost-effective and flexible way to meet the computing needs of organizations of all sizes, without the upfront investment required to build and maintain their own infrastructure.Azure Public Cloud is also sometimes referred to as a "native cloud" because it is built from the ground up to be a cloud computing service.<br>
<p align="center">
  <img src="https://github.com/Manjil-sharma/Microsoft-Azure-Fundamentals/blob/main/Git%20hub/public%20cloud.PNG?raw=true">
</p><br>


### Private Cloud

Azure Private Cloud is a deployment model for the Azure platform that provides a dedicated, isolated computing environment within a customer's own data center. In this model, the infrastructure, hardware, and underlying resources are owned, maintained, and managed by the customer, while Microsoft provides the Azure platform and management services.<br>

This deployment model is intended for customers who have specific security, regulatory, or compliance requirements that cannot be met by a public cloud service. With Azure Private Cloud, customers can run their workloads on a fully managed and highly secure infrastructure that is dedicated to their organization.<br>

The Azure Private Cloud deployment model provides customers with greater control over their computing environment and a higher degree of customization. It also enables customers to leverage the benefits of the cloud, such as scalability and flexibility, while retaining full control over their data and compliance requirements.<br>

<p align="center">
  <img src="https://github.com/Manjil-sharma/Microsoft-Azure-Fundamentals/blob/main/Git%20hub/private%20cloud.PNG?raw=true">
</p><br>

### Hybrid Cloud

Azure Hybrid Cloud is a deployment model that combines the benefits of both public and private clouds. It allows organizations to run their workloads in both environments and easily move workloads between them.<br>

In an Azure Hybrid Cloud environment, some workloads can be run in the public cloud, taking advantage of its scalability and cost-effectiveness, while others can be run in the private cloud, providing greater control and security. This deployment model provides organizations with the ability to choose the best environment for each workload, based on their specific requirements.<br>

The Azure Hybrid Cloud deployment model provides organizations with maximum flexibility and choice, enabling them to optimize their computing resources based on their specific needs and requirements.<br>

<p align="center">
  <img src="https://github.com/Manjil-sharma/Microsoft-Azure-Fundamentals/blob/main/Git%20hub/Hybrid-cloud.png?raw=true">
</p><br>


### Cross-Cloud

Azure Cross-Cloud is a solution that allows organizations to run their workloads across multiple cloud environments, including Azure and other cloud platforms, providing maximum flexibility and choice.<br>

With Azure Cross-Cloud, customers can take advantage of the strengths of each cloud environment, such as the scalability and cost-effectiveness of public clouds, and the control and security of private clouds. This enables customers to choose the best environment for each workload, based on their specific requirements.<br>

The Azure Cross-Cloud solution provides organizations with the ability to optimize their computing resources based on their specific needs and requirements, across multiple cloud environments.<br>

<p align="center">
  <img src="https://github.com/Manjil-sharma/Microsoft-Azure-Fundamentals/blob/main/Git%20hub/cross.PNG?raw=true">
</p><br>



## Day 6 of #Microsoft Azure Fundamentals
:large_blue_diamond: **Course**: **Microsoft Azure Fundamentals (AZ-900)** <br>

Today I learned about the total cost of ownership (TCO) in cloud computing and how it's an important factor to consider when evaluating cloud solutions.<br>

### Total Cost of Ownership

Total Cost of Ownership (TCO) refers to the total cost of using cloud services, which includes both the direct costs such as the cost of cloud storage and computing services and indirect costs such as the cost of network connectivity and management.<br>

Some of the factors that contribute to TCO in cloud computing include:<br>

- Usage costs: This includes the cost of the cloud services used, such as storage, compute power, and bandwidth.<br>

- Data transfer costs: Data transfer costs are charged when data is transferred in and out of the cloud.<br>

- Network connectivity costs: This includes the cost of connecting to the cloud service provider's network, such as VPN or direct connect.<br>

- Security and compliance costs: These include the costs of ensuring data security and compliance with regulatory requirements.<br>

- Management and administration costs: This includes the cost of managing and administering cloud services, including the cost of tools and staff required for this purpose.<br>

It's important to take all of these costs into consideration when evaluating the TCO of a cloud computing solution, as the total cost can be significantly higher than just the cost of the cloud services themselves.<br>



<p align="center">
  <img src="https://github.com/Manjil-sharma/Microsoft-Azure-Fundamentals/blob/main/Git%20hub/total%20cost.PNG?raw=true">
</p><br>



The table is a comparison of the Total Cost Of Ownership (TCO) between using an on-premises data center and using Microsoft Azure cloud services. The comparison reveals that while the initial cost of purchasing software licenses and setting up an on-premises data center may seem lower, the long-term costs associated with hardware, IT personnel, maintenance, and physical security can quickly add up. In contrast, the subscription fees for Azure cloud services may be higher, but we only have to pay for the costs of implementation, configuration, and training.<br>





## Day 7 of #Microsoft Azure Fundamentals

:large_blue_diamond: **Course**: **Microsoft Azure Fundamentals (AZ-900)** <br>

Today, I gained understanding about the importance of Capital Expenditure (CAPEX) and Operational Expenditure (OPEX) in making informed decisions regarding cloud computing strategies for an organization.<br>


<p align="center">
  <img src="https://github.com/Manjil-sharma/Microsoft-Azure-Fundamentals/blob/main/Git%20hub/capvsop.png?raw=true">
</p><br>


### Capital Expenditure(CAPEX)

Capital expenditures (CAPEX) refers to the investments made in purchasing hardware, software, and other resources that are required to establish and maintain a cloud infrastructure. These investments are usually made by businesses and organizations to meet their long-term computing needs.<br>

Examples of capital expenditures in cloud computing include:<br>

- Purchasing servers, storage devices, and other physical hardware.<br>
- Buying licenses for cloud-based software and services.<br>
- Investing in network infrastructure, such as switches, routers, and firewalls.<br>
- Hiring experts to design, implement, and manage the cloud infrastructure.<br>

Capital expenditures are typically large, one-time expenses that are not incurred on a regular basis. The goal of capital expenditures in cloud computing is to create a scalable, flexible, and highly available computing infrastructure that can support the organization's computing needs for several years to come.<br>


### Operational Expenditure(OPEX)

Operational expenditures (OPEX) refers to the ongoing costs associated with using and maintaining a cloud infrastructure. These costs are incurred on a regular basis and are separate from capital expenditures, which are one-time investments made in purchasing hardware and software resources.<br>

Examples of operational expenditures in cloud computing include:<br>

- Monthly or annual subscription fees for cloud-based software and services.<br>
- Pay-as-you-go charges for using computing resources, such as virtual machines and storage.<br>
- Costs for maintaining and updating the cloud infrastructure, such as hardware upgrades, software patches, and security measures.<br>
- Labor costs for managing and supporting the cloud infrastructure, including the salaries of IT staff and contractors.<br>

Operational expenditures are an important consideration for organizations that are planning to adopt cloud computing, as they can significantly impact the overall cost of using the cloud. To minimize operational expenditures, organizations may choose to adopt cost-saving strategies, such as using reserved instances, implementing cost monitoring tools, and optimizing their use of cloud resources.<br>





## Day 8 of #Microsoft Azure Fundamentals
:large_blue_diamond: **Course**: **Microsoft Azure Fundamentals (AZ-900)** <br>

Today I learned about two important concepts in cloud computing: high availability and scalability. <br>

### High Availability

High availability (HA) is a key concept in cloud computing, which refers to the ability of a system, service, or application to remain operational and accessible to users during planned or unplanned downtime or outages. The goal of high availability is to minimize or eliminate system downtime, thereby ensuring that users are able to access and use the system, service, or application as needed.<br>

In cloud computing, high availability can be achieved through various techniques and approaches, including the use of multiple redundant components, such as load balancers, databases, and servers, as well as through the deployment of services across multiple geographic locations, also known as geographic redundancy. Other approaches to high availability in cloud computing include the use of automation and orchestration tools to manage and recover from failures, as well as the use of virtualization and containerization to ensure that services and applications are isolated from each other and can be restarted and rescheduled quickly and easily in the event of a failure.<br>

Overall, high availability is a critical component of cloud computing, as it helps ensure that users are able to access and use cloud-based services and applications with minimal disruption, even in the face of failures and outages.<br>


<p align="center">
  <img src="https://github.com/Manjil-sharma/Microsoft-Azure-Fundamentals/blob/main/Git%20hub/availability.PNG?raw=true"><br>
  <em>Running workload across multiple Availability zones ensures that if 1 or 2 (Availability Zones)AZs become unavailable but the Service/application remains available.</em>
</p><br>



### High Scalability

High scalability is a characteristic of cloud computing that enables systems, applications, and services to handle increasing loads of work by adding more resources as needed. The goal of high scalability is to ensure that the system continues to perform well and meet the demands of its users, even as the number of users, transactions, or data increases.<br>

In cloud computing, scalability is often achieved through the use of elastic computing resources, such as virtual machines, containers, and storage, that can be easily added or removed as needed. This allows organizations to quickly and easily scale their systems and applications to meet changing demands, without the need for significant upfront investments in hardware and infrastructure.<br>

High scalability in cloud computing can also be achieved through the use of automation and orchestration tools, which can help manage and distribute the load across multiple resources, as well as through the use of load balancing and auto-scaling techniques, which can help ensure that resources are added and removed as needed to maintain optimal performance.<br>

Overall, high scalability is a critical component of cloud computing, as it enables organizations to rapidly respond to changes in demand, while also reducing costs and increasing the reliability and performance of their systems, applications, and services.<br>

#### Vertical Scalling

- It means changing the capacity of a resource. For example you could move an application to a larger VM size.<br>
- It depends on hte avvailability of larger hardware which quickly hits an upper limit.<br>
- Example  changing capacity of Memory, GPU, Cpu cores etc.<br>

<p align="center">
   <img src="https://github.com/Manjil-sharma/Microsoft-Azure-Fundamentals/raw/main/Git%20hub/vertical%20scalling.PNG?raw=true"><br>
  <em>The above picture shows the vertical scaling in which the existing server size is increased.</em>
</p><br>



### Horizontal Scaling 

- It means adding or removing instance of a resource.<br>
- The application continues runing without interruption as new resources are provisioned.<br>
- More flexible in a cloud situation as it allow you to run potentially thousand of VM's to handle the load.<br>


<p align="center">
  <img src="https://github.com/Manjil-sharma/Microsoft-Azure-Fundamentals/blob/main/Git%20hub/horizontal%20scaling.PNG?raw=true"><br>
 <em> The above picture shows the Horizontal Scalling in which multiple servers are added of same size.</em>
</p><br>


- NOTE<br>

      Vertical Scalling -Scalling Up (Increasing the memory, GPU, CPU Cores etc of existing servers)
                        -Scalling down (Decreasing the memory, GPU, CPU Cores etc of existing servers)
                  
      Horizental Scalling -Scalling Out (Add more servers of same size)
                          -Scaling In (Removing more services of same size)
                  
                  




## Day 9 of #Microsoft Azure Fundamentals
:large_blue_diamond: **Course**: **Microsoft Azure Fundamentals (AZ-900)** <br>

Today I continued learning about other concept in cloud computing: Elasticity, Fault Tolorance and Durability.<br>

### High Elasticity

High elasticity in cloud computing refers to the ability of a cloud computing environment to dynamically scale its resources in response to changes in demand. The concept of elasticity is a key characteristic of cloud computing, and it is one of the key benefits that cloud computing provides over traditional IT infrastructure.<br>

With high elasticity, cloud computing allows organizations to quickly and easily add or remove computing resources as needed to accommodate changes in workloads. For example, if a company experiences a sudden increase in traffic to its website, it can quickly add more computing resources to handle the increased load, and then remove those resources once the traffic subsides.<br>


### How automatic increase and decrease happen?

- Azure VM Scale Set<br>

    It automatically increase or decrease in response to demand or a defeined scheduel.<br>

- SQL Server Streach Database<br>

    Dynamically strech warm and cold transactional data from Microsoft SQL Server 2016 to Microsoft Azure.<br>
    
    
    

### High Fault Tolerance

High fault tolerance in cloud computing refers to the ability of a cloud computing system to continue functioning correctly, even in the event of component failures or other system disruptions. Fault tolerance is a critical characteristic of cloud computing, as it helps ensure the availability and reliability of cloud-based applications and services.<br>

With high fault tolerance, cloud computing systems can detect and automatically recover from failures, without significant impact on the users or customers. For example, if a server fails, the system can automatically redirect traffic to another server, allowing the application to continue functioning with minimal downtime.<br>

In addition to improving availability and reliability, high fault tolerance can also help organizations reduce the risk of downtime and data loss, and improve their overall disaster recovery capabilities.<br>



### High Durability

High durability refers to the ability of a cloud computing system to persistently store data, even in the event of component failures or other disruptions. Durability is a critical aspect of cloud computing, as it helps ensure the integrity and availability of data stored in the cloud.<br>

With high durability, cloud computing systems use redundant storage, backup and recovery mechanisms, and other techniques to ensure that data is protected and can be recovered in the event of a failure. For example, cloud providers often store multiple copies of data in different geographic locations, so that data can be recovered even in the event of a disaster.<br>

High durability is a key benefit of cloud computing, as it enables organizations to store data in the cloud with confidence, knowing that their data is protected and can be recovered in the event of a failure. This can help organizations reduce the risk of data loss, improve their disaster recovery capabilities, and improve the overall availability and reliability of their data.<br>




## Day 10 of #Microsoft Azure Fundamentals
:large_blue_diamond: **Course**: **Microsoft Azure Fundamentals (AZ-900)** <br>

The evolution of computing has progressed from dedicated servers to virtual private servers to containers, and finally to serverless computing, where customers only need to upload their code and specify the amount of memory needed, making it a cost-effective and efficient solution.

### Dedicated Servers

A dedicated server is a physical server that is entirely dedicated to the use of a single customer. This type of server provides the customer with complete control and access to all of its underlying resources, including processing power, memory, storage, and network resources. However, there are a few potential drawbacks to consider when using a dedicated server.<br>

<p align="center">
  <img src="https://github.com/Manjil-sharma/Microsoft-Azure-Fundamentals/blob/main/Git%20hub/dedicated%20server.PNG?raw=true"><br>
 
</p><br>

One of the biggest challenges is guessing the correct capacity for the server. If the customer overestimates their needs, they may end up overpaying for an underutilized server. On the other hand, if the customer underestimates their needs, upgrading the server to meet their growing requirements can be slow and expensive.<br>

Despite these potential drawbacks, a dedicated server provides the customer with a guarantee of security, privacy, and full utilization of the underlying resources. This is especially important for customers who require a high degree of control over their data and processing resources, or who have strict security and privacy requirements.<br>

### Virtual Private Server (VPS)

A Virtual Private Server (VPS) is a hosting solution that allows multiple virtual machines (VMs) to run on a single physical server, which is shared by multiple customers. Each customer has access to a portion of the server's resources, including processing power, memory, and storage. This provides customers with a cost-effective alternative to dedicated servers, as they only pay for a fraction of the server's resources.<br>

he key technology behind VPS is a software layer known as a hypervisor. The hypervisor acts as an intermediary between the physical server and the VMs, allocating and managing the underlying resources to each virtual environment. This allows customers to run their own applications and operating systems on the VPS, as if it were a dedicated server.<br>

<p align="center">
  <img src="https://github.com/Manjil-sharma/Microsoft-Azure-Fundamentals/blob/main/Git%20hub/vms.PNG?raw=true"><br>
 
</p><br>

However, there are some trade-offs to consider when using a VPS. Just like with dedicated servers, customers must guess the correct capacity for their virtual environment, as overpaying for an underutilized virtual machine can be a waste of resources. Additionally, the guest operating system running on the VPS may impose limitations on the available resources, and multiple applications on a single virtual machine can result in conflicts in resource sharing, potentially leading to reduced performance and stability.<br>

Despite these potential drawbacks, VPS hosting is a popular choice for businesses and individuals who need more control over their hosting environment than what is available with shared hosting, but do not want to incur the costs associated with a dedicated server. <br>

### Containers

Containers are a lightweight and efficient way to run multiple applications on a single server. They are an alternative to virtual machines, and are often used in cloud-based applications and microservices architectures. With containers, multiple applications can run side by side, sharing the same underlying operating system (OS) and resources.<br>

The technology behind containers is Docker, a popular platform for building, shipping, and running applications. Docker uses a software layer called the Docker Daemon to manage and run multiple containers on a single server. The Docker Daemon is responsible for allocating resources to each container, ensuring that they are isolated from each other and can run independently.<br>

<p align="center">
  <img src="https://github.com/Manjil-sharma/Microsoft-Azure-Fundamentals/blob/main/Git%20hub/container.PNG?raw=true"><br>
 
</p><br>

Containers offer several advantages over virtual machines. First, they allow you to maximize the utilization of available capacity, making them more cost-effective. Secondly, because containers share the same underlying OS, they are more efficient than multiple virtual machines, as each container does not require its own OS.<br>

containers are a flexible and efficient way to run multiple applications on a single server. They offer the benefits of shared resources and isolation, making them a popular choice for cloud-based applications and microservices architectures. With Docker and the Docker Daemon, managing and running containers is easy and cost-effective, making it a popular choice for developers and system administrators alike.<br>


### Functions

Function as a Service (FaaS) is a type of cloud computing service that allows developers to run their code without the need to manage the underlying infrastructure. In this setup, managed virtual machines run managed containers and the user is only responsible for uploading a piece of code, choosing the amount of memory required, and specifying the duration. This setup, also known as Serverless Compute and  is highly cost-effective as the user only pays for the time the code is running and virtual machines only run when there is code to be executed. <br>

<p align="center">
  <img src="https://github.com/Manjil-sharma/Microsoft-Azure-Fundamentals/blob/main/Git%20hub/function.PNG?raw=true"><br>
 
</p><br>

FaaS offers several benefits over traditional cloud computing models. Firstly, it eliminates the need for managing and maintaining infrastructure, freeing up time and resources for developers to focus on building their applications. Secondly, it provides a more flexible and scalable solution, allowing developers to easily increase or decrease the amount of resources used based on the demands of the application. Additionally, FaaS eliminates the need for long-term commitments, as users only pay for the resources they actually use. Finally, it allows for easy integration with other cloud services and APIs, enabling the creation of complex and sophisticated applications.<br>

However, a side-effect of this setup is the occurrence of Cold Starts, which refers to the initial lag that occurs when a function is executed for the first time after a period of inactivity.<br>




## Day 11 of #Microsoft Azure Fundamentals
:large_blue_diamond: **Course**: **Microsoft Azure Fundamentals (AZ-900)** <br>

Today I learned abot the concept of Regions, Geography and Paired Regions in Azure.


### Region

In Microsoft Azure, a region is a geographical area that contains multiple datacenters. These regions are spread across different locations around the world and are designed to provide high availability and reliability for customers. Azure has 58 regions available across 140 countries.<br>

Each region is an isolated location that has its own network infrastructure, power, and cooling systems. By having multiple regions, customers can choose to store their data and run their applications in a location that meets their regulatory, compliance, or business requirements.<br>

### Geography

In Azure, a geography is a grouping of two or more regions within a geographic proximity, providing a higher level of redundancy and resiliency for your data. By creating resources in different regions within the same geography, you can ensure that your data is stored in separate physical locations, reducing the risk of data loss due to a disaster or a power outage.<br>

For example, Azure has several geographies, such as the United States, Europe, and Asia Pacific. Within each geography, there are multiple regions, such as "West US" or "North Europe." When you create a resource in a geography, your data will be automatically replicated within that geography to ensure high availability and durability.<br>

By choosing the right geography for your resources, you can ensure that your data is stored close to your users, reducing latency and improving performance, while also providing the necessary level of redundancy and resiliency.<br>

### Paired Regions

Paired regions are two regions within the same geography that are connected with low-latency, high-bandwidth links, providing a higher level of resilience for your data. In Azure, paired regions are used for disaster recovery and business continuity scenarios, allowing you to replicate your data and applications to another region in case of a disaster or an outage.<br>

For example, if you have an application running in the "West US" region, you can replicate the data to a paired region, such as "East US." In the event of a disaster or an outage in the "West US" region, you can quickly switch over to the paired region to ensure business continuity.<br>

Paired regions provide you with the flexibility to choose the right disaster recovery strategy for your organization, depending on your specific requirements and the criticality of your applications. With Azure paired regions, you can implement a disaster recovery plan that provides the right level of resilience and protection for your data, while also reducing downtime and maintaining high availability.<br>





## Day 12 of #Microsoft Azure Fundamentals
:large_blue_diamond: **Course**: **Microsoft Azure Fundamentals (AZ-900)** <br>

Today I learned about the types of Region and Service Availability.


### Recommended Region

Recommended regions refer to the regions that Microsoft recommends you use for deploying your resources based on factors such as performance, compliance, and availability. These regions are typically geographically closer to your end-users, and may have better performance for certain types of workloads.<br>

For example, if your users are located in the United States, you may want to choose a region in the United States, such as East US or West US. Similarly, if your users are in Europe, you may want to choose a region in Europe, such as West Europe or North Europe.<br>

Additionally, Microsoft may recommend certain regions for specific services or workloads. For example, for Azure Media Services, Microsoft recommends that you use a region that is close to your content origin to minimize data transfer costs and improve performance.<br>


### Alternate Region

Alternate regions in Azure refer to backup regions that you can use as a failover option in case your primary or recommended region is unavailable or experiencing issues. These alternate regions are typically located far away from your primary region to provide geographic redundancy.<br>

When configuring a geo-redundant deployment in Azure, you typically select an alternate region that is far enough away from your primary region to minimize the risk of both regions being affected by the same outage. For example, if your primary region is located in North America, you might choose an alternate region in Europe or Asia.<br>

It's important to note that failover to an alternate region typically incurs additional costs, and there may be some downtime during the failover process. It's important to design and test your failover strategy in advance to ensure that you can quickly and efficiently recover in the event of an outage.<br>

### General Availability

General availability (GA) refers to a stage in the release process of an Azure service or feature where it is considered to be production-ready and available for general use by customers. When a service or feature reaches GA, it means that Microsoft has completed development and testing, and has made it available for commercial use with a Service Level Agreement (SLA).<br>

Before reaching GA, Azure services and features go through a series of stages, including private preview, public preview, and sometimes, a limited availability release to a subset of customers. During these stages, Microsoft gathers feedback and makes necessary improvements to the service or feature. Once the service or feature is stable, meets all the requirements, and has been tested thoroughly, it is released to GA.<br>

When a service or feature is generally available, customers can use it in production environments with confidence, knowing that it has been thoroughly tested and meets Microsoft's quality standards. Additionally, Microsoft provides support for GA services and features, and customers can rely on a defined SLA for service availability and performance.<br>

### Service categories across region types

Azure services are grouped into three categories: foundational, mainstream, and strategic. Azure's general policy on deploying services into any given region is primarily driven by region type, service categories, and customer demand.<br>


- Foundational: Available in all recommended and alternate regions when the region is generally available, or within 90 days of a new foundational service becoming generally available.<br>

- Mainstream: Available in all recommended regions within 90 days of the region general availability. Demand-driven in alternate regions, and many are already deployed into a large subset of alternate regions.<br>

- Strategic (previously Specialized): Targeted service offerings, often industry-focused or backed by customized hardware. Demand-driven availability across regions, and many are already deployed into a large subset of recommended regions.<br>








## Day 13 of #Microsoft Azure Fundamentals
:large_blue_diamond: **Course**: **Microsoft Azure Fundamentals (AZ-900)** <br>

Today I learned about the Availability Zones and it's imoprtance on data recover.


### Availability Zones
Availability Zones in Azure are a feature that allows customers to deploy their applications and services in geographically separate data centers within an Azure region. Each availability zone is a physically separate data center with independent power, cooling, and networking, which are connected through high-speed, private fiber optic networks.<br>

By deploying resources across multiple availability zones, customers can protect their applications and services against data center-level failures, such as power outages or network disruptions. Additionally, deploying resources across availability zones can also improve application performance by reducing network latency between different components of the application that are distributed across different availability zones.<br>

The number of Availability Zones (AZs) in an Azure region can vary, but typically an Azure region has at least three Availability Zones. As of February 2023, there are over 60 Azure regions globally, and most of these regions have three or more Availability Zones. For example, the East US region has three Availability Zones, while the West Europe region has four Availability Zones.<br>

However, some Azure regions have fewer than three Availability Zones. For example, the South Central US region currently has only two Availability Zones. Additionally, some special regions or specialized services may have different numbers of Availability Zones depending on their requirements.<br>


## Day 14 of #Microsoft Azure Fundamentals
:large_blue_diamond: **Course**: **Microsoft Azure Fundamentals (AZ-900)** <br>

Today I learned about fault domains and update domains, which are used to ensure high availability and resilience of applications. We also discussed the use of availability sets to group virtual machines across fault and update domains to minimize the impact of localized disruptions.<br>

### Fault Domain:
In Azure, a fault domain is a logical group of underlying hardware resources (such as servers, network switches, and power sources) that share a common physical location, power, and cooling infrastructure. The purpose of creating fault domains is to ensure high availability and resilience of applications and services by minimizing the impact of hardware failures, maintenance events, or other localized disruptions.<br>

Each fault domain represents a separate failure zone, which means that if a hardware component fails in one fault domain, it should not affect the availability of resources in other fault domains. Azure uses fault domains to ensure that virtual machines (VMs) and other resources are spread across different fault domains, so that they can continue to operate even if there is a localized outage or failure.<br>

For example, when you create an availability set in Azure, you can specify the number of fault domains you want to use (usually two or three) and assign your VMs to those fault domains. This ensures that your VMs are running on different physical hardware within the same data center, which reduces the risk of downtime due to hardware failures, maintenance events, or other localized disruptions.<br>

### Update Domain

Update domains in Azure are logical groups of underlying hardware resources, such as servers and network switches, that can be updated or rebooted together during planned maintenance events. They are used to minimize the impact of maintenance events on running workloads and ensure high availability and resilience of applications and services.<br>

When you create an availability set in Azure, you can specify the number of update domains you want to use (usually two or three). When you deploy virtual machines (VMs) in the availability set, Azure automatically distributes them across the update domains to ensure that not all the VMs are updated or rebooted at the same time during maintenance events. This helps to minimize downtime and ensure that the workloads remain available and responsive to users.<br>


### Availability Set

Availability set is a logical grouping of two or more virtual machines (VMs) that are deployed across different fault domains and update domains. The purpose of creating an availability set is to ensure high availability and resilience of applications and services by minimizing the impact of localized hardware failures, maintenance events, or other disruptions.<br>

When you create an availability set, Azure distributes your VMs across multiple fault domains and update domains within a single data center. This means that if there is a hardware failure, network outage, or planned maintenance event in one fault domain or update domain, the other fault domain or update domain can still keep the virtual machines and applications running.<br>



<p align="center">
  <img src="https://github.com/Manjil-sharma/Microsoft-Azure-Fundamentals/blob/main/Git%20hub/av%20set.PNG?raw=true"><br>
 <em> Each VM in an availability Set is assigned a Fault Domain and Update Domain.</em>
</p><br>

To be included in an availability set, virtual machines must be in the same virtual network and same region. They can be running any supported operating system and can be of any size or series. When you create an availability set, Azure automatically assigns update domains and fault domains to your VMs.<br>




## Day 15 of #Microsoft Azure Fundamentals
:large_blue_diamond: **Course**: **Microsoft Azure Fundamentals (AZ-900)** <br>

Today I learned about Azure's Computing Services.<br>
      
### Azure Virtual Machines

Azure Virtual Machines is a core computing service offered by Microsoft Azure. It allows you to deploy and run virtual machines in the cloud, which can be used to run a wide range of applications and services. You can choose between Windows and Linux virtual machines, and you have the flexibility to choose your desired operating system, memory, CPU, and storage configurations. These virtual machines run on shared hardware with other customers, which allows for efficient use of resources and cost savings. With Azure Virtual Machines, you can easily scale up or down as needed and pay only for what you use.<br>


### Azure Container Instance

Azure Container Instances (ACI) is a computing service provided by Microsoft Azure that enables you to run containers on the Azure cloud platform, without the need to manage virtual machines or orchestration tools. With ACI, you can quickly and easily run containerized applications in the cloud, and pay only for the exact amount of resources that you consume.<br>

In addition to ACI, Azure also provides Docker as a Service (DaaS), which is built on top of ACI and allows you to run Docker containers in the cloud without having to manage servers or VMs. DaaS provides a fully managed and scalable environment for running Dockerized applications, and is designed for developers and IT teams who want to focus on building and deploying their applications, rather than managing infrastructure.<br>


### Azure Kubernetes Services

Azure Kubernetes Service (AKS) is a managed Kubernetes service provided by Microsoft Azure that makes it easy to deploy, manage, and scale containerized applications in the cloud.<br>

AKS allows you to run and manage containerized applications using the open-source Kubernetes (K8s) software, which provides a powerful and flexible platform for deploying and managing containerized applications. With AKS, you can easily deploy and manage Kubernetes clusters, and take advantage of built-in features such as automatic scaling, rolling updates, and self-healing.<br>

AKS provides a fully managed environment for running Kubernetes clusters, which means that you don't have to worry about managing the underlying infrastructure. This makes it easy to focus on building and deploying your applications, rather than managing the infrastructure.<br>





## Day 16 of #Microsoft Azure Fundamentals
:large_blue_diamond: **Course**: **Microsoft Azure Fundamentals (AZ-900)** <br>

Today I continued to learn about Azure's Computing Services.<br>


### Azure Service fabric

 It is a Tier-1 Enterprise Containers as a Service is a distributed systems platform that can run in both Azure and on-premises environments. It provides a comprehensive platform for managing and deploying microservices-based applications in a scalable and reliable way.<br>

Tier-1 Enterprise CaaS makes it easy to package, deploy, and manage microservices-based applications, providing developers with a set of tools and APIs to simplify the development process. It supports both stateful and stateless microservices and provides built-in support for automatic scaling, load balancing, and fault tolerance.<br>

Some of the key features of Tier-1 Enterprise CaaS include:

- Distributed architecture: Tier-1: Enterprise CaaS uses a distributed architecture to ensure high availability and fault tolerance for microservices-based applications.<br>

- Seamless integration: Tier-1: Enterprise CaaS integrates seamlessly.<br>

## Azure Functions

Azure Functions is a serverless computing service provided by Microsoft Azure that allows developers to run code on-demand without having to provision and manage the underlying infrastructure. With Azure Functions, developers can write and deploy small pieces of code, called functions, that are triggered by events such as HTTP requests, timer schedules, and message queue updates.<br>

Azure Functions supports a variety of programming languages, including C#, JavaScript, Python, and Java, and provides pre-built templates and integrations with other Azure services to simplify development. Functions can be deployed and scaled independently, allowing developers to focus on building and deploying specific functions as needed.<br>

## Azure Batch

Azure Batch is a service provided by Microsoft Azure that enables developers and IT professionals to run large-scale batch computing jobs in the cloud. With Azure Batch, users can easily schedule, run, and manage large-scale parallel and high-performance computing (HPC) workloads, such as simulations, data processing, rendering, and machine learning tasks.<br>

Azure Batch provides a simple interface for users to submit jobs and manage compute resources, and it automatically scales the compute resources up or down as needed to meet the demand of the workload. Users can also choose to use pre-configured VMs or bring their own VM images to customize the computing environment to their specific needs.<br>


## Day 17 of #Microsoft Azure Fundamentals
:large_blue_diamond: **Course**: **Microsoft Azure Fundamentals (AZ-900)** <br>

Today I learned about Azure Storage Services.<br>

### Azure Blob Storage 

Azure Blob Storage is a cloud-based storage service provided by Microsoft Azure that enables you to store and manage massive amounts of unstructured data. Unstructured data can include text or binary data, such as documents, images, videos, and audio files.<br>

Additionally, Azure Blob Storage provides three different access tiers - Hot, Cool, and Archive - each optimized for storing data with different access patterns and latency requirements.<br>

The Hot access tier is optimized for storing frequently accessed data, providing high-performance access to data at a slightly higher cost than the other tiers. The Cool access tier is optimized for infrequently accessed data that needs to be stored for at least 30 days, offering lower storage costs than the Hot tier. The Archive access tier is optimized for rarely accessed data that needs to be stored for at least 180 days, providing the lowest storage costs but with higher access latency, typically on the order of hours.<br>

Overall, Azure Blob Storage is a highly scalable and cost-effective storage solution for storing and managing large amounts of unstructured data, with flexible access tiers that enable you to optimize storage costs based on your data access patterns.<br>


### Azure Disk Storage

Azure Disk Storage is a cloud-based storage service provided by Microsoft Azure that enables you to create and manage virtual disks for your Azure virtual machines (VMs). Azure Disk Storage provides highly available and durable block-level storage that can be used for operating system disks, data disks, and temporary disks.<br>

Azure Disk Storage offers two types of disks: managed disks and unmanaged disks. Managed disks are the recommended and easier-to-use option, where Azure automatically manages disk storage for you. Unmanaged disks provide more control and flexibility but require manual management of disk storage.<br>

Azure Disk Storage integrates seamlessly with Azure virtual machines, enabling you to create and manage disks directly from the Azure portal, Azure CLI, Azure PowerShell, and various Azure SDKs and APIs. Azure Disk Storage also provides various features, such as disk encryption, disk snapshots, and disk replication, which can help you secure and manage your data more effectively.<br>

### Azure File Storage

Azure File Storage is a cloud-based file sharing service provided by Microsoft Azure that enables you to create file shares in the cloud and access them from anywhere over the internet. Azure File Storage provides a fully managed file sharing solution that can be used to store and share files with multiple users and applications.<br>

Azure File Storage uses the Server Message Block (SMB) protocol, which allows you to mount file shares from anywhere on your network, as if they were local file shares. This makes it easy to migrate on-premises file shares to the cloud and to integrate Azure File Storage with your existing applications and workflows.<br>


## Day 18 of #Microsoft Azure Fundamentals
:large_blue_diamond: **Course**: **Microsoft Azure Fundamentals (AZ-900)** <br>

Today I continued learning about Azure Storage Services.<br>


### Azure Queue Storage

Azure Queue storage is a messaging service provided by Microsoft Azure that allows applications to asynchronously communicate by sending and receiving messages between components or services.<br>

The messages are stored in queues, which are a type of storage that supports a first-in-first-out (FIFO) model. This means that the first message that is added to the queue will be the first message to be retrieved from the queue.<br>

Azure Queue storage is often used for scenarios where you want to ensure that messages are processed in order, such as when processing financial transactions or when performing batch processing of data. It can also be used to enable asynchronous processing of workloads, where the processing of messages can be done at a later time or by a different component or service.<br>

### Azure Table Storage

Azure Table Storage is a NoSQL key-value store provided by Microsoft Azure. It is a service that allows you to store and query large amounts of structured data in the cloud.<br>

With Azure Table Storage, you can store structured data such as JSON documents, entities with properties and values, or even binary data. It provides a key-value store where data is organized into tables, and each row in a table represents an entity.<br>

Azure Table Storage is often used for scenarios where you need to store and retrieve large amounts of structured data, such as for storing customer data, sensor data, or any other type of data that needs to be queried and processed quickly.<br>

  
  
### Azure Data Box
  
Azure Data Box is a family of physical devices provided by Microsoft Azure that enable secure, fast, and reliable transfer of large amounts of data between on-premises infrastructure and the cloud.<br>
  
Azure Data Box devices come in different form factors, including the original Data Box, the Data Box Disk, and the Data Box Heavy, each with varying capacities and performance levels. These devices are designed to simplify the process of transferring large amounts of data to Azure, which can be challenging when using traditional methods such as over-the-wire transfers.<br>
  
Azure Data Box is often used for scenarios where you need to transfer large amounts of data to Azure, such as for migration or backup purposes. It is also used for scenarios where the network connectivity is limited or the cost of transferring data over the network is high.<br>
  

## Day 19 of #Microsoft Azure Fundamentals
:large_blue_diamond: **Course**: **Microsoft Azure Fundamentals (AZ-900)** <br>


Today I continued on Azure Storage Serviecs.

### Azure Archive Storage

Azure Archive Storage is a storage solution offered by Microsoft Azure that provides customers with a low-cost, highly durable, and secure cloud-based archival storage service. It is designed for long-term data retention, with data access times of hours to days.<br>

Azure Archive Storage offers a highly cost-effective storage solution for data that is rarely accessed, but needs to be retained for a long period of time, such as backups, archives, and regulatory compliance data. With Azure Archive Storage, customers can store large amounts of data with predictable costs, making it an ideal choice for organizations that need to store large amounts of data for compliance or regulatory purposes.<br>

The storage is based on the same platform as other Azure storage services, and is accessible through the same APIs and management tools. The data is stored on low-cost, high-density media and can be accessed using the REST APIs, Azure portal, or various Azure storage tools.<br>
  
One thing to note is that accessing data stored in Azure Archive Storage can take several hours to retrieve, so it's important to ensure that the data you store in this type of storage is data that you don't need to access frequently. Additionally, there may be additional costs associated with retrieving data from Azure Archive Storage, so it's important to understand the pricing model before using this storage solution.<br>


### Azure Data Lake Storage

Azure Data Lake Storage (ADLS) is a cloud-based storage solution provided by Microsoft Azure. ADLS is designed to provide a scalable and secure platform for storing and analyzing large amounts of data. ADLS supports both structured and unstructured data, and provides a range of features for data processing and analysis, such as built-in analytics, batch and real-time processing, and machine learning.<br>

ADLS is built on top of the Azure Blob Storage service, and provides an additional layer of functionality specifically for big data scenarios. This includes the ability to store and process large data sets, as well as support for popular big data processing frameworks such as Hadoop, Spark, and Hive. ADLS also provides features for managing and securing data, such as data encryption, role-based access control, and auditing.<br>


  There are two tiers of ADLS available:
  
- ADLS Gen1: This is the original version of ADLS and is optimized for batch processing workloads. It provides a hierarchical namespace and supports data stored in either file or object formats.<br>

- ADLS Gen2: This is the newer version of ADLS and is designed for both batch and real-time processing workloads. It provides a unified namespace and supports data stored in object format only. ADLS Gen2 also provides a number of additional features, such as support for Azure Blob Storage features, hierarchical access control, and a built-in analytics service called Azure Data Lake Analytics.<br>


## Day 20 of #Microsoft Azure Fundamentals
:large_blue_diamond: **Course**: **Microsoft Azure Fundamentals (AZ-900)** <br>

Today I learned about Azure's Database Services.

### Azure Cosmos DB

Azure Cosmos DB is a globally distributed, multi-model database service provided by Microsoft as part of the Azure cloud platform. It is designed to provide high scalability, low latency, and global distribution of data.<br>

Azure Cosmos DB supports various data models, including document, key-value, graph, and column-family. It also provides multiple APIs, such as SQL, MongoDB, Cassandra, Gremlin, and Azure Table, allowing developers to access and manipulate data in their preferred programming language.<br>

Cosmos DB is designed for high performance and low latency, with data replication across multiple Azure regions and automatic failover in the event of a region-wide outage. It also provides features like configurable consistency levels, which allow developers to trade off between strong consistency and high availability, depending on their application requirements.<br>
  
### Azure SQL Database
  
Azure SQL Database is a fully managed relational database service provided by Microsoft on its Azure cloud computing platform. It is based on Microsoft SQL Server, and provides a range of features for managing, storing, and querying relational data in the cloud.<br>
  
Azure SQL Database is designed to be highly scalable and available, with built-in high availability and disaster recovery features. It can be used for a wide range of database workloads, from small single-database applications to large, complex enterprise applications. The service supports the full range of SQL Server features, including Transact-SQL, stored procedures, and triggers.<br>
  
Azure SQL Database offers several pricing tiers, each with different levels of performance, features, and storage capacity. It also offers the ability to scale up or down based on application needs, allowing developers to dynamically adjust the resources allocated to their databases as demand changes.<br>
  
  
### Azure Database For MYSQL/PSQL/Maria DB
  
Azure Database for MySQL, PostgreSQL, and MariaDB are fully managed relational database services provided by Microsoft on its Azure cloud computing platform. Each service is based on the respective open source database management system and provides a range of features for managing, storing, and querying relational data in the cloud.<br>
  
Like Azure SQL Database, each of these services is designed to be highly scalable and available, with built-in high availability and disaster recovery features. They can be used for a wide range of database workloads, from small single-database applications to large, complex enterprise applications.<br>
  
Azure Database for MySQL, PostgreSQL, and MariaDB also provide built-in security features such as data encryption, firewall protection, and advanced threat protection. They offer several pricing tiers, each with different levels of performance, features, and storage capacity. They also offer the ability to scale up or down based on application needs, allowing developers to dynamically adjust the resources allocated to their databases as demand changes.<br>
  
  

 ## Day 21 of #Microsoft Azure Fundamentals
:large_blue_diamond: **Course**: **Microsoft Azure Fundamentals (AZ-900)** <br>


Today I continued my learning on Azure's Database Services.<br>

### SQL Server on VMs

Azure SQL Server on VMs (Virtual Machines) is a database service offered by Microsoft Azure that enables users to create and manage SQL Server instances on Azure virtual machines. With this service, users can run SQL Server workloads on VMs with the same capabilities and features of an on-premises SQL Server deployment.<br>

Azure SQL Server on VMs provides users with more control over the SQL Server instance, including the choice of operating system, virtual machine size, and storage configuration. This service also provides support for features such as high availability, backup and restore, and performance optimization.<br>

However, it is worth noting that Azure SQL Server on VMs requires more management and maintenance than other Azure database services, such as Azure SQL Database or Azure Database for PostgreSQL. Users are responsible for patching and maintaining the underlying operating system and SQL Server instances. This may require more technical expertise and resources than other database services.<br>

### Azure Synapse Analytics (Azure SQL Data Warehouse)

Azure Synapse Analytics is a cloud-based analytics service. It is designed to help organizations analyze large amounts of data, derive insights from it, and take informed actions based on those insights. Azure Synapse Analytics integrates big data and data warehousing technologies into a single platform, making it easier for organizations to process and analyze large volumes of data from a variety of sources.<br>

One of the key benefits of Azure Synapse Analytics is its ability to provide a unified experience for data preparation, management, and analysis. It allows users to easily integrate data from a variety of sources, including structured and unstructured data, and provides tools for data preparation, data transformation, and data modeling.<br>

Azure Synapse Analytics also provides advanced analytics capabilities, such as machine learning, AI, and cognitive services. This enables users to derive insights from their data and make predictions based on that data.<br>


### Azure Database Migration Service

Azure Database Migration Service is a fully managed service offered by Microsoft Azure that enables organizations to migrate their databases to Azure with minimal downtime and risk. It provides a streamlined and automated process for migrating on-premises databases to Azure, as well as for migrating between Azure-based databases.<br>

One of the key benefits of the Azure Database Migration Service is its ability to perform online migrations with minimal downtime. It uses techniques such as log shipping and transactional replication to keep the source database synchronized with the target database during the migration process, which minimizes the amount of downtime required.<br>

The Azure Database Migration Service supports a wide range of database platforms, including SQL Server, MySQL, PostgreSQL, Oracle, and MongoDB. It also supports migration to Azure database services such as Azure SQL Database, Azure Database for MySQL, Azure Database for PostgreSQL, and Azure Cosmos DB.<br>



  ## Day 22 of #Microsoft Azure Fundamentals
:large_blue_diamond: **Course**: **Microsoft Azure Fundamentals (AZ-900)** <br>

Today I continued my learning on Azure's Database Services.<br>

### Azure Cache For Redis

Azure Cache for Redis is a fully managed, in-memory data store that is based on the open-source Redis cache. It provides high-performance data caching and access to improve the performance and scalability of web applications and services. Azure Cache for Redis can be used as a standalone cache or as a distributed cache with multiple nodes, and it supports a wide range of data types and caching scenarios. It also includes features such as data persistence, clustering, and high availability to ensure reliability and data consistency.<br>

It provides several important benefits for developers and organizations, including:<br>

- High performance: Azure Cache for Redis provides fast data access and processing, which can significantly improve application performance and reduce latency.<br>

- Scalability: The service can be easily scaled up or down to meet changing demand, without requiring significant changes to the underlying infrastructure.<br>

- Data consistency: Azure Cache for Redis provides several features that ensure data consistency, including data replication and automatic failover.<br>

- Reduced data access costs: By storing frequently accessed data in memory, Azure Cache for Redis can significantly reduce data access costs and improve overall application performance.<br>

- Easy integration: The service is fully compatible with Redis, which means that existing Redis-based applications can be easily migrated to Azure Cache for Redis with minimal modifications.<br>



### Azure Table Storage

Azure Table Storage is a NoSQL cloud-based data storage service provided by Microsoft Azure. It allows developers to store structured, non-relational data at scale in the cloud, and provides features that enable easy access to the stored data.<br>

Azure Table Storage is a schema-less storage service, meaning that it does not require a predefined schema to store data. Developers can store data with varying structures, and can add or remove attributes to the data on the fly.<br>

The service stores data in tables, which are similar to database tables in a traditional relational database system. Each table consists of a set of entities, which are individual items that can be queried, added, updated, or deleted. Entities are identified by a primary key, which can consist of up to four attributes.<br>



## Day 23 of #Microsoft Azure Fundamentals
:large_blue_diamond: **Course**: **Microsoft Azure Fundamentals (AZ-900)** <br>

Today I started to learn about Application Integration Services.

### Application Integration Services

Azure Application Integration Services is a collection of services offered by Microsoft Azure that enables businesses to connect different applications, data sources, and services within the cloud and on-premises environments. These services facilitate seamless data flow and communication between disparate systems, allowing businesses to streamline their operations and improve their overall efficiency.<br>

Some of the key services offered by Azure Application Integration Services include:<br>

### Azure Notification Hub

Azure Notification Hubs is a scalable mobile push notification engine for sending personalized push notifications to mobile devices and web applications. It is a fully managed, multi-platform, and highly available service provided by Microsoft Azure that simplifies the process of sending push notifications across different platforms, including iOS, Android, Windows, and Amazon devices, as well as web browsers.<br>

With Azure Notification Hubs, developers can easily send push notifications to millions of devices with just a few lines of code, without worrying about the underlying infrastructure. It provides a single platform for sending push notifications, which helps reduce the complexity of managing different platforms and devices.<br>

### Azure API Apps

Azure API Apps is a service provided by Microsoft Azure that enables developers to create, host, and consume APIs in the cloud. It is a fully managed, scalable, and secure platform that simplifies the process of building and deploying APIs, allowing developers to focus on creating great applications instead of managing infrastructure.<br>

Azure API Apps supports a wide range of programming languages and frameworks, including .NET, Java, Node.js, PHP, and Python, making it easy to develop APIs using the tools and languages that you are most familiar with.<br>



## Day 24 of #Microsoft Azure Fundamentals
:large_blue_diamond: **Course**: **Microsoft Azure Fundamentals (AZ-900)** <br>

Today I continued my learnings on Azure's Application Integration Services.

### Azure Service BUS
Azure Service Bus is a cloud-based messaging service that enables reliable communication between applications and services. It allows developers to build distributed systems that can communicate with each other regardless of the underlying platform or programming language.<br>

Azure Service Bus provides features such as message queuing, publish/subscribe messaging, and session-based messaging. It allows messages to be sent between different applications or services asynchronously, providing a decoupled architecture that can improve the scalability, reliability, and flexibility of an application.<br>

Azure Service Bus also provides enterprise-level features such as message batching, dead-lettering, and message expiration, making it a suitable choice for high-volume, mission-critical applications.<br>

### Azure Stream Analytics

Azure Stream Analytics is a cloud-based real-time data analytics service provided by Microsoft Azure. It enables developers to analyze and process large volumes of streaming data from a wide range of sources in real-time, such as IoT devices, social media, and sensors.<br>

Azure Stream Analytics allows developers to build complex data processing pipelines using a simple SQL-like language. It provides features such as windowing, filtering, aggregation, and transformation of data streams. These features can be used to extract insights, detect anomalies, and trigger alerts in real-time.<br>

Azure Stream Analytics supports integration with a variety of data sources and destinations, including Azure Event Hubs, Azure Blob Storage, Azure Data Lake Storage, and Azure SQL Database. It also provides built-in support for machine learning models and other advanced analytics capabilities, enabling developers to build intelligent applications that can adapt and learn from real-time data.<br>


## Day 25 of #Microsoft Azure Fundamentals
:large_blue_diamond: **Course**: **Microsoft Azure Fundamentals (AZ-900)** <br>

Today I continued my learnings on Azure's Application Integration Services.

### Azure Logic Apps

Azure Logic Apps are a cloud-based service that allows you to design and build workflows that integrate with various Azure and non-Azure services. They are designed to help businesses automate repetitive tasks and simplify complex business processes. Logic Apps use a visual designer that allows you to create workflows visually, without the need for coding.<br>

Logic Apps allow you to create workflows that can be triggered by events or schedules, and they can perform a wide range of tasks, such as sending emails, creating calendar events, updating databases, and more. You can use Logic Apps to integrate with a variety of services, such as Office 365, Salesforce, Dynamics 365, and other third-party applications.<br>

### Azure API Management

Azure API Management is a cloud-based service provided by Microsoft Azure that allows organizations to create, manage, secure, and publish APIs (Application Programming Interfaces) for internal and external consumption. APIs are a set of protocols, routines, and tools for building software applications, and API management is the process of designing, publishing, documenting, and analyzing APIs.<br>

With Azure API Management, you can:<br>

- Publish and manage APIs: You can publish your APIs with Azure API Management to make them available for internal or external consumption. You can also manage access to your APIs by setting up security policies, rate limits, and quotas.<br>

- Monitor and analyze API usage: Azure API Management provides detailed analytics and metrics to help you monitor and analyze API usage. You can use these insights to optimize your APIs and improve their performance.<br>

- Scale APIs: You can scale your APIs up or down based on demand. Azure API Management provides auto-scaling capabilities that can automatically adjust the capacity of your APIs based on usage.<br>

- Developer portal: Azure API Management also includes a developer portal where developers can discover, learn, and consume your APIs. The developer portal provides comprehensive API documentation, sample code, and interactive testing tools.<br>


## Day 26 of #Microsoft Azure Fundamentals
:large_blue_diamond: **Course**: **Microsoft Azure Fundamentals (AZ-900)** <br>


Today I continued my learnings on Azure's Application Integration Services and started learning about Developer and Mobile Tools.<br>

### Azure Queue Storage


Azure Queue Storage is a message queuing service provided by Microsoft Azure that enables you to store and process large numbers of messages that can be accessed by multiple clients. It is a scalable and cost-effective solution for asynchronous messaging between applications and services, and is often used in scenarios where you need to decouple your application components or scale them independently.<br>

In Azure Queue Storage, messages are stored in a queue and processed by one or more consumers. The messages can be up to 64 KB in size and can contain any type of data. The queue itself can hold an unlimited number of messages, and messages are automatically deleted from the queue once they are processed.<br>

## Developer and Mobile Tools

### Azure Single IR Service

Azure SignalR Service is a fully-managed cloud service provided by Microsoft Azure that simplifies the process of adding real-time functionality to web applications. It provides an easy way to integrate real-time web features such as instant messaging, push notifications, and live updates into your web applications.<br>

Azure SignalR Service uses the SignalR library, which is an open-source library for adding real-time web functionality to applications. It allows you to broadcast messages to multiple clients simultaneously, without the need for the clients to constantly poll the server for updates.<br>

With Azure SignalR Service, you can easily scale your real-time web applications by automatically provisioning and managing the infrastructure required to handle high volumes of traffic. This service provides automatic scaling and load balancing to ensure that your applications are always responsive and available.<br>





## Day 27 of #Microsoft Azure Fundamentals
:large_blue_diamond: **Course**: **Microsoft Azure Fundamentals (AZ-900)** <br>


Today I continued learning on Azure's Developer and Mobile Tools.<br>

### Azure App Service

Azure App Service is a fully managed Platform as a Service (PaaS) that enables developers to quickly build, deploy, and scale web and mobile applications. It supports multiple programming languages and frameworks, including .NET, Java, Node.js, PHP, Python, and Ruby.<br>

With Azure App Service, developers can easily deploy web and mobile applications to the cloud, without worrying about the underlying infrastructure, operating system, or runtime. It also provides built-in DevOps capabilities, including continuous deployment, automated builds, and integration with popular source control systems like GitHub and Azure DevOps.<br>

Azure App Service offers various pricing tiers and scaling options to meet the needs of different types of applications and workloads. It also provides integration with other Azure services, including Azure Active Directory, Azure SQL Database, Azure Cosmos DB, and Azure Functions, to name a few.<br>

### Visual studio

Azure Visual Studio is a set of tools and services provided by Microsoft Azure to enable developers to build and deploy applications in the cloud using Visual Studio IDE. With Azure Visual Studio, developers can leverage the powerful development features of Visual Studio to create, test, and deploy cloud-based applications seamlessly.<br>

Azure Visual Studio provides a rich set of features, including:<br>

- Integration with Azure DevOps - This enables developers to automate their software delivery pipeline from code commit to deployment using a single, integrated workflow.<br>

- Azure Resource Manager - This allows developers to define and deploy infrastructure resources for their applications using JSON templates.<br>

- Azure App Service - This provides a fully-managed PaaS offering for deploying and running web, mobile, and API applications in the cloud.<br>

- Azure SQL Database - This provides a fully-managed relational database service that allows developers to store and manage application data in the cloud.<br>

- Azure Functions - This provides a serverless computing service that allows developers to run event-driven, serverless applications in the cloud.<br>

- Azure Storage - This provides a scalable and secure cloud storage solution for storing and managing application data, including files, blobs, and queues.<br>
  



## Day 28 of #Microsoft Azure Fundamentals
:large_blue_diamond: **Course**: **Microsoft Azure Fundamentals (AZ-900)** <br>

I continued my learning journey on Azure Developer and Mobile Tools and started learning about Azure Devops Services.

### Xamarin

Xamarin is an open-source platform for building modern and performant applications for iOS, Android, and Windows with .NET. Xamarin is an abstraction layer that manages communication of shared code with underlying platform code. Xamarin runs in a managed environment that provides conveniences such as memory allocation and garbage collection.<br>

Xamarin enables developers to share an average of 90% of their application across platforms. This pattern allows developers to write all of their business logic in a single language (or reuse existing application code) but achieve native performance, look, and feel on each platform.<br>

Xamarin applications can be written on PC or Mac and compile into native application packages, such as an .apk file on Android, or an .ipa file on iOS.<br>


## Azure DevOps Services

Azure DevOps Services is a cloud-based platform that provides a set of tools and services for software development teams to plan, build, test, and deploy software. It includes features such as version control, continuous integration and delivery, project management, and collaboration tools to help teams work together efficiently and deliver high-quality software faster.<br>

### Azure Devops

Azure DevOps is a comprehensive platform that encompasses a range of DevOps services provided by Microsoft. These services include Azure Boards for project management, Azure Repos for version control, Azure Pipelines for continuous integration and delivery, Azure Test Plans for testing, and Azure Artifacts for package management.<br>

By providing a complete set of DevOps services, Azure DevOps enables software development teams to streamline their workflows, collaborate more effectively, and deliver high-quality software faster. Azure DevOps services are integrated with each other, making it easy for developers to manage the entire software development lifecycle from a single platform.<br>




## Day 29 of #Microsoft Azure Fundamentals
:large_blue_diamond: **Course**: **Microsoft Azure Fundamentals (AZ-900)** <br>


Today I continued my journey on Azure DevOps Services.

### Azure Boards

Azure Boards is a project management and work tracking tool provided by Microsoft Azure. It is used to manage work items such as features, bugs, and tasks across an entire software development project.<br>

- Features: Azure Boards offers a wide range of features such as customizable dashboards, backlog management, agile tools, sprint planning, and reporting.<br>

- Integration: Azure Boards integrates seamlessly with other Azure services such as Azure Repos, Azure Test Plans, and Azure DevOps Services. It also integrates with popular third-party tools such as GitHub, Jenkins, and Slack.<br>

- Collaboration: Azure Boards enables collaboration among team members by providing real-time updates, notifications, and discussions. It also allows stakeholders to track progress and provide feedback.<br>

- Customization: Azure Boards can be customized to fit the unique needs of any project. Users can create custom work item types, workflows, and fields.<br>

- Importance: Azure Boards is important because it provides a centralized platform for managing work items and tracking project progress. It helps teams stay organized, collaborate effectively, and deliver high-quality software products on time and within budget.<br>


### Azure Pipelines


Azure Pipelines is a cloud-based continuous integration and continuous delivery (CI/CD) service provided by Microsoft Azure. It is used to build, test, and deploy software applications to various platforms including Windows, Linux, and macOS. Here's some information about Azure Pipelines:<br>

- Usage: Azure Pipelines is used to automate the build and release processes for software applications. It allows developers to create pipelines that automatically build and test code changes, and deploy them to different environments such as production, staging, and development.<br>

- How it works: Azure Pipelines uses a YAML-based syntax to define the steps required to build, test, and deploy an application. The pipeline can be triggered by changes to the source code, or manually triggered by a developer. Once triggered, the pipeline executes the defined steps and provides detailed feedback on the results.<br>

- Benefits: Azure Pipelines offers several benefits including faster release cycles, improved quality of code, increased reliability, and reduced manual effort. It also supports multiple languages and platforms, making it easy for developers to integrate it into their existing workflows.<br>

- Integration: Azure Pipelines integrates seamlessly with other Azure services such as Azure Repos, Azure Artifacts, and Azure Test Plans. It also supports integration with third-party tools such as GitHub, Bitbucket, and Jira.<br>

- Pricing: Azure Pipelines offers a flexible pricing model with a free tier for open-source projects and a pay-as-you-go model for private projects.<br>





## Day 30 of #Microsoft Azure Fundamentals
:large_blue_diamond: **Course**: **Microsoft Azure Fundamentals (AZ-900)** <br>


I continued learning about Azure DevOps Services.


### Azure Repos

Azure Repos is a version control system (VCS) developed by Microsoft as part of the Azure DevOps suite of tools. It allows users to manage and store their source code and related artifacts, such as documentation and testing scripts, in a centralized repository.<br>

Azure Repos supports both centralized and distributed version control models, which means that users can choose to use either a traditional centralized model or a more modern distributed model depending on their needs.<br>

Azure Repos is commonly used by software development teams to collaborate on code, manage changes, and track project progress. It provides features such as branching and merging, code reviews, and pull requests, which help ensure code quality and improve team collaboration.<br>


### Azure Test Plans

Azure Test Plans is a testing solution provided by Microsoft as part of the Azure DevOps suite of tools. It is used by software development teams to plan, manage, and execute tests, as well as track and report on test results.<br>

Azure Test Plans provides a centralized repository for test cases and test suites and allows teams to collaborate on test planning and execution. It supports both manual and automated testing and integrates with popular testing frameworks like Selenium, Appium, and Visual Studio Test.<br>


Azure Test Plans is used by software development teams to:<br>

1.Plan and manage test cases and test suites<br>
2.Assign test cases to specific team members or iterations<br>
3.Execute tests manually or automatically<br>
4.Track and report on test results<br>
5.Analyze code coverage and quality metrics<br>
6.Integrate testing into the software development process<br>
7.Improve the quality of software products by ensuring that all components are thoroughly tested.<br>




## Day 31 of #Microsoft Azure Fundamentals
:large_blue_diamond: **Course**: **Microsoft Azure Fundamentals (AZ-900)** <br>

Today I learned about Azure Artifacts and Azure Dev Test Labs.<br>


### Azure Artifacts

Azure Artifacts is a service offered by Microsoft Azure that allows users to create and manage private repositories of packages, such as NuGet, npm, and Maven packages. It is designed to help organizations manage the dependencies of their applications and streamline the development and deployment process.<br>

Azure Artifacts can be used by software developers, DevOps teams, and IT professionals who are involved in the software development process. It is especially useful for organizations that use Microsoft Azure as their cloud platform, as it integrates seamlessly with other Azure services such as Azure DevOps and Azure Functions.<br>

To use Azure Artifacts, users must first create a feed, which is a container for packages. They can then upload their packages to the feed, either manually or through a build pipeline, and share them with other team members. Azure Artifacts provides several tools for managing packages, such as versioning, access control, and retention policies.<br>

### Azure DevTest Labs

Azure DevTest Labs is a service offered by Microsoft Azure that allows users to create and manage development and testing environments in the cloud. It is designed to help organizations streamline their development and testing workflows, reduce costs, and improve productivity.<br>

Azure DevTest Labs can be used by software developers, DevOps teams, and IT professionals who are involved in the software development process. It is especially useful for organizations that use Microsoft Azure as their cloud platform, as it integrates seamlessly with other Azure services such as Azure DevOps and Azure Virtual Machines.<br>

One of the main benefits of using Azure DevTest Labs is that it allows organizations to create development and testing environments quickly and easily, without the need for physical hardware. This helps to reduce costs and improve productivity, as developers and testers can work in a secure, isolated environment that can be easily replicated.<br>




## Day 32 of #Microsoft Azure Fundamentals
:large_blue_diamond: **Course**: **Microsoft Azure Fundamentals (AZ-900)** <br>

Today I learned about Infrastructure as a code and Azure Resource Manager.

### Infrastructure As a Code(IAC)
Infrastructure as code (IaC) refers to the practice of managing and provisioning computing infrastructure (such as servers, virtual machines, networks, and storage) using machine-readable definition files, rather than manually configuring them. In other words, it involves treating infrastructure as code that can be version controlled, tested, and automated.<br>

It is commonly used in cloud environments to manage and automate the provisioning and configuration of infrastructure resources, such as virtual machines, containers, and load balancers.<br>

There are several benefits to using IaC, including:<br>

- Consistency and repeatability: IaC ensures that infrastructure resources are configured and provisioned in a consistent and repeatable way, reducing the likelihood of errors and improving the reliability of infrastructure.

- Version control: IaC allows infrastructure configurations to be version controlled and audited, enabling teams to easily track changes, roll back to previous configurations, and collaborate more effectively.

- Automation: IaC enables the automation of infrastructure management tasks, reducing the need for manual intervention and improving efficiency.

- Scalability: IaC makes it easier to provision and scale infrastructure resources, enabling teams to quickly respond to changes in demand or workload.


### Azure Resource Manager(ARM)

Azure Resource Manager is a management framework provided by Microsoft Azure that allows users to provision and manage resources within Azure. It provides a unified approach to resource management across all Azure services and enables users to create, update, and delete resources as a single unit, called a Resource Group.<br>

Azure Resource Manager is used in Azure environments to manage and deploy resources such as virtual machines, storage accounts, networks, and other Azure services. It also provides features such as role-based access control, tagging, and templates for deploying and managing resources at scale.<br>

Azure Resource Manager is often used in conjunction with Infrastructure as Code (IaC) tools such as Azure Resource Manager templates, PowerShell scripts, or Azure CLI to provision and manage Azure resources using code. Azure Resource Manager templates are JSON files that define the infrastructure resources and configurations needed for an application or workload. The templates can be version-controlled and deployed using a CI/CD pipeline, making it easier to deploy, manage, and scale Azure resources in a consistent and repeatable way.<br>


## Day 33 of #Microsoft Azure Fundamentals
:large_blue_diamond: **Course**: **Microsoft Azure Fundamentals (AZ-900)** <br>

### Azure Quickstart Templates
Azure Quickstart templates are pre-built templates that can be used to deploy commonly used solutions or architectures on the Azure cloud platform. These templates are essentially scripts written in JSON format that can automate the process of creating and configuring Azure resources.<br>

These templates are used when you want to quickly set up a new environment or application in Azure, without having to manually configure every single component. You simply select the template that best matches your requirements, and Azure will automatically create the resources and configure them according to the template.<br>

Azure Quickstart templates are important because they allow you to get up and running quickly, while ensuring consistency and accuracy across different environments. By using templates, you can also reduce the risk of errors or misconfigurations that can occur when configuring resources manually.<br>



### Virtual Networks(vNETs) and Subnets
Virtual networks (VNETs) and subnets are both networking concepts that are used in the context of cloud computing, particularly in the Microsoft Azure cloud platform.<br>

A virtual network (VNET) is essentially a private network that is hosted within the Azure cloud platform. It provides a secure and isolated environment in which you can deploy your resources, such as virtual machines, web applications, and databases. Within a VNET, you can define IP address ranges, subnets, and routing tables to control network traffic.<br>

A subnet, on the other hand, is a smaller network within a larger network (in this case, the VNET). It is a range of IP addresses that are reserved for a specific set of resources or services. By dividing a VNET into subnets, you can further segment your network and apply additional security controls.<br>



