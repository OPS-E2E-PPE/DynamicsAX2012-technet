﻿---
title: IRetailTransactionV1.AmountToAccount Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: AmountToAccount Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.AmountToAccount
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.iretailtransactionv1.amounttoaccount(v=AX.60)
ms:contentKeyID: 49845375
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.AmountToAccount
dev_langs:
- CSharp
- C++
- VB
---

# AmountToAccount Property

The total amount posted to customer account.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property AmountToAccount As Decimal
    Get
    Set
'Usage
Dim instance As IRetailTransactionV1
Dim value As Decimal

value = instance.AmountToAccount

instance.AmountToAccount = value
```

``` csharp
decimal AmountToAccount { get; set; }
```

``` c++
property Decimal AmountToAccount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[IRetailTransactionV1 Interface](iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)
