﻿---
title: IAuthorizationManager.TryReadCustomerMap Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Storefront)
TOCTitle: TryReadCustomerMap Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Storefront.IAuthorizationManager.TryReadCustomerMap(System.String,Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.UserCustomerMap@)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.storefront.iauthorizationmanager.tryreadcustomermap(v=AX.60)
ms:contentKeyID: 65316679
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Storefront.IAuthorizationManager.TryReadCustomerMap
dev_langs:
- CSharp
- C++
- VB
---

# TryReadCustomerMap Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Storefront](microsoft-dynamics-retail-ecommerce-sdk-core-storefront-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Function TryReadCustomerMap ( _
    userId As String, _
    <OutAttribute> ByRef userCustomerMap As UserCustomerMap _
) As Boolean
'Usage
Dim instance As IAuthorizationManager
Dim userId As String
Dim userCustomerMap As UserCustomerMap
Dim returnValue As Boolean

returnValue = instance.TryReadCustomerMap(userId, _
    userCustomerMap)
```

``` csharp
bool TryReadCustomerMap(
    string userId,
    out UserCustomerMap userCustomerMap
)
```

``` c++
bool TryReadCustomerMap(
    String^ userId, 
    [OutAttribute] UserCustomerMap^% userCustomerMap
)
```

#### Parameters

  - userId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - userCustomerMap  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.UserCustomerMap](usercustomermap-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[IAuthorizationManager Interface](iauthorizationmanager-interface-microsoft-dynamics-retail-ecommerce-sdk-core-storefront.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Storefront Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-storefront-namespace.md)
