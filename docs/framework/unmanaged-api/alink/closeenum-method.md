---
title: "CloseEnum Method | Microsoft Docs"
ms.custom: ""
ms.date: "03/30/2017"
ms.prod: ".net-framework-4.6"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "dotnet-clr"
ms.tgt_pltfrm: ""
ms.topic: "reference"
apiname: 
  - "CloseEnum"
  - "IALink.CloseEnum"
apilocation: 
  - "alink.dll"
apitype: "COM"
f1_keywords: 
  - "CloseEnum"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "CloseEnum method"
ms.assetid: aa4a091e-13fe-4264-91de-e12f1c767c87
caps.latest.revision: 4
author: "mairaw"
ms.author: "mairaw"
manager: "wpickett"
---
# CloseEnum Method
Closes the indicated enumeration and frees associated resources.  
  
## Syntax  
  
```  
HRESULT CloseEnum(  
    HALINKENUM hEnum  
) PURE;  
```  
  
#### Parameters  
 `hEnum`  
 Handle of enumeration to be closed.  
  
## Return Value  
 Returns S_OK if the method succeeds.  
  
## Requirements  
 Requires alink.h  
  
## See Also  
 [IALink Interface](../../../../docs/framework/unmanaged-api/alink/ialink-interface.md)   
 [IALink2 Interface](../../../../docs/framework/unmanaged-api/alink/ialink2-interface.md)   
 [ALink API](../../../../docs/framework/unmanaged-api/alink/index.md)