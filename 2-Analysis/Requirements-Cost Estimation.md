<h2>Cloud configuration: Azure & AWS</h2>

|                      | Azure                    | Aws                               |
|----------------------|--------------------------|-----------------------------------|
| UI                   | Azure App Service        | AWS ECS/S3                        |
| Event Processing     | Azure Functions          | AWS Lambda                        |
|                      | Azure Notification Hubs  | AWS Simple Notification Service   |
| Labeling/Training/ML | Azure Kubernetes Service | Amazon Elastic Kubernetes Service |
| Storage              | Azure Blob storage       | AWS S3                            |
| Data Management      | Azure database           | AWS RDS                           |


<h2>Basic</h2>
Currency: USD <br/>
Region: US-west

| Service category | Service type | Description | Estimated monthly cost | Saving plan monthly cost | Notes |
|-------------------|--------------|-------------|-------------------------|---------------------------|-------|
| Compute           | App Service  | Standard Tier; 1 S1 (1 Core(s), 1.75 GB RAM, 50 GB Storage) x 730 Hours | $73.00 | | |
| Compute           | Azure Functions | Consumption tier, Pay as you go, 128 MB memory, 100 milliseconds execution time, 0 executions/mo | $0.00 | | The first 400,000 GB/s of execution and 1,000,000 executions are free. Per extra 1,000,000, $0.20/per month |
| Web               | Notification Hubs | Free tier | $0.00 | | Includes 1 million pushes for 500 active devices. |
| Compute           | Azure Kubernetes Service (AKS) | Standard; Cluster management for 1 clusters; 1 D2 v3 (2 vCPUs, 8 GB RAM) x 730 Hours (Pay as you go), Linux; 0 managed OS disks – S4 | $144.62 | 1y: &#36;135.24 <br/> 3y: &#36;122.44 <br/><br/>Reserved instances  <br/> 1y: &#36;116.28 <br/> 3y: $101.42 |
| Storage           | Storage Accounts | Block Blob Storage, General Purpose V2, Hierarchical Namespace, LRS Redundancy, Hot Access Tier, 1,000 GB Capacity - Pay as you go, 10 x 10,000 Write operations, 10 x 10,000 Read operations, 10 x 10,000 Iterative Read operations, 10 x 100 Iterative Write operations, 1,000 GB Data Retrieval, 1,000 GB Data Write, 1,000 GB Index, 1 x 10,000 Other operations | $45.41 | | |
| Databases         | Azure SQL Database | Single Database, vCore, General Purpose, Provisioned, Standard-series (Gen 5), Locally Redundant, 1 - 2 vCore Database(s) x 730 Hours, 32 GB Storage, RA-GRS Backup Storage Redundancy, 0 GB Point-In-Time Restore,  0 x 5 GB Long Term Retention | $372.97 | $295.23 | |
| Identity          | Azure Active Directory External Identities | Premium P1 tier: 50,000 monthly active user(s), 0 SMS/Phone Events | $0.00 | Your first 50,000 MAUs per month are free for both Premium P1 and Premium P2 features. More than 50,000 MAU, <br/> <br/>basic: &#36;0.00325, <br/>P2: $0.01625 | MAU: Month Activate Users
|                   | **Total** | | **$636.00** | **$558.26** | Depends on AKS payment plan selection. Save &#36;10 to &#36;40 |

<h2>Advanced</h2>

| Service category | Service type | Description | Estimated monthly cost | Saving plan monthly cost | Notes |
|-------------------|--------------|-------------|-------------------------|---------------------------|-------|
| Compute           | App Service  | Premium V2 Tier; 1 P1V2 (1 Core(s), 3.5 GB RAM, 250 GB Storage) x 730 Hours | $146.00 | | |
| Compute           | Azure Functions | Premium tier, Pay as you go, EP1: 1 Cores(s), 3.5 GB RAM, 250 GB Storage, 1 Pre-warmed instances, 1 Additional scaled out units | $291.85 | $242.24 | |
| Web               | Notification Hubs | Basic tier, 1 million additional pushes | $10.00 | | |
| Compute           | Azure Kubernetes Service (AKS) | Standard; Cluster management for 1 clusters; 1 D2 v3 (2 vCPUs, 8 GB RAM) x 730 Hours (Pay as you go), Linux; 0 managed OS disks – S4 | $143.08 | 1y: &#36;60.70 <br/> 3y: &#36;47.90 <br/> <br/>Reserved instances <br/>1y: &#36;41.75 <br/>3y: &#36;26.89 |
| Storage           | Storage Accounts | Block Blob Storage, General Purpose V2, Hierarchical Namespace, LRS Redundancy, Cool Access Tier, 1,000 GB Capacity - Pay as you go, 10 x 10,000 Write operations, 10 x 10,000 Read operations, 100,000 Archive High Priority Read, 10 x 10,000 Iterative Read operations, 10 x 100 Iterative Write operations, 1,000 GB Data Retrieval, 1,000 GB Archive High Priority Retrieval, 1,000 GB Data Write, 1 x 10,000 Other operations | $22.14 | | |
| Databases         | Azure SQL Database | Single Database, vCore, General Purpose, Provisioned, Standard-series (Gen 5), Locally Redundant, 1 - 4 vCore Database(s) x 730 Hours, 32 GB Storage, RA-GRS Backup Storage Redundancy, 0 GB Point-In-Time Restore,  0 x 5 GB Long Term Retention | $741.16 | $585.68 | |
| Identity          | Azure Active Directory External Identities | Premium P1 tier: 50,000 monthly active user(s), 0 SMS/Phone Events | $0.00 | Your first 50,000 MAUs per month are free for both Premium P1 and Premium P2 features. More than 50,000 MAU, <br/>basic: &#36;0.00325, P2: &#36;0.01625 | MAU: Month Activate Users
|                   | **Total** | | **$1,354.23** | **$1,198.75** | Depends on AKS payment plan selection. Save $60 to $120 |
