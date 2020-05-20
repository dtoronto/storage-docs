# Veeam Availability Platform

| GPv2 Storage |  Cool Tier | Archive Tier | WORM Support | On-prem to Azure | Backup Azure VM's | Azure Files | Backup Azure Blob |
|--------------|------------|--------------|--------------|------------------|-------------------|-------------|-------------------|
|X             |X           |              |X (possible through 3rd party VTL) |X                 |X                  |X            |                   |

### Links to Marketplace Offerings
- https://azuremarketplace.microsoft.com/en-us/marketplace/apps/veeam.veeam-backup-replication?tab=Overview
- https://azuremarketplace.microsoft.com/en-us/marketplace/apps/veeam.veeam-backup-replication?tab=Overview
- https://azuremarketplace.microsoft.com/en-us/marketplace/apps/veeam.azure_backup_free
- https://azuremarketplace.microsoft.com/en-us/marketplace/apps/veeam.azure_backup


### Is the Marketplace Offering required for Backup into Azure?
- Marketplace offering is an alternative to on premises installation, but not mandatory needed for Veeam Backup & Replication and Veeam Backup for Office 365. Veeam Backup for Microsoft Azure is only available at the Azure Marketplace.

### Is the Marketplace Offering required for Recovery in Azure?
- Not needed, but possible usage in a disaster recovery situation when on premises datacenter is not available. For Veeam Backup for Microsoft Azure this is the primary usecase.

### Is the Marketplace offering required for Protection of Azure Resources?
- Backup of Azure VMs, Backup of Office 365, Backup of Azure Files, Backup of Azure NetApp files and Backup of Applications like Oracle/SAP/SQL/Sharepoint running on VMs (Plug-ins/Agents).

### Links to Relevant Documentation
- https://helpcenter.veeam.com/docs/backup/hyperv/overview.html
- https://helpcenter.veeam.com/docs/vbo365/guide/vbo_introduction.html 

### Specific pages covering Azure considerations, best practices, steps to implement
- Restore to Azure: https://helpcenter.veeam.com/docs/backup/vsphere/restore_azure.html
- Backup to Azure BLOB https://helpcenter.veeam.com/docs/backup/hyperv/adding_azure_object_storage.html
- Backup to Azure BLOB: https://helpcenter.veeam.com/docs/vbo365/guide/adding_azure_storage.html   

### A Reference Architecture for On-Premises -to-Azure and In-Azure deployment
- Direct Restore to Azure: https://www.veeam.com/blog/direct-restore-azure-integrated-veeam-backup-replication.html
- On-premises deployment: https://helpcenter.veeam.com/docs/vbo365/guide/vbo_deployment.html
- In-Azure Deployment: https://www.veeam.com/blog/office-365-backup-azure-market.html

### A brief step-by-step of how to implement
- https://helpcenter.veeam.com/docs/backup/qsg_hyperv/getting_started.html
- https://helpcenter.veeam.com/docs/vbo365/guide/vbo_deployment.html

### Links to User Guide content on Veeam’s Support Site
- https://helpcenter.veeam.com

### Network bandwidth and storage account guidance
- http://rps.dewin.me/bandwidth/

### Links to Screenshots
- https://www.veeam.com/blog/wp-content/uploads/2017/03/123.png

### A brief guide of how to monitor the deployment going forward
- https://helpcenter.veeam.com/docs/one/qsg/welcome.html

### Information on Azure alerting and performance monitoring
- https://helpcenter.veeam.com/docs/one/qsg/welcome.html

### Links to User Guide content on Veeam’s Support Site
- https://helpcenter.veeam.com/docs/one/qsg/welcome.html

### Additional videos showcasing recovery in Azure and monitoring the backup to Azure
- https://www.veeam.com/videos/cloud-restore-azure-integration-7999.html

### How to open support cases?
- https://www.veeam.com/support.html

