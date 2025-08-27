**Microsoft Azure**

**Azure Console**

![](images/media/image7.png)

**Creating an Ubuntu Virtual Machine in Azure**

![](images/media/image32.png)

![](images/media/image15.png)

**Connecting to that VM using SSH**

**ssh -i \<private-key-file-path\> azureuser@publicip**

![](images/media/image2.png)

Creating a security inbound rule allowing HTTP to access nginx page

![](images/media/image20.png)

Ngnix installed successfully

![](images/media/image26.png)

Virtual Machine

each VM has its own image & we can find new images from marketplace

![](images/media/image29.png)

Azure VM has different series

Like A series - **Entry-level VMs for dev/test**

Bs Series - **Economical burstable VMs**

**D series - General purpose compute**

![](images/media/image16.png)

**Azure VM Disks**

**IOPS: (Input/Output per second)**

how many read/write operations a system can perform in one second.

Like using data base which needs high read and write operations

**Throughput**:

amount of data transferred per second.

Eg. To Copy large videos & files

![](images/media/image17.png)

![](images/media/image9.png)

**Snapshot:**

A **snapshot** in Azure is a **point-in-time, full, read-only copy** of
a managed disk.

![](images/media/image12.png)

Create a snapshot and attach it to new VM

![](images/media/image4.png)

![](images/media/image22.png)

We can create a snapshot and then create a disk attach to an existing
disk

Generally Virtual network,Network interfaces Network Security Groups are
free of cost in azure

![](images/media/image31.png)

Public ip, Disk etc.. price depends on time.

![](images/media/image24.png)

**AZure Key-vault Service**

![](images/media/image11.png)

![](images/media/image6.png)

**Custom Script Extensions**

![](images/media/image8.png)

![](images/media/image3.png)

![](images/media/image30.png)

![](images/media/image28.png)

**We can also use custom data**

![](images/media/image10.png)

![](images/media/image5.png)

**Boot diagnostics is a feature in Azure Virtual Machines (VMs) that
helps you troubleshoot VM startup issues.**

**When you enable it, Azure captures:**

1.  **Console output (text output during boot)\
    > **

2.  **Screenshot of the VM's desktop (for Windows) or console (for
    > Linux)\
    > **

**This helps you see what's happening inside the VM when it starts up
--- useful if the VM is stuck, unresponsive, or fails to boot.**

**Run Commad:**

**Run Command in Azure lets you run scripts or commands inside an Azure
VM directly from the Azure Portal, CLI, or PowerShell --- without
needing to log in via RDP (Windows) or SSH (Linux).**

![](images/media/image23.png)

**Availability Sets**

![](images/media/image18.png)

**Availability Set → Protects against failures within one datacenter
(rack-level).\
**

**Availability Zone → Protects against failures across multiple
datacenters in a region.**

**Availability Set = a grouping feature that distributes your VMs across
multiple fault domains and update domains, ensuring higher availability
within a single Azure region datacenter.**

**AZURE Scale set**

**An Azure Virtual Machine Scale Set (VMSS) is a service that lets you
deploy and manage a set of identical VMs that can automatically scale
in/out based on demand or a defined schedule.**

**Think of it as an auto-scaling group of VMs behind a load balancer.**

-   **Automatically increase capacity when demand is high.**

-   **Automatically decrease capacity when demand is low (saving
    > cost).**

-   **Ensure high availability (VMs are spread across fault/update
    > domains or zones).**

**Virtual Machine Images**

![](images/media/image13.png)

**We can create Images from an existing VM. It is the complete blueprint
of the VM which we can use to launch another VM which has the same
functionality.**

![](images/media/image1.png)

**Proximity Placement groups**

**Proximity Placement Group (PPG) is an Azure logical grouping that
ensures your Virtual Machines (VMs) are physically located close to each
other within the same datacenter.**

**Sometimes Apps need least latency ,High-Performance Computing (HPC),
n-memory databases (like Redis, SAP HANA),**

![](images/media/image21.png)

**\
**

**Azure Webapp**

**An Azure Web App is a Platform-as-a-Service (PaaS) offering from
Microsoft Azure that allows you to host, build, and scale web
applications without managing the underlying infrastructure.**

**like .NET, Java, Python, PHP, Node.js, Ruby, etc.**

![](images/media/image19.png)

![](images/media/image25.png)

**Free plan has only 60/day of webapp**

**Azure App Service (Web Apps), Deployment Slots are like having
multiple live environments (instances) for your application within the
same App Service.**

**They allow you to safely deploy and test changes without affecting
your production app.**

![](images/media/image14.png)

**Autoscaling in azure webapp**

![](images/media/image27.png)
