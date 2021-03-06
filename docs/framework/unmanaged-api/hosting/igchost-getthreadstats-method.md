---
title: "IGCHost::GetThreadStats Method | Microsoft Docs"
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
  - "IGCHost.GetThreadStats"
apilocation: 
  - "mscoree.dll"
apitype: "COM"
f1_keywords: 
  - "GetThreadStats"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "IGCHost::GetThreadStats method [.NET Framework hosting]"
  - "GetThreadStats method [.NET Framework hosting]"
ms.assetid: 826baa9b-9218-4736-a509-7ab193b125a0
caps.latest.revision: 8
author: "rpetrusha"
ms.author: "ronpet"
manager: "wpickett"
---
# IGCHost::GetThreadStats Method
Gets the per-thread statistics for garbage collection.  
  
## Syntax  
  
```  
HRESULT GetThreadStats (  
    [in] DWORD *pFiberCookie,  
    [in, out] COR_GC_THREAD_STATS *pStats  
);  
```  
  
#### Parameters  
 `pFiberCookie`  
 [in] A pointer to a fiber cookie that specifies the thread for which to retrieve the statistics.  
  
 `pStats`  
 [in, out] A pointer to a [COR_GC_THREAD_STATS](../../../../docs/framework/unmanaged-api/hosting/cor-gc-thread-stats-structure.md) structure that contains the garbage collection statistics for the specified thread.  
  
## Requirements  
 **Platforms:** See [System Requirements](../../../../docs/framework/get-started/system-requirements.md).  
  
 **Header:** GCHost.idl, GCHost.h  
  
 **Library:** Included as a resource in MSCorEE.dll  
  
 **.NET Framework Versions:** [!INCLUDE[net_current_v20plus](../../../../includes/net-current-v20plus-md.md)]  
  
## See Also  
 [IGCHost Interface](../../../../docs/framework/unmanaged-api/hosting/igchost-interface.md)