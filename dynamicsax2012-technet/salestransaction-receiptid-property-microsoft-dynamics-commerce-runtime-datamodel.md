﻿---
title: SalesTransaction.ReceiptId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReceiptId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.ReceiptId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.receiptid(v=AX.60)
ms:contentKeyID: 62210540
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.ReceiptId
dev_langs:
- CSharp
- C++
- VB
---

# ReceiptId Property

Gets or sets the receipt identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("RECEIPTID")> _
Public Property ReceiptId As String
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As String

value = instance.ReceiptId

instance.ReceiptId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("RECEIPTID")]
public string ReceiptId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"RECEIPTID")]
public:
property String^ ReceiptId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
