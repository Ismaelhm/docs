---
title: "ICLRDataEnumMemoryRegionsCallback Interface"
ms.date: "03/30/2017"
api_name: 
  - "ICLRDataEnumMemoryRegionsCallback"
api_location: 
  - "mscordbi.dll"
api_type: 
  - "COM"
f1_keywords: 
  - "ICLRDataEnumMemoryRegionsCallback"
helpviewer_keywords: 
  - "ICLRDataEnumMemoryRegionsCallback interface [.NET Framework debugging]"
ms.assetid: 3f1af8b0-8478-48e0-a7ec-3e90e0b97649
topic_type: 
  - "apiref"
author: "rpetrusha"
ms.author: "ronpet"
---
# ICLRDataEnumMemoryRegionsCallback Interface
Provides a callback method for [ICLRDataEnumMemoryRegions::EnumMemoryRegions](../../../../docs/framework/unmanaged-api/debugging/iclrdataenummemoryregions-enummemoryregions-method.md) to report to the debugger the result of an attempt to enumerate a specified region of memory.  
  
## Methods  
  
|Method|Description|  
|------------|-----------------|  
|[EnumMemoryRegion Method](../../../../docs/framework/unmanaged-api/debugging/iclrdataenummemoryregionscallback-enummemoryregion-method.md)|Called by `ICLRDataEnumMemoryRegions::EnumMemoryRegions` to report to the debugger the result of an attempt to enumerate a specified region of memory.|  
  
## Requirements  
 **Platforms:** See [System Requirements](../../../../docs/framework/get-started/system-requirements.md).  
  
 **Header:** ClrData.idl, ClrData.h  
  
 **Library:** CorGuids.lib  
  
 **.NET Framework Versions:** [!INCLUDE[net_current_v20plus](../../../../includes/net-current-v20plus-md.md)]  
  
## See also

- [Debugging Interfaces](../../../../docs/framework/unmanaged-api/debugging/debugging-interfaces.md)
