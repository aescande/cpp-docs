---
title: "char_traits&lt;char16_t&gt; Struct | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: ["cpp-standard-libraries"]
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: ["char_traits<char16_t>", "iosfwd/std::char_traits<char16_t>"]
dev_langs: ["C++"]
helpviewer_keywords: ["char_traits<char16_t> class"]
ms.assetid: 5daf3b62-dd6e-451f-b189-0350a04ff966
caps.latest.revision: 15
author: "corob-msft"
ms.author: "corob"
manager: "ghogen"
---
# char_traits&lt;char16_t&gt; Struct
A struct that is a specialization of the template struct **char_traits\<CharType>** to an element of type `char16_t`.  
  
## Syntax  
  
```
template <>  
struct char_traits<char16_t>;
```  
  
## Remarks  
 Specialization allows the struct to take advantage of library functions that manipulate objects of the type `char16_t`.  
  
## Requirements  
 **Header:** \<string>  
  
 **Namespace:** std  
  
## See Also  
 [\<string>](../standard-library/string.md)   
 [char_traits Struct](../standard-library/char-traits-struct.md)   
 [Thread Safety in the C++ Standard Library](../standard-library/thread-safety-in-the-cpp-standard-library.md)



