﻿---
title: Transaction.DeliveryModeDescription Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models)
TOCTitle: DeliveryModeDescription Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Transaction.DeliveryModeDescription
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.models.transaction.deliverymodedescription(v=AX.60)
ms:contentKeyID: 65318719
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Transaction.DeliveryModeDescription
dev_langs:
- CSharp
- C++
- VB
---

# DeliveryModeDescription Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DeliveryModeDescription As String
    Get
    Set
'Usage
Dim instance As Transaction
Dim value As String

value = instance.DeliveryModeDescription

instance.DeliveryModeDescription = value
```

``` csharp
[DataMemberAttribute]
public string DeliveryModeDescription { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ DeliveryModeDescription {
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
