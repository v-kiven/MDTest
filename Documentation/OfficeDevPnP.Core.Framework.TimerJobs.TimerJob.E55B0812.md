String, String, String, SecureString# TimerJob.UseAzureADAppOnlyAuthentication members
Prepares the timerjob to operate against SharePoint Only with Azure AD app-only credentials. Sets AuthenticationType 
            to AuthenticationType.AzureADAppOnly  

**Namespace:** [OfficeDevPnP.Core.Framework.TimerJobs](OfficeDevPnP.Core.Framework.TimerJobs.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public void UseAzureADAppOnlyAuthentication(String, String, String, SecureString)
```
### Parameters
#### clientId
Type: [System.String](System.String.md) 
#### 
#### azureTenant
Type: [System.String](System.String.md) 
#### 
#### certificatePath
Type: [System.String](System.String.md) 
#### 
#### certificatePassword
Type: [System.Security.SecureString](System.Security.SecureString.md) 
#### 
### Return Value
Type: [System.Void](System.Void.md)## See also
- [OfficeDevPnP.Core.Framework.TimerJobs](OfficeDevPnP.Core.Framework.TimerJobs.md)