Remove-AzureDeployment
======================

            

This Azure Automation shutdowns Azure Cloud Service (Web & Worker role) from specific slot and then removes deployment. This runbook needs AzureClassicRunAsConnection.


You can use this Runbook for example to shutdown your test environments outside office hours in order to reduce costs.


Use [Deploy-CloudServiceFromBlob](https://gallery.technet.microsoft.com/scriptcenter/Deploy-CloudServiceFromBlob-e68838cd) runbook to start Cloud Service again.


.............................................................................

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
