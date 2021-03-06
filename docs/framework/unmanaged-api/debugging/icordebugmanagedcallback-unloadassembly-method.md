---
title: "ICorDebugManagedCallback::UnloadAssembly Method | Microsoft Docs"
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
  - "ICorDebugManagedCallback.UnloadAssembly"
apilocation: 
  - "mscordbi.dll"
apitype: "COM"
f1_keywords: 
  - "ICorDebugManagedCallback::UnloadAssembly"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "ICorDebugManagedCallback::UnloadAssembly method [.NET Framework debugging]"
  - "UnloadAssembly method [.NET Framework debugging]"
ms.assetid: 6734321c-c8a9-401f-a558-cad715ec4a77
caps.latest.revision: 14
author: "rpetrusha"
ms.author: "ronpet"
manager: "wpickett"
---
# ICorDebugManagedCallback::UnloadAssembly Method
Notifies the debugger that a common language runtime assembly has been unloaded.  
  
## Syntax  
  
```  
HRESULT UnloadAssembly (  
    [in] IcorDebugAppDomain  *pAppDomain,  
    [in] ICorDebugAssembly   *pAssembly  
);  
```  
  
#### Parameters  
 `pAppDomain`  
 [in] A pointer to an ICorDebugAppDomain object that represents the application domain that contained the assembly.  
  
 `pAssembly`  
 [in] A pointer to an ICorDebugAssembly object that represents the assembly.  
  
## Remarks  
 The assembly should not be used after this callback.  
  
## Requirements  
 **Platforms:** See [System Requirements](../../../../docs/framework/get-started/system-requirements.md).  
  
 **Header:** CorDebug.idl, CorDebug.h  
  
 **Library:** CorGuids.lib  
  
 **.NET Framework Versions:** [!INCLUDE[net_current_v10plus](../../../../includes/net-current-v10plus-md.md)]  
  
## See Also  
 [LoadAssembly Method](../../../../docs/framework/unmanaged-api/debugging/icordebugmanagedcallback-loadassembly-method.md)   
 [ICorDebugManagedCallback Interface](../../../../docs/framework/unmanaged-api/debugging/icordebugmanagedcallback-interface.md)