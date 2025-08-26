**Microsoft Azure**

Virtual Machine

each VM has its own image & we can find new images from marketplace

![](images/media/image4.png)

Azure VM has different series

Like A series - **Entry-level VMs for dev/test**

Bs Series - **Economical burstable VMs**

**D series - General purpose compute**

![](images/media/image2.png)

![](images/media/image3.png)

Generally Virtual network,Network interfaces Network Security Groups are
free of cost in azure

![](images/media/image5.png)

Public ip, Disk etc.. price depends on time.

![](images/media/image1.png)

Deploying the Linux Virtual & Windows Virtual machine in Azure

Click + Create → azure Vm

### **Configure Basics**

-   **Subscription**: Select your subscription.

-   **Resource Group**: Create a new one or select existing.

-   **Virtual machine name**: e.g., myLinuxVM.

-   **Region**: Select the Azure region (e.g., East US, Central India).

-   **Availability options**: Leave default unless you need HA.

-   **Image**: Choose Linux distro (e.g., **Ubuntu Server 22.04 LTS**).

-   **Size**: Select a VM size (e.g., B1s for testing).

Virtual network every time created new if we don't specify
