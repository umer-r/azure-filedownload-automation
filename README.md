![GitHub](https://img.shields.io/github/license/umer-r/azure-filedownload-automation) ![GitHub top language](https://img.shields.io/github/languages/top/umer-r/azure-filedownload-automation) ![GitHub commit activity](https://img.shields.io/github/commit-activity/m/umer-r/azure-filedownload-automation)

# Azure (File Download) Automation Script
***PowerShell Script to download a file from Azure Storage Share with Thumbprint certificate-based Authentication.***

## Usage

### Define variables:

Prior to running the script please ensure to set the following variables accordingly in [File](AzCertConnectDownload.ps1).

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

## Connect with Me 🤝🏻 &nbsp;

<p align="center">
<a href="https://www.linkedin.com/in/umer-r-437120214/"><img src="https://img.shields.io/badge/-Umer%20R-0077B5?style=flat&logo=Linkedin&logoColor=white"/></a>
<a href="mailto:russs3400@gmail.com"><img src="https://img.shields.io/badge/-Umer R-D14836?style=flat&logo=Gmail&logoColor=white"/></a>
<a href="https://instagram.com/umer_r74"><img src="https://img.shields.io/badge/-@umer__r74-E4405F?style=flat&logo=Instagram&logoColor=white"/></a>
<a href="https://twitter.com/umer_74"><img src="https://img.shields.io/badge/-@umer__74-1877F2?style=flat&logo=Twitter&logoColor=white"/></a>
</p>

### Let's Talk about your project :smiley:

<p align="center">
<a href="https://www.upwork.com/freelancers/~011184505ed9059668"><img src="https://img.shields.io/badge/-Umer%20R-6fda44?style=flat&logo=upwork&logoColor=white"/></a>
<a href="https://www.fiverr.com/hamza_rajaz"><img src="https://img.shields.io/badge/-Umer%20R-00b22d?style=flat&logo=Fiverr&logoColor=white"/></a>

</p>