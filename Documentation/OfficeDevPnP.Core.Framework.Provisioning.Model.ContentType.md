# ContentType
  

**Namespace:** [OfficeDevPnP.Core.Framework.Provisioning.Model](OfficeDevPnP.Core.Framework.Provisioning.Model.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Inheritance Hierarchy
System.Object  
-- [OfficeDevPnP.Core.Framework.Provisioning.Model.BaseModel](OfficeDevPnP.Core.Framework.Provisioning.Model.BaseModel.md)
## Syntax
```C#
public class ContentType: BaseModel
```
## Constructors
|**Name**|**Description**|
|:-----|:-----|
| [ContentType()](OfficeDevPnP.Core.Framework.Provisioning.Model.ContentType.Constructor1details.md) | 
| [ContentType(String, String, String, String, Boolean, Boolean, Boolean, String, Boolean, IEnumerable<FieldRef>)](OfficeDevPnP.Core.Framework.Provisioning.Model.ContentType.Constructor2details.md) | 
## Properties
|**Name**|**Description**|
|:-----|:-----|
| [Id](OfficeDevPnP.Core.Framework.Provisioning.Model.ContentType.Id.md) | The Id of the Content Type
| [Name](OfficeDevPnP.Core.Framework.Provisioning.Model.ContentType.Name.md) | The name of the Content Type
| [Description](OfficeDevPnP.Core.Framework.Provisioning.Model.ContentType.Description.md) | The description of the Content Type
| [Group](OfficeDevPnP.Core.Framework.Provisioning.Model.ContentType.Group.md) | The group name of the content type
| [FieldRefs](OfficeDevPnP.Core.Framework.Provisioning.Model.ContentType.FieldRefs.md) | The FieldRefs entries of the List Instance
| [Hidden](OfficeDevPnP.Core.Framework.Provisioning.Model.ContentType.Hidden.md) | True to define the content type as hidden. If you define a content type as hidden, SharePoint Foundation does not display that content type on the New button in list views.
| [Sealed](OfficeDevPnP.Core.Framework.Provisioning.Model.ContentType.Sealed.md) | True to prevent changes to this content type. You cannot change the value of this attribute through the user interface, but you can change it in code if you have sufficient rights. You must have site collection administrator rights to unseal a content type.
| [ReadOnly](OfficeDevPnP.Core.Framework.Provisioning.Model.ContentType.ReadOnly.md) | True to specify that the content type cannot be edited without explicitly removing the read-only setting. This can be done either in the user interface or in code.
| [Overwrite](OfficeDevPnP.Core.Framework.Provisioning.Model.ContentType.Overwrite.md) | True to overwrite an existing content type with the same ID.
| [DocumentTemplate](OfficeDevPnP.Core.Framework.Provisioning.Model.ContentType.DocumentTemplate.md) | Specifies the document template for the content type
| [DocumentSetTemplate](OfficeDevPnP.Core.Framework.Provisioning.Model.ContentType.DocumentSetTemplate.md) | Specifies the properties of the DocumentSet Template if the ContentType defines a DocumentSet
| [DisplayFormUrl](OfficeDevPnP.Core.Framework.Provisioning.Model.ContentType.DisplayFormUrl.md) | Specifies the URL of a custom display form to use for list items that have been assigned the content type
| [EditFormUrl](OfficeDevPnP.Core.Framework.Provisioning.Model.ContentType.EditFormUrl.md) | Specifies the URL of a custom edit form to use for list items that have been assigned the content type
| [NewFormUrl](OfficeDevPnP.Core.Framework.Provisioning.Model.ContentType.NewFormUrl.md) | Specifies the URL of a custom new form to use for list items that have been assigned the content type
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [GetHashCode()](OfficeDevPnP.Core.Framework.Provisioning.Model.ContentType.GetHashCode.md) | 
| [Equals(Object)](OfficeDevPnP.Core.Framework.Provisioning.Model.ContentType.EqualsObject.md) | 
| [Equals(ContentType)](OfficeDevPnP.Core.Framework.Provisioning.Model.ContentType.EqualsContentType.md) | 
## See also
- [https://msdn.microsoft.com/en-us/library/office/ms463449.aspx](https://msdn.microsoft.com/en-us/library/office/ms463449.aspx)
- [OfficeDevPnP.Core.Framework.Provisioning.Model](OfficeDevPnP.Core.Framework.Provisioning.Model.md)
