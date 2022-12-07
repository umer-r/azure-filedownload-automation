![GitHub](https://img.shields.io/github/license/umer-r/azure-filedownload-automation) ![GitHub top language](https://img.shields.io/github/languages/top/umer-r/azure-filedownload-automation) ![GitHub commit activity](https://img.shields.io/github/commit-activity/m/umer-r/azure-filedownload-automation)

# Azure (File Download) Automation Script
***PowerShell Script to download a file from Azure Storage Share without opening the access prompt***

## Usage

### Define variables:

Prior to running the script please ensure to set the following variables accordingly in [file](AzCertConnectDownload.ps1)

**Connection details**
- ***TenantID*** = [Find your azure Tenant ID](https://learn.microsoft.com/en-us/azure/active-directory/fundamentals/active-directory-how-to-find-tenant)
- ***AppID*** = [Find your Azure App ID](https://forum.tufin.com/support/kc/latest/Content/Suite/10864.htm)
- ***thumbprint*** = [Generate your App Thumbprint certificate](https://learn.microsoft.com/en-us/azure/app-service/configure-ssl-certificate-in-code)

**Predefined variables**
- ***StorageAccountName*** = Your Storage Account's name where the file is stored.
- ***ResourceGroupName*** = Your Resource Group name.
- ***DestinationPath*** = Local path to save file on host.
- ***DownloadFilePath*** = File path to download.
- ***StorageAccountKey*** = [Find your Storage Account key](https://learn.microsoft.com/en-us/azure/storage/common/storage-account-keys-manage?tabs=azure-portal)


#### Unblock, Set execution policy and run setup.ps1:

```powershell
  # Download project
  git clone https://github.com/umer-r/azure-filedownload-automation.git
  cd azure-filedownload-automation
  # Unblock and set execution policy bypass
  Unblock-File -Path .\AzCertConnectDownload.ps1; PowerShell -ExecutionPolicy Bypass -File ".\AzCertConnectDownload.ps1"
  # Run File
  .\AzCertConnectDownload.ps1
```

# Contact

- [Gmail](mailto:russs3400@gmail.com)
- [LinkedIn](https://www.linkedin.com/in/umer-mehmood-437120214/)
- [Upwork](https://www.upwork.com/o/profiles/users/~011184505ed9059668/)
- [Fiverr](https://www.fiverr.com/hamza_rajaz)

Made with :heart: by [Umer](https://twitter.com/UmerMehmood_)