# acora-iaas-demo
Demonstration of Azure ARM templates and complex environment creation.

This environment will create a single virtual network and storage account, plus three Windows 2012 R2 servers.  It will then apply custom actions to these services to install ADDS, ADCS, ADFS and WAP between the hosts.

RDP will be available via the PIP on the WAP server once the configuration has been completed.  Full unattended configuration of the environment takes approximately one hour.

Use the Scripts\Deploy-AzureRMResourceGroup.ps1 script to execute, or load the solution into VS2015 and Deploy.

