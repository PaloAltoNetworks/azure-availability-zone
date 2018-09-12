![alt_text](https://github.com/PaloAltoNetworks/Azure-Transit-VNet/blob/master/Azure-Transit-VNET-1.1/documentation/images/pan-logo-badge-green-dark-kick-up.png "logo")


# VM-Series in Azure with Availability Zones


This template deploys a VM-Series firewall in Azure with Availability Zones. Any customization requirements can be accomplished by cloning the GitHub repo to your desktop. For more information on Azure Availability Zones please reference the link below. 

What are Availability Zones in Azure
https://docs.microsoft.com/en-us/azure/availability-zones/az-overview


This Template consists of
-   1 Resource Group
-	1 VM-Series Firewall in an availability Zone
-	1 Virtual Network
-	3 Subnets MGT, Untrust and Trust
-	2 Public IP Addresses both in Availability Zones
-	1 Network Security Group for management access


[<img src="http://azuredeploy.net/deploybutton.png"/>](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FPaloAltoNetworks%2Fazure-availability-zone%2Fmaster%2FazureDeploy.json?token=AZoiWUdo2qPkcTjMXpY8_KOkrP2aBqp_ks5ahJwcwA%3D%3D)



# Support Policy: Community-Supported
The code and templates in this repository are released under an as-is, best effort, support policy. These scripts should viewed as community supported and Palo Alto Networks will contribute our expertise as and when possible. We do not provide technical support or help in using or troubleshooting the components of the project through our normal support options such as Palo Alto Networks support teams, or ASC (Authorized Support Centers) partners and backline support options. The underlying product used (the VM-Series firewall) by the scripts or templates are still supported, but the support is only for the product functionality and not for help in deploying or using the template or script itself. Unless explicitly tagged, all projects or work posted in our GitHub repository (at https://github.com/PaloAltoNetworks) or sites other than our official Downloads page on https://support.paloaltonetworks.com are provided under the best effort policy.

