﻿# windows10AssociatedApps resource type> **Note:** Using the Microsoft Graph APIs to configure Intune controls and policies still requires that the Intune service is [correctly licensed](https://www.microsoft.com/en-us/cloud-platform/microsoft-intune-pricing) by the customer.

Windows 10 Associated Application definition.
### Properties
|Property|Type|Description|
|---|---|---|
|appType|String|Application type. Possible values are: `desktop`, `universal`.|
|identifier|String|Identifier.|

### Relationships
None
### JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.windows10AssociatedApps"
}
-->
```json
{
  "@odata.type": "#microsoft.graph.windows10AssociatedApps",
  "appType": "String",
  "identifier": "String"
}
```



