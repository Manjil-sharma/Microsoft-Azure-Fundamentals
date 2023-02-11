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
                          -Scaling In (Removing more services of same size)<br>
                  
                  




## Day 9 of #Microsoft Azure Fundamentals
:large_blue_diamond: **Course**: **Microsoft Azure Fundamentals (AZ-900)** <br>

Today I continued learning about Cloud Terminologies

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












