# Infrastructure


## Resource Groups

#### Create resource group

    az group create 
    --location northeurope 
    --name rg_ne_dev_myapi 
    --tags environment=dev application=payments


## Azure Active Directory
Docs:
https://docs.microsoft.com/en-us/cli/azure/ad?view=azure-cli-latest
#### Create app registration

    az ad app create --display-name <application-name>

#### List all app registrations
    az ad app list --query '[].{name: displayName, appId: appId}'
