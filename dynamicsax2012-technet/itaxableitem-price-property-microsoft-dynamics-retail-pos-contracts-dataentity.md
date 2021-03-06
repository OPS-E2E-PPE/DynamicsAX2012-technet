﻿---
title: ITaxableItem.Price Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Price Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem.Price
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.itaxableitem.price(v=AX.60)
ms:contentKeyID: 47128062
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem.Price
dev_langs:
- CSharp
- C++
- VB
---

# Price Property

Gets or sets the price.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property Price As Decimal
    Get
    Set
'Usage
Dim instance As ITaxableItem
Dim value As Decimal

value = instance.Price

instance.Price = value
```

``` csharp
decimal Price { get; set; }
```

``` c++
property Decimal Price {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
The price.  

## See Also

#### Reference

[ITaxableItem Interface](itaxableitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

