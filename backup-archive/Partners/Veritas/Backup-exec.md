# Backup Exec Partner Documentation

### Minimum Software version required to support read/write from Azure Blob Storage and support of features in the Support Matrix (if supported)
- Backup to Azure Hot/Cool Tiers – Backup Exec 16 or later
- Dedupe to Azure Hot/Cool – Backup Exec 16 or later with OpenDedup
- Dedupe to Azure Archive – Backup Exec 20.1 or later with OpenDedup
- https://www.veritas.com/support/en_US/article.100038940

| GPv2 Storage |  Cool Tier | Archive Tier | WORM Support | On-prem to Azure | Backup Azure VM's | Azure Files | Backup Azure Blob |
|--------------|------------|--------------|--------------|------------------|-------------------|-------------|-------------------|
|BE 16         |BE 16       |BE 20.1 /w OpenDedupe|N/A             |BE 20.2 via ASR-integration|BE 16 (w/Agents)   |Comming in BE 21.1|N/A                |


Azure and Azure China supported with BE 16 for Cloud Connectors. Azure Government and Azure Germany with BE 16 FP2 and higher
Backup Exec Instant Cloud Recovery in BE 20.2 and later, Instant Cloud Recovery (ICR) powered by Azure Site Recovery (ASR) takes the Azure cloud integration further by leveraging the native Azure Disaster Recovery-as-a-Service (DRaaS) to complement off-site backups.

Additionally Backup Exec supports 3rd party storage appliances with connection to Azure storage as described in the HCL

### Link(s) to Marketplace Offering(s)
- Marketplace offering enables easy deployment of BE Server into Azure – enabled backup in Azure (IaaS), Recovery in Azure (IaaS). Integrates with Azure Site Recovery (ASR)
- https://azuremarketplace.microsoft.com/en-us/marketplace/apps/veritas.backup-exec-20

### Links to relevant documentation
- https://www.veritas.com/protection/backup-exec/azure
- https://www.veritas.com/support/en_US/article.100038940
- https://azure.microsoft.com/en-gb/blog/azure-site-recovery-powers-veritas-backup-exec-instant-cloud-recovery-for-disaster-recovery/
- https://vox.veritas.com/t5/Backup-Exec/Introducing-Instant-Cloud-Recovery-in-Veritas-Backup-Exec-20-2/ba-p/855353
- https://vox.veritas.com/t5/Backup-Exec/How-to-deploy-Backup-Exec-from-Microsoft-Azure-Marketplace/ba-p/843662

###Refeerence Architecture for On-premises-to-Azure and In-Azure deployments
- https://www.veritas.com/support/en_US/article.100038940
- https://vox.veritas.com/t5/Backup-Exec/How-to-deploy-Backup-Exec-from-Microsoft-Azure-Marketplace/ba-p/843662

### Step-by-step guide of how to implement
- https://www.veritas.com/support/en_US/article.100038940
- https://vox.veritas.com/t5/Backup-Exec/How-to-deploy-Backup-Exec-from-Microsoft-Azure-Marketplace/ba-p/843662

### Videos showcasing implementing Azure Storage with Veritas
- https://www.youtube.com/watch?v=4uThVJd60SU
- https://www.youtube.com/watch?v=VpSOOBrWdjE

###How to Open Support Cases
- https://www.veritas.com/support/en_US/article.100038625
