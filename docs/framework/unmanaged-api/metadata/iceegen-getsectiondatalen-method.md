---
title: "ICeeGen::GetSectionDataLen Method | Microsoft Docs"
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
  - "ICeeGen.GetSectionDataLen"
apilocation: 
  - "mscoree.dll"
apitype: "COM"
f1_keywords: 
  - "ICeeGen::GetSectionDataLen"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "ICeeGen::GetSectionDataLen method [.NET Framework metadata]"
  - "GetSectionDataLen method [.NET Framework metadata]"
ms.assetid: e2a06ee4-b8ee-49c7-935a-c1031a29eef2
caps.latest.revision: 13
author: "mairaw"
ms.author: "mairaw"
manager: "wpickett"
---
# ICeeGen::GetSectionDataLen Method
Gets the length of the specified section.  
  
 This method is obsolete and should not be used.  
  
## Syntax  
  
```  
HRESULT GetSectionDataLen (  
    [in]  HCEESECTION  section,  
    [out] ULONG        *dataLen  
);  
```  
  
#### Parameters  
 `section`  
 [in] The data section whose length will be retrieved.  
  
 `dataLen`  
 [out] The returned length of the specified section.  
  
## Remarks  
 Call `GetSectionDataLen` only if you have special section requirements that are not handled by other methods.  
  
## Requirements  
 **Platforms:** See [System Requirements](../../../../docs/framework/get-started/system-requirements.md).  
  
 **Header:** Cor.h  
  
 **Library:** Used as a resource in MsCorEE.dll  
  
 **.NET Framework Versions:** [!INCLUDE[net_current_v10plus](../../../../includes/net-current-v10plus-md.md)]  
  
## See Also  
 [ICeeGen Interface](../../../../docs/framework/unmanaged-api/metadata/iceegen-interface.md)