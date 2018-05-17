﻿---
title: GiftCardRealtimeRequestBase Constructor (String, Decimal, String, Int64, String, String, String, String) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GiftCardRealtimeRequestBase Constructor (String, Decimal, String, Int64, String, String, String, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GiftCardRealtimeRequestBase.#ctor(System.String,System.Decimal,System.String,System.Int64,System.String,System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.giftcardrealtimerequestbase.giftcardrealtimerequestbase(v=AX.60)
ms:contentKeyID: 65315823
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GiftCardRealtimeRequestBase Constructor (String, Decimal, String, Int64, String, String, String, String)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Protected Sub New ( _
    giftCardId As String, _
    amount As Decimal, _
    currencyCode As String, _
    channelId As Long, _
    terminalId As String, _
    staffId As String, _
    transactionId As String, _
    receiptId As String _
)
'Usage
Dim giftCardId As String
Dim amount As Decimal
Dim currencyCode As String
Dim channelId As Long
Dim terminalId As String
Dim staffId As String
Dim transactionId As String
Dim receiptId As String

Dim instance As New GiftCardRealtimeRequestBase(giftCardId, _
    amount, currencyCode, channelId, _
    terminalId, staffId, transactionId, _
    receiptId)
```

``` csharp
protected GiftCardRealtimeRequestBase(
    string giftCardId,
    decimal amount,
    string currencyCode,
    long channelId,
    string terminalId,
    string staffId,
    string transactionId,
    string receiptId
)
```

``` c++
protected:
GiftCardRealtimeRequestBase(
    String^ giftCardId, 
    Decimal amount, 
    String^ currencyCode, 
    long long channelId, 
    String^ terminalId, 
    String^ staffId, 
    String^ transactionId, 
    String^ receiptId
)
```

#### Parameters

  - giftCardId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - amount  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - staffId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - transactionId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - receiptId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GiftCardRealtimeRequestBase Class](giftcardrealtimerequestbase-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GiftCardRealtimeRequestBase Overload](giftcardrealtimerequestbase-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)
