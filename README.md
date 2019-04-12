# azureinterviewquestions
Azure Interview Questions


**1. What is an Availability Set?**
When Virtual Machines are part of the same Availability Sets, Azure will place these virtual machines across seperate Fault Domains - essentially racks with independent power, cooling, etc. See this as a form of "anti-affinity".

**2. What are managed disks?**
Managed Disks are an abstraction over storage accounts, blob storage etc. They are a random IO object in Azure, and Microsoft manages all aspect of the disk.

3. Can existing VMs be added to an Availability Set?
No.

4. What are the types of storage in Azure?
Queue Storage, Blob storage, file storage, table storage.

5. What are scale sets?
Scale Sets are a grouping of identical VMs, built for autoscaling.

6. What are Network Security Groups?
Network Security Groups are ACLs to permit or deny traffic between subnets and NICs, in a VNET. 

7. Can you explain Azure Service Fabric?
It is a distributed system platform, which makes it easy to pack, deploy and manage the micro services.

8. What are script modules?
Script modules allow users to create PowerShell functions or Cmdlets that could later on be used in deployment processes across multiple projects.

9. What are the various patterns for deployments?
Blue-green deployments, canary deployments, offline package drop, multi-tenant deployments, rolling deployents, isolated deployments.

10. What are the benefits and drawbacks of cloud computing?

Benefits are increased enterprise agility, elastic capacity, also often overseen is that cloud providers have datacentres which have lower carbon footprint so this may be particularly attractive for companies with a CSR (Corporate Social Responsibility) of reducing emissions. 

Cloud providers also have compliance certifications to ensure use by any industry, which are often expensive and difficult to achieve for enterprises. Cloud providers also enable enterprises to cut out the cost of hardware, thereby moving to an OPEX model, which is more flexible. This change in finance management does have process implications, however.

By default, applications built on the cloud are easily available in multiple regions, which used to be difficult to achieve.

11. What are disadvantages of the cloud?

Some of the  benefits of the cloud can also be disadvantages.

The move to a shared responsibility model can also mean that the lack of control may be a constraint in day-to-day operations. For example, there is no way to implement a custom status page for Office 365 when it is down. In addition, some applications have specific networking requirements and these may not work in the cloud, where this cannot be changed.

There is a high opportunity cost to adopting cloud. To fully realise benefits such as increased agility, a substantial investment needs to be made initially in training, changing behaviours, to therefore change culture. So initial cost of cloud migration and adoption will be high.

In addition, while the cloud will, in some respects, simplify the IT landscape in the enterprise, it will also add complexity. There will be additional APIs to manage, new roles in teams (cloud auditor, cloud broker), multiple provider SLAs to monitor, additional governance processes to implement, a CMP (Cloud Magement Platform) to procure and manage, 

12. What is the history of cloud computing?

**13. What is a cloud broker?**

A cloud broker is an intermediary acting on behalf of the purchaser of cloud services, negotiating deals and managing the relationship with cloud providers.


 **- How to reduce cloud costs without effecting capacity?**
 - Leverage discount options/reserved instances
 - Use less expensive regions
 - Shut down idle virtual machines

 - What is a virtual directory in IIS?

**15. What makes a cloud native architecture?**

Use of managed services, elastic scaling ability, distributed caching.

 1.  What are some loadbalancing strategies?
 2.  What is the difference between an L4/ L7 loadbalancer
 3.  Whare are some caching strategies
 4.  Explain the differences between SQL & NoSQL and where you would use each one.
 5.  Describe partioning/ sharding
 6.  CAP theorem

The CAP theorem is the belief that a distributed application can only satisfy two of the following characteristics:

Consistency
Availability
 
 7. When you here the word "Orchestration", what do you think of in
    terms of software delivery?
 8.   What are the advantages of orchestration tools?
 9.   What are some use cases of orchestration tools?
 10.   What orchestration tools have you used in the past?
 11.   Can you explain the architecture of <tool_mentioned_above>
 12.   Can you provide a detailed example of how you used <tool_mentioned_above> to solve a complex problem?
 13.   How does <tool_mentioned_above> handle authentication and authorization?
 14.   How does <tool_mentioned_above> handle encryption of data?
 15. 
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTU2OTk5NzUwMCwtMjk1MjA1MzQsNTc0Mz
MzMTg4LDQ1NDM4MTE4OCwtMjEyNTMwNjY1N119
-->