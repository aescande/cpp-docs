---
title: "Compiler Errors C2500 Through C2599 | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: ["cpp-tools"]
ms.tgt_pltfrm: ""
ms.topic: "error-reference"
f1_keywords: ["C2501", "C2508", "C2515", "C2519", "C2520", "C2522", "C2525", "C2527", "C2536", "C2538", "C2539", "C2546", "C2547", "C2559", "C2560", "C2564", "C2565", "C2576", "C2578", "C2580", "C2590", "C2591", "C2595", "C2596"]
helpviewer_keywords: ["C2501", "C2508", "C2515", "C2519", "C2520", "C2522", "C2525", "C2527", "C2536", "C2538", "C2539", "C2546", "C2547", "C2559", "C2560", "C2564", "C2565", "C2576", "C2578", "C2580", "C2590", "C2591", "C2595", "C2596"]
dev_langs: ["C++"]
ms.assetid: a869aaed-e9f6-49e3-b273-00ea7f45bed7
caps.latest.revision: 15
author: "corob-msft"
ms.author: "corob"
manager: "ghogen"
---
# Compiler Errors C2500 Through C2599
The articles in this part of the documentation contain information about a subsection of the Visual C++ compiler errors. You can access the information here or, in the **Output** window in Visual Studio, you can select an error number and then choose the F1 key.  
  
