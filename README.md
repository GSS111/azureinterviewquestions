# azureinterviewquestions
Azure Interview Questions


1. What is an Availability Set?
When Virtual Machines are part of the same Availability Sets, Azure will place these virtual machines across seperate Fault Domains - essentially racks with independent power, cooling, etc. See this as a form of "anti-affinity".

2. What are managed disks?
Managed Disks are an abstraction over storage accounts, blob storage etc. They are a random IO object in Azure, and Microsoft manages all aspect of the disk.

3. Can existing VMs be added to an Availability Set?
No.

4. What are the types of storage in Azure?
Queue Storage, Blob storage, file storage, table storage.

5. What are scale sets?
Scale Sets are a grouping of identical VMs, built for autoscaling.
