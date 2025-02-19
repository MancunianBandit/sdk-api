---
UID: NF:shobjidl_core.IVirtualDesktopManager.GetWindowDesktopId
title: IVirtualDesktopManager::GetWindowDesktopId (shobjidl_core.h)
description: Gets the identifier for the virtual desktop hosting the provided top-level window.
old-location: shell\ivirtualdesktopmanager_getwindowdesktopid.htm
tech.root: shell
ms.assetid: 1A53C70F-6034-449D-832E-A563886F20E4
ms.date: 12/05/2018
ms.keywords: GetWindowDesktopId, GetWindowDesktopId method [Windows Shell], GetWindowDesktopId method [Windows Shell],IVirtualDesktopManager interface, IVirtualDesktopManager interface [Windows Shell],GetWindowDesktopId method, IVirtualDesktopManager.GetWindowDesktopId, IVirtualDesktopManager::GetWindowDesktopId, shell.ivirtualdesktopmanager_getwindowdesktopid, shobjidl_core/IVirtualDesktopManager::GetWindowDesktopId
f1_keywords:
- shobjidl_core/IVirtualDesktopManager.GetWindowDesktopId
dev_langs:
- c++
req.header: shobjidl_core.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 10 [desktop apps only]
req.target-min-winversvr: Windows Server 2016 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- shobjidl_core.h
api_name:
- IVirtualDesktopManager.GetWindowDesktopId
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IVirtualDesktopManager::GetWindowDesktopId


## -description


Gets the identifier for the virtual desktop hosting the provided top-level window.


## -parameters




### -param topLevelWindow [in]

The top level window for the virtual desktop you are interested in.


### -param desktopId [out]

The identifier for the virtual desktop hosting the <i>topLevelWindow</i>.


## -returns



If this method succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.




## -see-also




[IVirtualDesktopManager](/windows/win32/api/shobjidl_core/nn-shobjidl_core-ivirtualdesktopmanager)a>
 

 

