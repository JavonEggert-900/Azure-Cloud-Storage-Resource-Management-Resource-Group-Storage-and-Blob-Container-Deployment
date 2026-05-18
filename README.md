# Azure Cloud Storage and Resource Management: Resource Group, Storage Account and Blob Container Deployment

<p align="center">
<img src="https://github.com/user-attachments/assets/caf8fa0b-536a-4905-88d7-7cba9a8532a7" alt="Microsoft Azure Header" width="80%"/>
</p>

## Project Overview

This project demonstrates the foundational deployment and management of cloud storage infrastructure using Microsoft Azure. Starting from scratch, a Resource Group and Storage Account were provisioned, a blob container was created, and files were uploaded, edited and downloaded directly within the Azure Portal. Every step reflects how businesses organize, store and manage data in the cloud, from initial resource provisioning to proper cost management through resource cleanup. This project establishes the core cloud infrastructure skills that underpin every Azure deployment in a real business environment.

# Environments and Technologies Used

* Microsoft Azure (Resource Groups, Storage Accounts, Blob Containers, Cost Management)
* Azure Portal
* Microsoft Azure Blob Storage

# Operating Systems Used

* macOS (local machine used to access Azure Portal)

# Project Objectives

* Create and configure a Resource Group in Microsoft Azure
* Deploy a Storage Account within the Resource Group
* Build a blob container to organize and store files in the cloud
* Upload a text file to the container and edit it directly within the Azure Portal
* Download the file to verify changes were saved successfully
* Delete all resources after completion to practice proper cloud cost management
* Review Cost Management and Cost Analysis within Azure

# High-Level Deployment and Configuration Steps

1. Create a free Azure subscription and log into the Azure Portal
2. Observe the portal including Resource Groups, Virtual Machines and Entra ID
3. Create a Resource Group
4. Create a Storage Account within the Resource Group
5. Create a text file on the local desktop and upload it to the Storage Account
6. Edit the file directly within the Azure Portal
7. Download the file and verify the changes
8. Delete the Resource Group to avoid unnecessary charges
9. Verify the Resource Group has been successfully deleted
10. Review Cost Management and Cost Analysis

# Deployment and Configuration Steps

## Step 1: Resource Group Overview

<p align="center">
<img src="https://github.com/user-attachments/assets/545c6f18-78a8-47b1-a810-b178471220e5" alt="Resource Group Overview" width="80%"/>
</p>

Created a Resource Group named Re.1Group in the Microsoft Azure Portal with the Storage Account javonsfirststorage successfully deployed inside it. Resource Groups are how businesses logically organize their cloud assets, grouping related services together for easier management, cost tracking and access control. Every enterprise Azure deployment begins with this foundational structure.

## Step 2: Blob Container with File Inside

<p align="center">
<img src="https://github.com/user-attachments/assets/976513c0-d36c-4193-9d9a-f3c720140d9f" alt="Container Selected with File Inside" width="80%"/>
</p>

Built a blob container named labtest within the Storage Account and successfully uploaded Azure.Lab.Text as a Block Blob with Hot access tier. Blob containers are how businesses store unstructured data in the cloud, documents, images, backups and log files all live in blob storage. The Hot access tier ensures frequently accessed data is available instantly, reflecting how businesses balance performance and cost in their storage configurations.

## Step 3: Storage Account Containers View

<p align="center">
<img src="https://github.com/user-attachments/assets/c07b50fa-c31b-4ad1-b4c3-eacf05ab4034" alt="Storage Account Containers View" width="80%"/>
</p>

Viewed the full Containers section within the Storage Account showing the labtest container successfully created and active. In a business environment a single Storage Account may contain dozens of containers organizing different types of data for different departments, applications or clients, each with its own access controls and retention policies.

## Step 4: Text File Edited in Azure Portal

<p align="center">
<img src="https://github.com/user-attachments/assets/b8d45a82-9ade-4ed2-9df8-e92b7102a129" alt="Text File Edited in Azure Portal" width="80%"/>
</p>

Opened Azure.Lab.Text directly within the Azure Portal and edited the file contents without leaving the cloud environment. The ability to interact with stored files at the blob level directly in the portal, viewing, editing and saving, demonstrates how cloud administrators manage and update stored content in real time without needing to download and re-upload files. This mirrors how businesses manage configuration files, logs and documentation stored in Azure Blob Storage.

## Step 5: Resource Group Deletion Confirmation

<p align="center">
<img src="https://github.com/user-attachments/assets/093554ed-7ba7-4735-8ce3-5274fedf556b" alt="Resource Group Deletion Confirmation" width="80%"/>
</p>

Initiated and confirmed the deletion of the Re.1Group Resource Group and all dependent resources including the Storage Account and all containers. Proper cloud resource cleanup is a critical and valued skill in any cloud environment, unmanaged resources accumulate charges daily and cost businesses thousands in unnecessary spend monthly. Consistently practicing this discipline reflects the cost-conscious approach required of cloud administrators and engineers managing business infrastructure at scale.

# Key Skills Demonstrated

* Microsoft Azure: Resource Group and Storage Account provisioning
* Azure Blob Storage: container creation and file management
* Cloud Portal Navigation: creating, editing and managing resources in the Azure Portal
* File Management in the Cloud: uploading, editing and downloading blob files
* Cloud Cost Management: resource deletion and Cost Analysis review
* Cloud Resource Organization: logical grouping of assets using Resource Groups
* Technical Documentation: step by step lab documentation with visual proof of work

# Business Applications

Cloud storage is the backbone of modern business operations. Every organization that uses cloud infrastructure relies on the same foundational concepts demonstrated in this project, Resource Groups to organize assets, Storage Accounts to house data, and blob containers to store everything from customer files to application backups to compliance documents. By provisioning and managing these resources hands on, this project demonstrates the ability to build and maintain the storage infrastructure that businesses depend on daily. The cost management aspect is equally critical, cloud spend is one of the largest and most controllable IT costs in any organization, and professionals who understand how to provision resources responsibly and clean up after themselves are consistently more valued than those who do not.

# Lessons Learned

This project established the foundational understanding of how cloud infrastructure is organized and managed in Microsoft Azure. The most important takeaway was not just how to create resources but understanding why they are structured the way they are, Resource Groups exist to give businesses visibility and control over their cloud spend, Storage Accounts provide a scalable and secure home for data, and blob containers allow organizations to organize that data in a way that mirrors their operational needs. Practicing resource deletion at the end reinforced that cloud management is not just about building, it is about maintaining, optimizing and cleaning up responsibly. These habits built at the foundational level carry directly into more complex cloud engineering work.
