﻿---
title: PurgeOfflineTransactionsRequest.TransactionIds Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: TransactionIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.PurgeOfflineTransactionsRequest.TransactionIds
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.purgeofflinetransactionsrequest.transactionids(v=AX.60)
ms:contentKeyID: 65321511
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.PurgeOfflineTransactionsRequest.TransactionIds
dev_langs:
- CSharp
- C++
- VB
---

# TransactionIds Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TransactionIds As IEnumerable(Of String)
    Get
    Private Set
'Usage
Dim instance As PurgeOfflineTransactionsRequest
Dim value As IEnumerable(Of String)

value = instance.TransactionIds
```

``` csharp
[DataMemberAttribute]
public IEnumerable<string> TransactionIds { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<String^>^ TransactionIds {
    IEnumerable<String^>^ get ();
    private: void set (IEnumerable<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  

## See Also

#### Reference

[PurgeOfflineTransactionsRequest Class](purgeofflinetransactionsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

