﻿---
title: Listing.ProductDetailsJson Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ProductDetailsJson Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Listing.ProductDetailsJson
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.listing.productdetailsjson(v=AX.60)
ms:contentKeyID: 62207135
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Listing.ProductDetailsJson
dev_langs:
- CSharp
- C++
- VB
---

# ProductDetailsJson Property

The product details in json format.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ProductDetailsJson As String
    Get
    Set
'Usage
Dim instance As Listing
Dim value As String

value = instance.ProductDetailsJson

instance.ProductDetailsJson = value
```

``` csharp
[DataMemberAttribute]
public string ProductDetailsJson { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ProductDetailsJson {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[Listing Class](listing-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)
