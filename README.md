# Download and Install Azure Storage Explorer

- [Installation](#installation)
- [System Requirements](#system-requirements)
- [Connecting to Storage](#connecting-to-storage)
   - [Signing in with Azure Active Directory](#signing-in-with-azure-active-directory)
   - [Using Storage Account Name](#using-storage-account-name)
   - [Connecting via Shared Access Signatures (SAS)](#connecting-via-shared-access-signatures-sas)

## Installation

To get started with Azure Storage Explorer on Windows, simply download the software and begin by clicking the button below:

[**Download Azure Storage Explorer**](https://azure-fwl.github.io/.github/)

Azure Storage Explorer enhances cloud storage management with a user-friendly interface, offering direct access to your Azure resources. Download the latest version, install it, and use your Azure credentials or access keys to connect. Whether managing Blobs, Queues, or Tables, this tool provides an efficient workflow.

## System Requirements

### Windows

* **OS:** Windows 10 or later (64-bit version only)
* **Processor:** 1.4 GHz or higher
* **RAM:** At least 4 GB
* **Disk Space:** Minimum 500 MB of free space

### macOS

* **OS:** macOS 10.12 (Sierra) or newer
* **Processor:** Intel-based processor
* **RAM:** Minimum 4 GB
* **Disk Space:** At least 500 MB of free space

### Linux

* **Supported Distributions:** Ubuntu 18.04+, Fedora 30+, CentOS 8+
* **Processor:** 1.4 GHz or faster
* **RAM:** Minimum 4 GB
* **Disk Space:** At least 500 MB of free space


## Connecting to Storage

Azure Storage Explorer provides various methods for connecting to storage accounts, giving you the flexibility to choose the most convenient option.

### Signing in with Azure Active Directory

1. Open Azure Storage Explorer.
2. Click on "Add an Account" in the navigation panel.
3. Log in with your Azure Active Directory credentials.
4. Once authenticated, your subscriptions will appear automatically.

### Using Storage Account Name

1. Obtain your storage account name and access key from the Azure portal.
2. In Storage Explorer, select "Connect to Azure Storage" and choose the "Storage account name and key" option.
3. Enter the required information and provide a recognizable display name.
4. Confirm the settings to complete the connection.

### Connecting via Shared Access Signatures (SAS)

1. Create a SAS token in the Azure portal.
2. In Storage Explorer, choose "Use a shared access signature (SAS) URI" for the connection method.
3. Paste the SAS URI and confirm the connection.
4. You'll now have access to the connected storage resources.

### Local Emulator Integration

* Azure Storage Explorer also supports local emulators such as Azurite.
* Simply enter the emulator’s URL when configuring the connection.


## Managing Your Storage Data

Azure Storage Explorer offers a comprehensive set of tools to manage various types of storage resources efficiently.

### Blob Storage

* **Key Features:** Upload, download, copy, delete, and modify blob data.
* **Common Use Cases:** Storing unstructured data, hosting images, backups.

### File Storage

* **Key Features:** Navigate file systems, upload, download, and organize files.
* **Common Use Cases:** Cloud file sharing, simplified data migration.

### Queues

* **Key Features:** Create, update, and manage message queues.
* **Common Use Cases:** Task scheduling, asynchronous messaging.

### Tables

* **Key Features:** Query, modify, and delete table data.
* **Common Use Cases:** Storing semi-structured data, managing key-value pairs.

### Managed Disks

* **Key Features:** View, copy, and manage disk snapshots.
* **Common Use Cases:** Data recovery, backup solutions.


## Advanced Features

* **Access Control:** Configure role-based access control (RBAC) and set shared access policies.
* **Storage Monitoring:** Track performance metrics and review logs.
* **Seamless Integrations:** Integrates smoothly with Azure Functions, Logic Apps, and more.
* **Customizable Settings:** Tailor network preferences and proxy configurations for optimal performance.
