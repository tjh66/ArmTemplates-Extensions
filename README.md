# ArmTemplates-Extensions
## Use powershell below to deploy 

remember to change the path to where the json files are located and change the entries in the parameter file on location of vm and vm name

New-AzResourceGroupDeployment -Name loganalyticsdeployment -ResourceGroupName 'VMDEV01' -TemplateFile 'D:\AzureBluprints\vmextensions\latemplate.json' -TemplateParameterFile 'D:\AzureBluprints\vmextensions\laparam.json'
