---
title: "CDynamicAccessor::GetBlobSizeLimit | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: ["cpp-windows"]
ms.tgt_pltfrm: ""
ms.topic: "reference"
f1_keywords: ["ATL::CDynamicAccessor::GetBlobSizeLimit", "CDynamicAccessor.GetBlobSizeLimit", "CDynamicAccessor::GetBlobSizeLimit", "GetBlobSizeLimit", "ATL.CDynamicAccessor.GetBlobSizeLimit"]
dev_langs: ["C++"]
helpviewer_keywords: ["GetBlobSizeLimit method"]
ms.assetid: 7131e7c4-6e05-42f3-9d87-110301b672f2
caps.latest.revision: 8
author: "mikeblome"
ms.author: "mblome"
manager: "ghogen"
ms.workload: ["cplusplus", "data-storage"]
---
# CDynamicAccessor::GetBlobSizeLimit
Retrieves the maximum BLOB size in bytes.  
  
## Syntax  
  
```cpp
const DBLENGTH GetBlobSizeLimit() const;  
  
```  
  
## Remarks  
 Returns the BLOB handling value `nBlobSize` as set by [SetBlobSizeLimit](../../data/oledb/cdynamicaccessor-setblobsizelimit.md).  
  
## Requirements  
 **Header:** atldbcli.h  
  
## See Also  
 [CDynamicAccessor Class](../../data/oledb/cdynamicaccessor-class.md)