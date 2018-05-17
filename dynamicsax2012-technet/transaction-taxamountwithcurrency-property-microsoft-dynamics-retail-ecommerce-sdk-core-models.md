﻿---
title: Transaction.TaxAmountWithCurrency Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models)
TOCTitle: TaxAmountWithCurrency Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Transaction.TaxAmountWithCurrency
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.models.transaction.taxamountwithcurrency(v=AX.60)
ms:contentKeyID: 65316021
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Transaction.TaxAmountWithCurrency
dev_langs:
- CSharp
- C++
- VB
---

# TaxAmountWithCurrency Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TaxAmountWithCurrency As String
    Get
    Set
'Usage
Dim instance As Transaction
Dim value As String

value = instance.TaxAmountWithCurrency

instance.TaxAmountWithCurrency = value
```

``` csharp
[DataMemberAttribute]
public string TaxAmountWithCurrency { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ TaxAmountWithCurrency {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[Transaction Class](transaction-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)