> [!NOTE]
>  Not every [!INCLUDE[vcprvc](../../build/includes/vcprvc_md.md)] error is documented in MSDN. In many cases, the diagnostic message provides all of the information that's available. If you think an error message needs additional explanation, you can let us know. You can use the feedback form on this page, or go to the menu bar in Visual Studio and choose **Help**, **Report a Bug**, or you can submit a suggestion or bug report on [Microsoft Connect](http://connect.microsoft.com/VisualStudio).  
  
 You may find additional assistance for errors and warnings on the MSDN public forums. The [Visual C++ Language](http://go.microsoft.com/fwlink/?LinkId=158195) forum is for questions and discussions about the [!INCLUDE[vcprvc](../../build/includes/vcprvc_md.md)] language syntax and compiler. The [Visual C++ General](http://go.microsoft.com/fwlink/?LinkId=158194) forum is for questions about [!INCLUDE[vcprvc](../../build/includes/vcprvc_md.md)] that are not discussed in other forums. You may also find help about errors and warnings on [Stack Overflow](http://stackoverflow.com/).  
  
|Error|Message|  
|-----------|-------------|  
|[Compiler Error C2500](compiler-error-C2500.md)|'*identifier1*': '*identifier2*' is already a direct base class|  
|Compiler Error C2501|'*identifier*': '__declspec(*specifier*)' can only be applied to structs, unions, classes, or unsigned bit field members|  
|[Compiler Error C2502](compiler-error-C2502.md)|'*identifier*': too many access modifiers on the base class|  
|[Compiler Error C2503](compiler-error-C2503.md)|'*class*': base classes cannot contain zero-sized arrays|  
|[Compiler Error C2504](compiler-error-C2504.md)|'*class*': base class undefined|  
|[Compiler Error C2505](compiler-error-C2505.md)|'*symbol*': '__declspec(*specifier*)' can only be applied to declarations or definitions of global objects or static data members|  
|[Compiler Error C2506](compiler-error-C2506.md)|'*member*': '__declspec(*specifier*)' cannot be applied to this symbol|  
|[Compiler Error C2507](compiler-error-C2507.md)|'*identifier*': too many virtual modifiers on the base class|  
|Compiler Error C2508|'*identifier*': '__declspec(*specifier1*)' cannot be combined with '__declspec(*specifier2*)'|  
|[Compiler Error C2509](compiler-error-C2509.md)|'*identifier*': member function not declared in '*class*'|  
|[Compiler Error C2510](compiler-error-C2510.md)|'*identifier*': left of '::' must be a class/struct/union|  
|[Compiler Error C2511](compiler-error-C2511.md)|'*identifier*': overloaded member function not found in '*class*'|  
|[Compiler Error C2512](compiler-error-C2512.md)|'*identifier*': no appropriate default constructor available|  
|[Compiler Error C2513](compiler-error-C2513.md)|'*type': no variable declared before '='|  
|[Compiler Error C2514](compiler-error-C2514.md)|'*class*': class has no constructors|  
|Compiler Error C2515|'*identifier*': 'vtguard' can only be applied to class declarations or definitions|  
|[Compiler Error C2516](compiler-error-C2516.md)|'*class*': is not a legal base class|  
|[Compiler Error C2517](compiler-error-C2517.md)|'*identifier*': right of '::' is undefined|  
|[Compiler Error C2518](compiler-error-C2518.md)|keyword '*keyword*' illegal in base class list; ignored|  
|Compiler Error C2519|'*identifier*': WinRT attributes may only contain public fields|  
|Compiler Error C2520|'*class*': no non-explicit constructor available for implicit conversion|  
|[Compiler Error C2521](compiler-error-C2521.md)|a destructor/finalizer does not take any arguments|  
|Compiler Error C2522|'*identifier*': Overload identifier cannot be used on '*identifier1*' as it's already specified on '*identifier2*'|  
|[Compiler Error C2523](compiler-error-C2523.md)|'*class*::~*identifier*': destructor/finalizer tag mismatch|  
|[Compiler Error C2524](compiler-error-C2524.md)|'*identifier*': a destructor/finalizer must have a 'void' parameter list|  
|Compiler Error C2525|'*identifier*': The parameter '*identifier1*' is named '*identifier2*' on the base function and must be matched in a published implementation|  
|[Compiler Error C2526](compiler-error-C2526.md)|'*identifier1*': C linkage function cannot return C++ class '*identifier2*'|  
|Compiler Error C2527|'*identifier*': DefaultOverload cannot be specified on both '*function1*' and '*function2*'. Remove one specification or rename the function during implementation|  
|[Compiler Error C2528](compiler-error-C2528.md)|'*identifier*': pointer to reference is illegal|  
|[Compiler Error C2529](compiler-error-C2529.md)|'*identifier*': reference to reference is illegal|  
|[Compiler Error C2530](compiler-error-C2530.md)|'*identifier*': references must be initialized|  
|[Compiler Error C2531](compiler-error-C2531.md)|'*identifier*': reference to a bit field illegal|  
|[Compiler Error C2532](compiler-error-C2532.md)|'*identifier*': illegal modifier for reference|  
|[Compiler Error C2533](compiler-error-C2533.md)|'*identifier*': constructors not allowed a return type|  
|[Compiler Error C2534](compiler-error-C2534.md)|'*identifier*': constructor cannot return a value|  
|[Compiler Error C2535](compiler-error-C2535.md)|'*identifier*': member function already defined or declared|  
|Compiler Error C2536|Obsolete.|  
|[Compiler Error C2537](compiler-error-C2537.md)|'*specifier*': illegal linkage specification|  
|Compiler Error C2538|Obsolete.|  
|Compiler Error C2539|Obsolete.|
|[Compiler Error C2540](compiler-error-C2540.md)|non-constant expression as array bound|  
|[Compiler Error C2541](compiler-error-C2541.md)|'*identifier*': cannot delete objects that are not pointers|  
|[Compiler Error C2542](compiler-error-C2542.md)|'*identifier*': class object has no constructor for initialization|  
|[Compiler Error C2543](compiler-error-C2543.md)|expected ']' for operator '[]'|  
|[Compiler Error C2544](compiler-error-C2544.md)|expected ')' for operator '()'|  
|[Compiler Error C2545](compiler-error-C2545.md)|'*operator*': unable to find overloaded operator|  
|Compiler Error C2546|'*identifier*': when a type is defined in both a PIA and a no-PIA the PIA must be referenced first|  
|Compiler Error C2547|'*identifier*': All parameters of a published method must be explicitly named on the declaration|  
|[Compiler Error C2548](compiler-error-C2548.md)|'*function*': missing default parameter for parameter *parameter*|  
|[Compiler Error C2549](compiler-error-C2549.md)|user-defined conversion cannot specify a return type|  
|[Compiler Error C2550](compiler-error-C2550.md)|'*identifier*': constructor initializer lists are only allowed on constructor definitions|  
|[Compiler Error C2551](compiler-error-C2551.md)|'void *' type needs explicit cast|  
|[Compiler Error C2552](compiler-error-C2552.md)|'*identifier*': non-aggregates cannot be initialized with an initializer list|  
|[Compiler Error C2553](compiler-error-C2553.md)|'*type* *derived_class*::*function*': overriding virtual function return type differs from '*type* *base_class*::*function*'|  
|[Compiler Error C2555](compiler-error-C2555.md)|'*derived_class*::*function*': overriding virtual function return type differs and is not covariant from '*base_class*::*function*'|  
|[Compiler Error C2556](compiler-error-C2556.md)|'*type1* *class*::*function*': overloaded function differs only by return type from '*type2* *class*::*function*'|  
|[Compiler Error C2557](compiler-error-C2557.md)|'*identifier*': private and protected members cannot be initialized without a constructor|  
|[Compiler Error C2558](compiler-error-C2558.md)|class '*class*': no copy constructor available or copy constructor is declared 'explicit'|  
|Compiler Error C2559|'*identifier*': cannot overload a member function without ref-qualifier with a member function with ref-qualifier|  
|Compiler Error C2560|'*identifier*': cannot overload a member function with ref-qualifier with a member function without ref-qualifier|  
|[Compiler Error C2561](compiler-error-C2561.md)|'*function*': function must return a value|  
|[Compiler Error C2562](compiler-error-C2562.md)|'*function*': 'void' function returning a value|  
|[Compiler Error C2563](compiler-error-C2563.md)|mismatch in formal parameter list|  
|Compiler Error C2564|Obsolete.|  
|Compiler Error C2565|'*identifier*': ref-qualifier is illegal for constructors/destructors|  
|[Compiler Error C2566](compiler-error-C2566.md)|overloaded function in conditional expression|  
|[Compiler Error C2567](compiler-error-C2567.md)|unable to open metadata in '*filename*', *possible_reason*|  
|[Compiler Error C2568](compiler-error-C2568.md)|'*identifier*': unable to resolve function overload|  
|[Compiler Error C2569](compiler-error-C2569.md)|'*identifier*': enum/union cannot be used as a base class|  
|[Compiler Error C2570](compiler-error-C2570.md)|'*identifier*': union cannot have base classes|  
|[Compiler Error C2571](compiler-error-C2571.md)|'*identifier*': virtual function cannot be in union '*union*'|  
|[Compiler Error C2572](compiler-error-C2572.md)|'*function*': redefinition of default argument: parameter *number*|  
|[Compiler Error C2573](compiler-error-C2573.md)|'*class*': cannot delete pointers to objects of this type; the class has no non-placement overload for 'operator delete'. Use ::delete, or add 'operator delete(void*)' to the class|  
|[Compiler Error C2574](compiler-error-C2574.md)|'*destructor*': cannot be declared static|  
|[Compiler Error C2575](compiler-error-C2575.md)|'*identifier*': only member functions and bases can be virtual|  
|Compiler Error C2576|'*identifier*': cannot introduce a new virtual method as 'public'. Consider making the method non-virtual, or change the accessibility to 'internal' or 'protected private'|  
|[Compiler Error C2577](compiler-error-C2577.md)|'*identifier*': a destructor/finalizer cannot have a return type|  
|Compiler Error C2578|'*class*': type cannot have a 'protected' or 'protected public' constructor|  
|[Compiler Error C2579](compiler-error-C2579.md)|unable to resolve type *type* (*offset*). It is expected in *filename*|  
|Compiler Error C2580|'*identifier*': multiple versions of a defaulted special member functions are not allowed|  
|[Compiler Error C2581](compiler-error-C2581.md)|'*type*': static 'operator =' function is illegal|  
|[Compiler Error C2582](compiler-error-C2582.md)|'operator *operator*' function is unavailable in '*type*'|  
|[Compiler Error C2583](compiler-error-C2583.md)|'*identifier*': 'const/volatile' 'this' pointer is illegal for constructors/destructors|  
|[Compiler Error C2584](compiler-error-C2584.md)|'*class*': direct base '*base_class2*' is inaccessible; already a base of '*base_class1*'|  
|[Compiler Error C2585](compiler-error-C2585.md)|explicit conversion to '*type*' is ambiguous|  
|[Compiler Error C2586](compiler-error-C2586.md)|incorrect user-defined conversion syntax: illegal indirections|  
|[Compiler Error C2587](compiler-error-C2587.md)|'*identifier*': illegal use of local variable as default parameter|  
|[Compiler Error C2588](compiler-error-C2588.md)|'::~*identifier*': illegal global destructor/finalizer|  
|[Compiler Error C2589](compiler-error-C2589.md)|'*identifier*': illegal token on right side of '::'|  
|Compiler Error C2590|'*identifier*': only a constructor can have a base/member initializer list|  
|Compiler Error C2591|ExclusiveTo cannot use '*type*' as an argument. Only a 'ref class' is a valid argument|  
|[Compiler Error C2592](compiler-error-C2592.md)|'*class*': '*base_class2*' is inherited from '*base_class1*' and cannot be re-specified|  
|[Compiler Error C2593](compiler-error-C2593.md)|'operator *identifier*' is ambiguous|  
|[Compiler Error C2594](compiler-error-C2594.md)|'*operator*': ambiguous conversions from '*type1*' to '*type2*'|  
|Compiler Error C2595|'*identifier*' A WinRT attribute type must be sealed|  
|Compiler Error C2596|'*identifier*' A WinRT attribute field can only be a 'public enum class', 'int', 'unsigned int', 'bool', 'Platform::Type', 'Platform::String' or 'Windows::Foundation::HResult'|  
|[Compiler Error C2597](compiler-error-C2597.md)|illegal reference to non-static member '*identifier*'|  
|[Compiler Error C2598](compiler-error-C2598.md)|linkage specification must be at global scope|  
|[Compiler Error C2599](compiler-error-C2599.md)|'*identifier*': the forward declaration of a managed/WinRT enum is not allowed|  