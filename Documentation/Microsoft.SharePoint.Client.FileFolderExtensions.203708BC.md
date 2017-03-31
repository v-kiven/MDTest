Folder, String, Stream, Boolean# FileFolderExtensions.UploadFile members
Uploads a file to the specified folder.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  UploadFile(Folder, String, Stream, Boolean)
```
### Parameters
#### folder
Type: [Microsoft.SharePoint.Client.Folder](Microsoft.SharePoint.Client.Folder.md) 
#### 
#### fileName
Type: [System.String](System.String.md) 
#### 
#### stream
Type: [System.IO.Stream](System.IO.Stream.md) 
#### 
#### overwriteIfExists
Type: [System.Boolean](System.Boolean.md) 
#### 
### Return Value
Type: [Microsoft.SharePoint.Client.File](Microsoft.SharePoint.Client.File.md)The uploaded File, so that additional operations (such as setting properties) can be done.
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)