# ProvisioningTemplateApplyingInformation
  

**Namespace:** [OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers](OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Inheritance Hierarchy
System.Object  
## Syntax
```C#
public class ProvisioningTemplateApplyingInformation
```
## Constructors
|**Name**|**Description**|
|:-----|:-----|
| [ProvisioningTemplateApplyingInformation()](OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.ProvisioningTemplateApplyingInformation.Constructor1details.md) | 
## Properties
|**Name**|**Description**|
|:-----|:-----|
| [ProgressDelegate](OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.ProvisioningTemplateApplyingInformation.ProgressDelegate.md) | 
| [MessagesDelegate](OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.ProvisioningTemplateApplyingInformation.MessagesDelegate.md) | 
| [PersistTemplateInfo](OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.ProvisioningTemplateApplyingInformation.PersistTemplateInfo.md) | 
| [OverwriteSystemPropertyBagValues](OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.ProvisioningTemplateApplyingInformation.OverwriteSystemPropertyBagValues.md) | If true, system propertybag entries that start with _, vti_, dlc_ etc. will be overwritten if overwrite = true on the PropertyBagEntry. If not true those keys will be skipped, regardless of the overwrite property of the entry.
| [ClearNavigation](OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.ProvisioningTemplateApplyingInformation.ClearNavigation.md) | If true, existing navigation nodes of the site (where applicable) will be cleared out before applying the navigation nodes from the template (if any). This setting will override any settings made in the template.
| [IgnoreDuplicateDataRowErrors](OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.ProvisioningTemplateApplyingInformation.IgnoreDuplicateDataRowErrors.md) | If true then duplicate id errors when the same importing datarows simply generate a warning don't stop the engine. Reason for this is being able to apply the same template multiple times (Delta handling) without that failing cause the same record is being added twice
| [ProvisionContentTypesToSubWebs](OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.ProvisioningTemplateApplyingInformation.ProvisionContentTypesToSubWebs.md) | If true then any content types in the template will be provisioned to subwebs
| [HandlersToProcess](OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.ProvisioningTemplateApplyingInformation.HandlersToProcess.md) | 
| [ExtensibilityHandlers](OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.ProvisioningTemplateApplyingInformation.ExtensibilityHandlers.md) | 
## See also
- [OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers](OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.md)
