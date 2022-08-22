# VEEAM HANDS-ON LAB FOR MICROSOFT AZURE

## VEEAM

Veeam Software is a privately held US-based information technology company owned by Insight Partners that develops backup, disaster recovery and modern data protection software for virtual, physical and multi-cloud infrastructures. The company's headquarters are in Baar, Switzerland and Columbus, Ohio, United States

Veeam Backup & Replication v11 delivers industry‑leading Modern Data Protection for your growing enterprise, including some great NEW cloud and security capabilities in the latest V11A r            elease. Whether you're seeking the most flexible hybrid cloud capabilities from AWS, Azure and Google Cloud, or the most robust ransomware protection and recovery options, Veeam is ready! Veeam brings hardened immutable storage options, dependable cloud‑native backup options, Continuous Data Protection and much more all under one platform, with a single portable license for all workloads!


Veeam Backup for Microsoft Azure does not install agent software inside instances to retrieve data. To back up resource data, Veeam Backup for Microsoft Azure uses native Microsoft Azure capabilities. During every backup session, Veeam Backup for Microsoft Azure creates a cloud-native snapshot (for an Azure VM or an Azure file share) or a BACPAC file (for an Azure SQL database) for each Azure resource added to a backup policy. The cloud-native snapshot is further used to create an image-level backup of the Azure VM, and the BACPAC file is used to create an image-level backup of the Azure SQL database.

## Lab context

### Exercise 1: Getting Started with Azure
In this exercise, you will log in to the Azure Portal and review the pre-deployed resources as part of the lab environment.

### Exercise 2: Access and Configure VEEAM Backup for MS Azure
In this exercise, you will deploy a Veeam Virtual machine to configure Backup for MS Azure, and also you will add Microsoft Azure Account, Workers to Workspace, and Repository to the Virtual Machine.

### Exercise 3 : Create Backup policy for Virtual Machines
In this exercise, you will create the backup for both Linux and Windows virtual Machine.

### Exercise 4: Delete and Restore Virtual machines
In this exercise, you will delete the windows VM, then work on the backup of the Windows VM and also recovery of files from the Linux VM

### Exercise 5: Add Azure SQL Backup
In this exercise, you will be adding Azure SQL Backup. Azure Backup offers a stream-based, specialized solution to back up SQL Server running in Azure VMs. This solution aligns with Azure Backup's benefits of zero-infrastructure backup, long-term retention, and central management.

### Exercise 6: Delete and Restore SQL Database
In this exercise, you will be deleting the created SQL database from Azure portal and restoring it from Veeam Backup.

### Exercise 7: Backup of Azure File Share
In this exercise, you are creating the backup for the Azure file share

### Exercise 8: Restore Azure File Share
In this exercise, we are doing recovery of file share
