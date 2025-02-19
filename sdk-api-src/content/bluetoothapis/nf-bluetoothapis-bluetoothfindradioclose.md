---
UID: NF:bluetoothapis.BluetoothFindRadioClose
title: BluetoothFindRadioClose function (bluetoothapis.h)
description: The BluetoothFindRadioClose function closes the enumeration handle associated with finding Bluetooth radios.
old-location: bluetooth\bluetoothfindradioclose.htm
tech.root: bluetooth
ms.assetid: 859771b1-d06c-414b-81cb-bb3913fd0380
ms.date: 12/05/2018
ms.keywords: BluetoothFindRadioClose, BluetoothFindRadioClose function [Bluetooth], bluetooth.bluetoothfindradioclose, bluetoothapis/BluetoothFindRadioClose
f1_keywords:
- bluetoothapis/BluetoothFindRadioClose
dev_langs:
- c++
req.header: bluetoothapis.h
req.include-header: Bthsdpdef.h, BluetoothAPIs.h
req.target-type: Windows
req.target-min-winverclnt: Windows Vista, Windows XP with SP2 [desktop apps only]
req.target-min-winversvr: None supported
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Bthprops.lib
req.dll: Bthprops.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- DllExport
api_location:
- Bthprops.dll
- BluetoothAPIs.dll
- Ext-MS-Win-Bluetooth-APIs-l1-1-0.dll
api_name:
- BluetoothFindRadioClose
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# BluetoothFindRadioClose function


## -description


The <b>BluetoothFindRadioClose</b> function closes the enumeration handle associated with finding Bluetooth radios.


## -parameters




### -param hFind

Enumeration handle to close, obtained with a previous call to the <a href="https://docs.microsoft.com/windows/desktop/api/bluetoothapis/nf-bluetoothapis-bluetoothfindfirstradio">BluetoothFindFirstRadio</a> function.


## -returns



Returns <b>TRUE</b> when the handle is successfully closed. Returns <b>FALSE</b> if the attempt fails to close the enumeration handle. For additional information on possible errors associated with closing the handle, call the <a href="https://docs.microsoft.com/windows/desktop/api/errhandlingapi/nf-errhandlingapi-getlasterror">GetLastError</a> function.




## -see-also




<a href="https://docs.microsoft.com/windows/win32/api/bluetoothapis/ns-bluetoothapis-bluetooth_find_radio_params">BLUETOOTH_FIND_RADIO_PARAMS</a>



<a href="https://docs.microsoft.com/windows/desktop/api/bluetoothapis/nf-bluetoothapis-bluetoothfindfirstradio">BluetoothFindFirstRadio</a>



<a href="https://docs.microsoft.com/windows/desktop/api/bluetoothapis/nf-bluetoothapis-bluetoothfindnextradio">BluetoothFindNextRadio</a>



<a href="https://docs.microsoft.com/windows/desktop/api/bluetoothapis/nf-bluetoothapis-bluetoothgetradioinfo">BluetoothGetRadioInfo</a>



<a href="https://docs.microsoft.com/windows/desktop/api/errhandlingapi/nf-errhandlingapi-getlasterror">GetLastError</a>
 

 

