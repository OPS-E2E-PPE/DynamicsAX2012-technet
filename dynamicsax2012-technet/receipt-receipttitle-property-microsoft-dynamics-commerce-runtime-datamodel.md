﻿---
title: Receipt.ReceiptTitle Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReceiptTitle Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Receipt.ReceiptTitle
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.receipt.receipttitle(v=AX.60)
ms:contentKeyID: 62213657
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Receipt.ReceiptTitle
dev_langs:
- CSharp
- C++
- VB
---

# ReceiptTitle Property

Gets or sets the receipt title.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ReceiptTitle As String
    Get
    Set
'Usage
Dim instance As Receipt
Dim value As String

value = instance.ReceiptTitle

instance.ReceiptTitle = value
```

``` csharp
[DataMemberAttribute]
public string ReceiptTitle { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ReceiptTitle {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[Receipt Class](receipt-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
