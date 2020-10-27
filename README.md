Deploy a Windows Azure Virtual Machine with Two Data Disks
==========================================================

            

[Windows Azure Scripting Center](http://www.windowsazure.com/en-us/documentation/scripts) |
[Get Started with Windows Azure PowerShell](http://go.microsoft.com/fwlink/?linkid=320929&clcid=0x409) |
[Windows Azure Infrastructure Scripts](http://www.windowsazure.com/en-us/documentation/scripts/index/?solution=infrastructure&service=all)

Description

Creates a Virtual Machine (small) configured with two data disks. After the Virtual Machine is provisioned and running, the data disks are then formatted and drive letters assigned. User is prompted for credentials to use to provision the new Virtual Machine.


**Note:** This script requires an Azure Storage Account to run. The storage account can be specified by setting the subscription configuration. For example,


Set-AzureSubscription -SubscriptionName 'MySubscription' -CurrentStorageAccount 'MyStorageAccount'

Example
 
Scenario
You want to provision a Virtual Machine with one or more data disks pre-formatted.
Requirements

  *  PowerShell Version 3.0 
  *  Windows Azure PowerShell 0.6.18 
See Also

  *  [Set-AzureSubscription](http://msdn.microsoft.com/en-us/library/windowsazure/dn408531.aspx)

  *  [Windows Azure Infrastructure Scripts](http://www.windowsazure.com/en-us/documentation/scripts/index/?solution=infrastructure&service=all)

Script Content

The content of the script is reproduced below

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
