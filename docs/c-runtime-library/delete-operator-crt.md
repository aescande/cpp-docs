---
title: "operator delete(CRT) | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "devlang-cpp"
ms.tgt_pltfrm: ""
ms.topic: "article"
apilocation: 
  - "msvcr90.dll"
  - "msvcr110_clr0400.dll"
  - "msvcr110.dll"
  - "msvcr120.dll"
  - "msvcr100.dll"
  - "msvcr80.dll"
apitype: "DLLExport"
f1_keywords: 
  - "delete[]"
dev_langs: 
  - "C++"
  - "C"
helpviewer_keywords: 
  - "operator delete[]"
  - "vector delete"
ms.assetid: e91bd0df-3815-40ca-950a-67b470518aed
caps.latest.revision: 9
author: "corob-msft"
ms.author: "corob"
manager: "ghogen"
translation.priority.ht: 
  - "cs-cz"
  - "de-de"
  - "es-es"
  - "fr-fr"
  - "it-it"
  - "ja-jp"
  - "ko-kr"
  - "pl-pl"
  - "pt-br"
  - "ru-ru"
  - "tr-tr"
  - "zh-cn"
  - "zh-tw"
---
# operator delete(CRT)
Frees allocated block.  
  
## Syntax  
  
```  
  
      void __cdecl operator delete[](void * object);  
void __cdecl operator delete[](void * object,   
   void * memory) throw();  
void __cdecl operator delete[](void * object,   
   const std::nothrow_t&) throw();  
```  
  
#### Parameters  
 *memory*  
 The memory location being freed.  
  
 *object*  
 A pointer to the object being deleted.  
  
## Remarks  
 This form of **operator delete** is known as vector delete, in contrast to the scalar delete form ([operator delete](../c-runtime-library/operator-delete-crt.md)).  
  
 **operator** `delete[]` frees memory allocated by [operator new&#91;&#93;](../c-runtime-library/new-operator-crt.md).  
  
 The first form of this operator is known as the nonplacement form. The second and third forms of this operator will commonly not be called from code but exist to give the compiler a matching delete to call when a placement new fails.  
  
 The first form of the operator is defined by the compiler and does not require new.h to be included in your program.  
  
 With the exception of throwing or no-throwing behavior, the CRT **operator** `delete[]` behaves like [operator delete&#91;&#93;](../Topic/operator%20delete\(%3Cnew%3E\).md) in the Standard C++ Library.  
  
## Requirements  
  
|Routine|Required header|  
|-------------|---------------------|  
|`delete[]`|\<new.h>|  
  
 For additional compatibility information, see [Compatibility](../c-runtime-library/compatibility.md) in the Introduction.  
  
## Libraries  
 All versions of the [C run-time libraries](../c-runtime-library/crt-library-features.md).  
  
## Example  
 See [operator new&#91;&#93;](../c-runtime-library/new-operator-crt.md) for examples of using operator **delete**.  
  
## See Also  
 [Memory Allocation](../c-runtime-library/memory-allocation.md)