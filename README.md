# End to End Data Engineering Pipeline: Airline  Data Ingestion Pipeline in Azure

In the Azure environment, a dedicated **Data Factory (ADF) namespace** is used for development. During development, data is read from the storage account named **development**, while a separate storage account is used for production.

The steps for setting up **ADF** in the development environment are as follows:

1. **Linked Service Creation**: First, a linked service is set up for the storage account. This step involves specifying the storage account name, authentication details, and connection string for the storage account.

2. **Dataset Creation**: The next step is to create datasets for both the source and target locations. A dataset is configured to point to the exact location of the file being read, as well as the target storage account where the data will be written.

3. **Pipeline Creation**: Finally, a pipeline is created in **ADF** to orchestrate the data flow between the source and target storage accounts.

This outlines the development process for **ADF** in the Azure environment. 
### **Architecture**
[Architecture](AirLineDataCICD.png)

