# Get the Data on Azure

The main idea is here: 

![](getthedata/1.png)

You may want to use the dataset in a virtual machine or with other services in Azure. 

If you need to use the dataset only in a virtual machine, you can just download the data in the virtual machine. Done!

You'll be able to install the tools you need and access the data on this VM's hard drive.

You can create a [Windows virtual machine](AzureWindows.md) or a [Linux virtual machine](AzureLinux.md).

If you want to leverage additional services like 
[Azure Machine Learning](AzureML.md), [Azure SQL DW](AzureSQLDW.md), or [Power BI](PowerBI.md) to name a few, 
you may also want to copy the data to an [Azure storage account](AzureStorage.md).

Note that, **if the bandwidth is good**, you can also copy from the source to Azure blob storage thru your laptop, without using an Azure VM. 

