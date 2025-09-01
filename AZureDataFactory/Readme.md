**Azure Data Factory**

**ADF managed service in the cloud for scale-out serverless data
integration, data transformation and orchestration**

-   **Azure data factory is PaaS service , so we don\'t requried to
    > manage the patching , upgrading, maintaining and provisioning
    > infrastructure on cloud and on-premises etc and there is no
    > upfront cost**

![](images/media/image12.png)

Managed service in the cloud for scale-out serverless data integration,
data transformation & orchestration.

Pay for what we use

**Benefits of azure data factory:**

Data Transformation

Data Integration

Orchestration

![](images/media/image15.png)

![](images/media/image4.png)

![](images/media/image2.png)

Software Tools which require for this project

-   VS Code & extensions

-   Git or Azure Devops

![](images/media/image3.png)

![](images/media/image23.png)

Azure Resources that we will need

Azure data lake , Data factory, Azure Sql DB, Storage account

Create a storage account for data lake

![](images/media/image14.png)

Create Azure Data factory

![](images/media/image10.png)

![](images/media/image6.png)
Azure Data Studio Integration with Mysql

![](images/media/image17.png)

![](images/media/image25.png)

Azure Storage Explorer Setup

![](images/media/image8.png)

![](images/media/image18.png)

![](images/media/image13.png)

![](images/media/image11.png)

![](images/media/image24.png)

1.  Landing - The data arrive to this containers. Just drop data as it
    > is. No changes.

2.  Raw - The raw data like json and csv file will be stored here
    > without process. Data is still unstructured but you organized it
    > by folders, date etc.

3.  Cleansed - Cleaned, stores Unique data and remove duplicates. we
    > will process the data from cleansed contianer into a staging layer
    > within Azure SQL DB.

![](images/media/image21.png)

Running the First Data Pipeline to Azure data factory

The aim of this pipeline to copy and unzip the the data which inside the
raw container and paste and unzip from lending container.

![](images/media/image9.png)

![](images/media/image16.png)

![](images/media/image20.png)

Another pipeline the aim of this pipeline to cleanse the data and paste
it into cleanse named container extract it to salesdata

![](images/media/image7.png)

![](images/media/image26.png)

![](images/media/image22.png)

Key-vault ser

![](images/media/image19.png)

Importing Semi Structured data

![](images/media/image5.png)

![](images/media/image1.png)
