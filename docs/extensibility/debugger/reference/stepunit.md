---
title: "STEPUNIT | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.technology: 
  - "vs-ide-sdk"
ms.topic: "conceptual"
f1_keywords: 
  - "STEPUNIT"
helpviewer_keywords: 
  - "STEPUNIT enumeration"
ms.assetid: cb8441f2-f744-4e73-acfe-ae8542df9649
author: "gregvanl"
ms.author: "gregvanl"
manager: douge
ms.workload: 
  - "vssdk"
---
# STEPUNIT
Specifies the step unit for stepping.  
  
## Syntax  
  
```cpp  
enum enum_STEPUNIT {   
   STEP_STATEMENT   = 0,  
   STEP_LINE        = 1,  
   STEP_INSTRUCTION = 2  
};  
typedef DWORD STEPUNIT;  
```  
  
```csharp  
enum enum_STEPUNIT {   
   STEP_STATEMENT   = 0,  
   STEP_LINE        = 1,  
   STEP_INSTRUCTION = 2  
};  
```  
  
## Members  
 STEP_STATEMENT  
 Steps by statement.  
  
 STEP_LINE  
 Steps by line.  
  
 STEP_INSTRUCTION  
 Steps by instruction.  
  
## Remarks  
 Passed as an argument to the [Step](../../../extensibility/debugger/reference/idebugprocess3-step.md) method.  
  
## Requirements  
 Header: msdbg.h  
  
 Namespace: Microsoft.VisualStudio.Debugger.Interop  
  
 Assembly: Microsoft.VisualStudio.Debugger.Interop.dll  
  
## See Also  
 [Enumerations](../../../extensibility/debugger/reference/enumerations-visual-studio-debugging.md)   
 [Step](../../../extensibility/debugger/reference/idebugprocess3-step.md)