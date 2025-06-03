# Describe The Azure Databricks Platform Architecture
Azure Databricks (ADB) is a fully-managed cloud-based, big data and machine learning platform witch simplifies the developing of enterprise grade production data applications.

ADB is natively integrated with Azure providing a firts-party Microsoft service.

## Azure Databricks collaborative workspace
Enables teams to work together by using features such as:
1. User management.
2. Git source code repository integration.
3. User workspace folders.

ADB is totaly integrated with Azure, we can use VMs to setting up our clusters, there are several VM series:
1. F-Series for machine learning scenarios.
2. M-Series for massive memories scenarios.
3. D-Series for general purpose.

## Security and privacy
The ownership and control of data is always with the customer.
Microsoft aims for ADB to adhere to all of the compliance certifications that the rest of Azure provides.

## Networks
To ensure flexibility and network topology, ADB supports deployments into virtual networks (VNets), This implementation allows have control on which sourses and sinks can be accessed and how they can be accessed.

## Azure Active Diretory (Azure AD)
Azure AD can be used to control access to sources, results and jobs.

## Azure Storage
Azure Storage and Data Lake Store services are exposed to ADB users through the Databricks File System DBFS to provide caching and optimized analysis over existing data.
