---
title: "__wbinvd | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: ["cpp-tools"]
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: ["__wbinvd"]
dev_langs: ["C++"]
helpviewer_keywords: ["__wbinvd intrinsic", "wbinvd instruction"]
ms.assetid: 628d0981-39e5-49e1-bd43-706d123af121
caps.latest.revision: 11
author: "corob-msft"
ms.author: "corob"
manager: "ghogen"
---
# __wbinvd
**Microsoft Specific**  
  
 Generates the Write Back and Invalidate Cache (`wbinvd`) instruction.  
  
## Syntax  
  
```  
void __wbinvd(void);  
```  
  
## Requirements  
  
|Intrinsic|Architecture|  
|---------------|------------------|  
|`__wbinvd`|x86, [!INCLUDE[vcprx64](../assembler/inline/includes/vcprx64_md.md)]|  
  
 **Header file** \<intrin.h>  
  
## Remarks  
 This function is only available in kernel mode with a privilege level (CPL) of 0, and the routine is only available as an intrinsic.  
  
**END Microsoft Specific**  
  
## See Also  
 [Compiler Intrinsics](../intrinsics/compiler-intrinsics.md)