﻿---
title: EmployeeActivity Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EmployeeActivity Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivity
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.employeeactivity(v=AX.60)
ms:contentKeyID: 62214938
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivity
dev_langs:
- CSharp
- C++
- VB
---

# EmployeeActivity Class

Represents a employee activities.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DefaultSortOrderAttribute(ColumnName := "REGDATETIME", IsDescending := True)> _
<DataContractAttribute> _
Public Class EmployeeActivity _
    Inherits CommerceEntity
'Usage
Dim instance As EmployeeActivity
```

``` csharp
[DefaultSortOrderAttribute(ColumnName = "REGDATETIME", IsDescending = true)]
[DataContractAttribute]
public class EmployeeActivity : CommerceEntity
```

``` c++
[DefaultSortOrderAttribute(ColumnName = L"REGDATETIME", IsDescending = true)]
[DataContractAttribute]
public ref class EmployeeActivity : public CommerceEntity
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
    Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivity  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
