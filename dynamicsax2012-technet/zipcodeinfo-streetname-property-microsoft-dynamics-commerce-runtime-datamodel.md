﻿---
title: ZipCodeInfo.StreetName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StreetName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ZipCodeInfo.StreetName
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.zipcodeinfo.streetname(v=AX.60)
ms:contentKeyID: 49826202
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ZipCodeInfo.StreetName
dev_langs:
- CSharp
- C++
- VB
---

# StreetName Property

Gets or sets the name of the street.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("STREETNAME")> _
<DataMemberAttribute> _
Public Property StreetName As String
    Get
    Set
'Usage
Dim instance As ZipCodeInfo
Dim value As String

value = instance.StreetName

instance.StreetName = value
```

``` csharp
[ColumnAttribute("STREETNAME")]
[DataMemberAttribute]
public string StreetName { get; set; }
```

``` c++
[ColumnAttribute(L"STREETNAME")]
[DataMemberAttribute]
public:
property String^ StreetName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ZipCodeInfo Class](zipcodeinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
