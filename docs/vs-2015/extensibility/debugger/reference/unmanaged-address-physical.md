---
title: "UNMANAGED_ADDRESS_PHYSICAL | Microsoft Docs"
ms.custom: ""
ms.date: "2018-06-30"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-sdk"
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: 
  - "UNMANAGED_ADDRESS_PHYSICAL"
helpviewer_keywords: 
  - "UNMANAGED_ADDRESS_PHYSICAL structure"
ms.assetid: fed09686-caa6-4efc-851e-a0432019e9d0
caps.latest.revision: 7
ms.author: "gregvanl"
manager: "ghogen"
---
# UNMANAGED_ADDRESS_PHYSICAL
[!INCLUDE[vs2017banner](../../../includes/vs2017banner.md)]

The latest version of this topic can be found at [UNMANAGED_ADDRESS_PHYSICAL](https://docs.microsoft.com/visualstudio/extensibility/debugger/reference/unmanaged-address-physical).  
  
This structure represents a physical address.  
  
## Syntax  
  
```cpp  
typedef struct _tagUNMANAGED_ADDRESS_PHYSICAL {  
   ULONGLONG offset;  
} UNMANAGED_ADDRESS_PHYSICAL;  
```  
  
```csharp  
public struct UNMANAGED_ADDRESS_PHYSICAL {  
   public ulong offset;  
}  
```  
  
## Terms  
 offset  
 A 64-bit offset into a physical address space.  
  
## Remarks  
 This structure is part of the union in the [DEBUG_ADDRESS_UNION](../../../extensibility/debugger/reference/debug-address-union.md) structure when the `dwKind` field of the `DEBUG_ADDRESS_UNION` structure is set to `ADDRESS_KIND_UNMANAGED_PHYSICAL` (a value from the [ADDRESS_KIND](../../../extensibility/debugger/reference/address-kind.md) enumeration).  
  
## Requirements  
 Header: sh.h  
  
 Namespace: Microsoft.VisualStudio.Debugger.Interop  
  
 Assembly: Microsoft.VisualStudio.Debugger.Interop.dll  
  
## See Also  
 [Structures and Unions](../../../extensibility/debugger/reference/structures-and-unions.md)   
 [DEBUG_ADDRESS_UNION](../../../extensibility/debugger/reference/debug-address-union.md)

