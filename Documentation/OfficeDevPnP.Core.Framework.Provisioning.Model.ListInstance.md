# ListInstance
This class holds deprecated ListInstance properties and methods  

**Namespace:** [OfficeDevPnP.Core.Framework.Provisioning.Model](OfficeDevPnP.Core.Framework.Provisioning.Model.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Inheritance Hierarchy
System.Object  
-- [OfficeDevPnP.Core.Framework.Provisioning.Model.BaseModel](OfficeDevPnP.Core.Framework.Provisioning.Model.BaseModel.md)
## Syntax
```C#
public class ListInstance: BaseModel
```
## Constructors
|**Name**|**Description**|
|:-----|:-----|
| [ListInstance()](OfficeDevPnP.Core.Framework.Provisioning.Model.ListInstance.Constructor1details.md) | 
| [ListInstance(IEnumerable<ContentTypeBinding>, IEnumerable<View>, IEnumerable<Field>, IEnumerable<FieldRef>, List<DataRow>)](OfficeDevPnP.Core.Framework.Provisioning.Model.ListInstance.Constructor2details.md) | 
| [ListInstance(IEnumerable<ContentTypeBinding>, IEnumerable<View>, IEnumerable<Field>, IEnumerable<FieldRef>, List<DataRow>, Dictionary<String, String>, ObjectSecurity)](OfficeDevPnP.Core.Framework.Provisioning.Model.ListInstance.Constructor3details.md) | 
| [ListInstance(IEnumerable<ContentTypeBinding>, IEnumerable<View>, IEnumerable<Field>, IEnumerable<FieldRef>, List<DataRow>, Dictionary<String, String>, ObjectSecurity, List<Folder>)](OfficeDevPnP.Core.Framework.Provisioning.Model.ListInstance.Constructor4details.md) | 
| [ListInstance(IEnumerable<ContentTypeBinding>, IEnumerable<View>, IEnumerable<Field>, IEnumerable<FieldRef>, List<DataRow>, Dictionary<String, String>, ObjectSecurity, List<Folder>, List<CustomAction>)](OfficeDevPnP.Core.Framework.Provisioning.Model.ListInstance.Constructor5details.md) | 
## Properties
|**Name**|**Description**|
|:-----|:-----|
| [Title](OfficeDevPnP.Core.Framework.Provisioning.Model.ListInstance.Title.md) | Gets or sets the list title
| [Description](OfficeDevPnP.Core.Framework.Provisioning.Model.ListInstance.Description.md) | Gets or sets the description of the list
| [DocumentTemplate](OfficeDevPnP.Core.Framework.Provisioning.Model.ListInstance.DocumentTemplate.md) | Gets or sets a value that specifies the identifier of the document template for the new list.
| [OnQuickLaunch](OfficeDevPnP.Core.Framework.Provisioning.Model.ListInstance.OnQuickLaunch.md) | Gets or sets a value that specifies whether the new list is displayed on the Quick Launch of the site.
| [TemplateType](OfficeDevPnP.Core.Framework.Provisioning.Model.ListInstance.TemplateType.md) | Gets or sets a value that specifies the list server template of the new list. https://msdn.microsoft.com/en-us/library/office/microsoft.sharepoint.client.listtemplatetype.aspx
| [Url](OfficeDevPnP.Core.Framework.Provisioning.Model.ListInstance.Url.md) | Gets or sets a value that specifies whether the new list is displayed on the Quick Launch of the site.
| [EnableVersioning](OfficeDevPnP.Core.Framework.Provisioning.Model.ListInstance.EnableVersioning.md) | Gets or sets whether verisioning is enabled on the list
| [EnableMinorVersions](OfficeDevPnP.Core.Framework.Provisioning.Model.ListInstance.EnableMinorVersions.md) | Gets or sets whether minor verisioning is enabled on the list
| [DraftVersionVisibility](OfficeDevPnP.Core.Framework.Provisioning.Model.ListInstance.DraftVersionVisibility.md) | Gets or sets the DraftVersionVisibility for the list
| [EnableModeration](OfficeDevPnP.Core.Framework.Provisioning.Model.ListInstance.EnableModeration.md) | Gets or sets whether moderation/content approval is enabled on the list
| [MinorVersionLimit](OfficeDevPnP.Core.Framework.Provisioning.Model.ListInstance.MinorVersionLimit.md) | Gets or sets the MinorVersionLimit for versioning, just in case it is enabled on the list
| [MaxVersionLimit](OfficeDevPnP.Core.Framework.Provisioning.Model.ListInstance.MaxVersionLimit.md) | Gets or sets the MinorVersionLimit for verisioning, just in case it is enabled on the list
| [RemoveExistingContentTypes](OfficeDevPnP.Core.Framework.Provisioning.Model.ListInstance.RemoveExistingContentTypes.md) | Gets or sets whether existing content types should be removed
| [RemoveExistingViews](OfficeDevPnP.Core.Framework.Provisioning.Model.ListInstance.RemoveExistingViews.md) | Gets or sets whether existing views should be removed
| [ContentTypesEnabled](OfficeDevPnP.Core.Framework.Provisioning.Model.ListInstance.ContentTypesEnabled.md) | Gets or sets whether content types are enabled
| [Hidden](OfficeDevPnP.Core.Framework.Provisioning.Model.ListInstance.Hidden.md) | Gets or sets whether to hide the list
| [ForceCheckout](OfficeDevPnP.Core.Framework.Provisioning.Model.ListInstance.ForceCheckout.md) | Gets or sets whether to force checkout of documents in the library
| [EnableAttachments](OfficeDevPnP.Core.Framework.Provisioning.Model.ListInstance.EnableAttachments.md) | Gets or sets whether attachments are enabled. Defaults to true.
| [EnableFolderCreation](OfficeDevPnP.Core.Framework.Provisioning.Model.ListInstance.EnableFolderCreation.md) | Gets or sets whether folder is enabled. Defaults to true.
| [ContentTypeBindings](OfficeDevPnP.Core.Framework.Provisioning.Model.ListInstance.ContentTypeBindings.md) | Gets or sets the content types to associate to the list
| [Views](OfficeDevPnP.Core.Framework.Provisioning.Model.ListInstance.Views.md) | Gets or sets the content types to associate to the list
| [Fields](OfficeDevPnP.Core.Framework.Provisioning.Model.ListInstance.Fields.md) | 
| [FieldRefs](OfficeDevPnP.Core.Framework.Provisioning.Model.ListInstance.FieldRefs.md) | 
| [TemplateFeatureID](OfficeDevPnP.Core.Framework.Provisioning.Model.ListInstance.TemplateFeatureID.md) | 
| [DataRows](OfficeDevPnP.Core.Framework.Provisioning.Model.ListInstance.DataRows.md) | 
| [FieldDefaults](OfficeDevPnP.Core.Framework.Provisioning.Model.ListInstance.FieldDefaults.md) | Defines a list of default values for the Fields of the List Instance
| [Security](OfficeDevPnP.Core.Framework.Provisioning.Model.ListInstance.Security.md) | Defines the Security rules for the List Instance
| [Folders](OfficeDevPnP.Core.Framework.Provisioning.Model.ListInstance.Folders.md) | Defines a collection of folders (eventually nested) that will be provisioned into the target list/library
| [UserCustomActions](OfficeDevPnP.Core.Framework.Provisioning.Model.ListInstance.UserCustomActions.md) | Defines a collection of user custom actions that will be provisioned into the target list/library
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [GetHashCode()](OfficeDevPnP.Core.Framework.Provisioning.Model.ListInstance.GetHashCode.md) | 
| [Equals(Object)](OfficeDevPnP.Core.Framework.Provisioning.Model.ListInstance.EqualsObject.md) | 
| [Equals(ListInstance)](OfficeDevPnP.Core.Framework.Provisioning.Model.ListInstance.EqualsListInstance.md) | 
## See also
- [OfficeDevPnP.Core.Framework.Provisioning.Model](OfficeDevPnP.Core.Framework.Provisioning.Model.md)
