﻿---
title: ListingAvailableQuantity.ExtensionData Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ExtensionData Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ListingAvailableQuantity.ExtensionData
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.listingavailablequantity.extensiondata(v=AX.60)
ms:contentKeyID: 62205298
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ListingAvailableQuantity.ExtensionData
dev_langs:
- CSharp
- C++
- VB
---

# ExtensionData Property

Gets or sets the structure that contains extra data.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
Public Property ExtensionData As ExtensionDataObject
    Get
    Set
'Usage
Dim instance As ListingAvailableQuantity
Dim value As ExtensionDataObject

value = instance.ExtensionData

instance.ExtensionData = value
```

``` csharp
public ExtensionDataObject ExtensionData { get; set; }
```

``` c++
public:
virtual property ExtensionDataObject^ ExtensionData {
    ExtensionDataObject^ get () sealed;
    void set (ExtensionDataObject^ value) sealed;
}
```

#### Property Value

Type: [System.Runtime.Serialization.ExtensionDataObject](https://technet.microsoft.com/en-us/library/ms574816\(v=ax.60\))  
An [ExtensionDataObject](https://technet.microsoft.com/en-us/library/ms574816\(v=ax.60\)) that contains data that is not recognized as belonging to the data contract.  

#### Implements

[IExtensibleDataObject.ExtensionData](https://technet.microsoft.com/en-us/library/ms553662\(v=ax.60\))  

## See Also

#### Reference

[ListingAvailableQuantity Class](listingavailablequantity-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)
