List, String, String, EventReceiverType, EventReceiverSynchronization, Boolean# ListExtensions.AddRemoteEventReceiver members
Registers a remote event receiver  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  AddRemoteEventReceiver(List, String, String, EventReceiverType, EventReceiverSynchronization, Boolean)
```
### Parameters
#### list
Type: [Microsoft.SharePoint.Client.List](Microsoft.SharePoint.Client.List.md) 
#### 
#### name
Type: [System.String](System.String.md) 
#### 
#### url
Type: [System.String](System.String.md) 
#### 
#### eventReceiverType
Type: [Microsoft.SharePoint.Client.EventReceiverType](Microsoft.SharePoint.Client.EventReceiverType.md) 
#### 
#### synchronization
Type: [Microsoft.SharePoint.Client.EventReceiverSynchronization](Microsoft.SharePoint.Client.EventReceiverSynchronization.md) 
#### 
#### force
Type: [System.Boolean](System.Boolean.md) 
#### 
### Return Value
Type: [Microsoft.SharePoint.Client.EventReceiverDefinition](Microsoft.SharePoint.Client.EventReceiverDefinition.md)Returns an EventReceiverDefinition if succeeded. Returns null if failed.
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)