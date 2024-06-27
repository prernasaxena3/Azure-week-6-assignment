# Azure-week-6-assignment

Link for deployed webapp on azure Link: prernatest123.azurewebsites.net

Steps to Complete the Assignment

1. Creating a Storage Account

Create an Azure Storage Account:

I logged into the Azure portal and navigated to the "Storage accounts" section.
I clicked "Create" and filled out the necessary details, such as resource group, storage account name, region, and performance (Standard or Premium).

Explore Storage Account Options:

During creation, I explored various options including redundancy (LRS, GRS, RA-GRS, ZRS), access tiers (Hot, Cool, Archive), and advanced options (data protection, encryption, networking).

2. Uploading and Accessing Blobs

Upload a Blob:

I created a container within the storage account and uploaded a blob using the Azure portal.

Access the Blob:

I accessed the uploaded blob through the portal and verified its accessibility via URL.

3. Authentication Techniques

Go Through Different Authentication Techniques:

I learned about different authentication methods like Azure AD, Shared Key, and SAS tokens.

Test Authentication Techniques:

I tested these methods by accessing the blob using each technique and verified the permissions.

4. Azure Storage Explorer

Try Azure Storage Explorer:

I installed Azure Storage Explorer and connected it to my storage account using the provided connection string and access keys.
I explored the interface, uploaded, downloaded, and managed blobs.

5. Provisioning Access Keys

Provision Access Keys:

I accessed the storage account's settings to find the access keys.
I used these keys to connect to the storage account via Azure Storage Explorer and other tools.

6. Shared Access Signature (SAS)

Create a Shared Access Signature:

I generated a SAS token with specific permissions and an expiration time.
I tested the SAS token by accessing the blob with the generated URL.

Create a Stored Access Policy:

I created a stored access policy for the container and associated it with a SAS token.
I verified the access scope by testing the SAS token.

7. Access Tiers and Lifecycle Policies

Learn About Different Access Tiers:

I explored the Hot, Cool, and Archive access tiers and their use cases.

Apply Lifecycle Policy:

I created a lifecycle management policy to move blobs between tiers based on their age.
I tested the policy by checking if blobs moved according to the defined rules.

8. Object Replication in Blob Storage

Test Object Replication:

I set up object replication between two storage accounts.
I verified the replication by uploading a blob to the source account and ensuring it appeared in the destination account.

9. File Share and Azure File Sync

Create a File Share:

I created a file share in the storage account and tested its functionality by uploading and accessing files.

Create an Azure File Sync:

I set up Azure File Sync to synchronize files between on-premises servers and the Azure file share.
I tested the synchronization by making changes to the files and observing the updates in both locations.
