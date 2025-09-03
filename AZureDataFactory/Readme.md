**Azure Data Factory**

**ADF managed service in the cloud for scale-out serverless data
integration, data transformation and orchestration**

-   **Azure data factory is PaaS service , so we don\'t requried to
    > manage the patching , upgrading, maintaining and provisioning
    > infrastructure on cloud and on-premises etc and there is no
    > upfront cost**

![](images/media/image5.png)

Managed service in the cloud for scale-out serverless data integration,
data transformation & orchestration.

Pay for what we use

**Benefits of azure data factory:**

Data Transformation

Data Integration

Orchestration

![](images/media/image33.png)

![](images/media/image21.png)

![](images/media/image1.png)

Software Tools which require for this project

-   VS Code & extensions

-   Git or Azure Devops

![](images/media/image40.png)

![](images/media/image14.png)

Azure Resources that we will need

Azure data lake , Data factory, Azure Sql DB, Storage account

Create a storage account for data lake

![](images/media/image7.png)

Create Azure Data factory

![](images/media/image30.png)

![](images/media/image11.png)

Azure Data Studio Integration with Mysql

![](images/media/image24.png)

![](images/media/image44.png)

Azure Storage Explorer Setup

![](images/media/image47.png)

![](images/media/image26.png)

![](images/media/image31.png)

![](images/media/image41.png)

![](images/media/image27.png)

1.  Landing - The data arrive to this containers. Just drop data as it
    > is. No changes.

2.  Raw - The raw data like json and csv file will be stored here
    > without process. Data is still unstructured but you organized it
    > by folders, date etc.

3.  Cleansed - Cleaned, stores Unique data and remove duplicates. we
    > will process the data from cleansed contianer into a staging layer
    > within Azure SQL DB.

![](images/media/image46.png)

Running the First Data Pipeline to Azure data factory

The aim of this pipeline to copy and unzip the the data which inside the
raw container and paste and unzip from lending container.

![](images/media/image43.png)

![](images/media/image25.png)

![](images/media/image6.png)

Another pipeline the aim of this pipeline to cleanse the data and paste
it into cleanse named container extract it to salesdata

![](images/media/image15.png)

![](images/media/image51.png)

![](images/media/image32.png)

Key-vault ser

![](images/media/image13.png)

Importing Semi Structured data

![](images/media/image3.png)

![](images/media/image35.png)

Modification and transform the data

#### **Mapping Data Flows**

-   data flow : data flow is a visual tool that allows you to design and
    > build data transformation logic without writing code. This is a
    > key component of ADF, designed for data engineers to create
    > complex data workflows using a drag-and-drop interface. The data
    > flows are then executed on scaled-out Apache Spark clusters
    > managed by Azure, which handles all the code translation and
    > optimization behind the scenes

![](images/media/image37.png)

![](images/media/image49.png)

![](images/media/image38.png)

![](images/media/image8.png)

![](images/media/image22.png)

![](images/media/image10.png)

![](images/media/image45.png)

Implementing Flowlets

![](images/media/image4.png)

![](images/media/image36.png)

Implementing with pipeline

![](images/media/image2.png)

Asserts

![](images/media/image28.png)

Data Warehouse

![](images/media/image42.png)

![](images/media/image23.png)

Data Processing

![](images/media/image34.png)

**Triggers**

![](images/media/image29.png)

Creating a master pipeline to execute two pipelines

![](images/media/image20.png)

Creating triggers

![](images/media/image12.png)

![](images/media/image18.png)

Trigger Executed

![](images/media/image19.png)

There is cost associated with pipeline run so we should schedule it.

Monitoring

![](images/media/image39.png)

What to Monitor

-   Data Factory Resources

-   Pipelines

-   Activities

-   Triggers

-   Integration Run time

![](images/media/image17.png)

Integration Run Time

![](images/media/image16.png)

![](images/media/image48.png)

![](images/media/image9.png)

Metrics

![](images/media/image50.png)
