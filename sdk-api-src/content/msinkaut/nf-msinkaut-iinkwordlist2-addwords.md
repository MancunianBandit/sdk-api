---
UID: NF:msinkaut.IInkWordList2.AddWords
title: IInkWordList2::AddWords (msinkaut.h)
description: Adds more than one word to an InkWordList in a single operation.
old-location: tablet\iinkwordlist2_addwords.htm
tech.root: tablet
ms.assetid: 65afd260-f2ef-4744-a623-bcec4c742d61
ms.date: 12/05/2018
ms.keywords: 65afd260-f2ef-4744-a623-bcec4c742d61, AddWords, AddWords method [Tablet PC], AddWords method [Tablet PC],IInkWordList2 interface, IInkWordList2 interface [Tablet PC],AddWords method, IInkWordList2.AddWords, IInkWordList2::AddWords, msinkaut/IInkWordList2::AddWords, tablet.iinkwordlist2_addwords
f1_keywords:
- msinkaut/IInkWordList2.AddWords
dev_langs:
- c++
req.header: msinkaut.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows XP Tablet PC Edition [desktop apps only]
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
req.lib: InkObj.dll
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- InkObj.dll
- InkObj.dll.dll
api_name:
- IInkWordList2.AddWords
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IInkWordList2::AddWords


## -description



Adds more than one word to an <a href="https://docs.microsoft.com/windows/desktop/tablet/inkwordlist-class">InkWordList</a> in a single operation.




## -parameters




### -param NewWords [in]

A <b>BSTR</b> of <b>NULL</b> separated words terminated by a double <b>NULL</b> containing the words to add to the <a href="https://docs.microsoft.com/windows/desktop/tablet/inkwordlist-class">InkWordList</a>.

For more information about the <b>BSTR</b> data type, see <a href="https://docs.microsoft.com/windows/desktop/tablet/using-the-com-library">Using the COM Library</a>.


## -returns



This method can return one of these values.

<table>
<tr>
<th>Return code</th>
<th>Description</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>S_OK</b></dt>
</dl>
</td>
<td width="60%">
Success.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>S_FALSE</b></dt>
</dl>
</td>
<td width="60%">
At least one word already exists in the list.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_OUTOFMEMORY</b></dt>
</dl>
</td>
<td width="60%">
Cannot allocate memory to complete the operation.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_FAIL</b></dt>
</dl>
</td>
<td width="60%">
An unspecified error occurred.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_POINTER</b></dt>
</dl>
</td>
<td width="60%">
A parameter contained an invalid pointer.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_INK_EXCEPTION</b></dt>
</dl>
</td>
<td width="60%">
An exception occurred inside the method.

</td>
</tr>
</table>
 




## -remarks



To access this method, first create and instance of the <a href="https://docs.microsoft.com/windows/desktop/tablet/inkwordlist-class">InkWordList Class</a>, then call <a href="https://docs.microsoft.com/windows/desktop/api/unknwn/nf-unknwn-iunknown-queryinterface(q_)">QueryInterface</a> to get a pointer to the <a href="https://docs.microsoft.com/windows/desktop/api/msinkaut/nn-msinkaut-iinkwordlist2">IInkWordList2 Interface</a>. Use this pointer to call the <b>AddWords Method</b>.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/msinkaut/nf-msinkaut-iinkwordlist-addword">AddWord Method</a>



<a href="https://docs.microsoft.com/windows/desktop/api/msinkaut/nn-msinkaut-iinkwordlist2">IInkWordList2 Interface</a>



<a href="https://docs.microsoft.com/windows/desktop/tablet/inkwordlist-class">InkWordList Class</a>
 

 

