---
title: "CDBPropSet::SetGUID | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.technology: ["cpp-data"]
ms.topic: "reference"
f1_keywords: ["ATL.CDBPropSet.SetGUID", "CDBPropSet.SetGUID", "ATL::CDBPropSet::SetGUID", "SetGUID", "CDBPropSet::SetGUID"]
dev_langs: ["C++"]
helpviewer_keywords: ["SetGUID method", "AddProperty method"]
ms.assetid: a4cce036-cf1f-4897-9712-7b01eaf887ff
author: "mikeblome"
ms.author: "mblome"
ms.workload: ["cplusplus", "data-storage"]
---
# CDBPropSet::SetGUID
Sets the **guidPropertySet** field in the **DBPROPSET** structure.  
  
## Syntax  
  
```cpp
      void SetGUID(const GUID& guid) throw();  
```  
  
#### Parameters  
 `guid`  
 [in] A GUID used to set the **guidPropertySet** field of the [DBPROPSET](https://msdn.microsoft.com/en-us/library/ms714367.aspx) structure.  
  
## Remarks  
 This field can be set by the [constructor](../../data/oledb/cdbpropset-cdbpropset.md) as well.  
  
## Requirements  
 **Header:** atldbcli.h  
  
## See Also  
 [CDBPropSet Class](../../data/oledb/cdbpropset-class.md)