---
UID: NF:rdpencomapi.IRDPSRAPIInvitation.get_Revoked
title: IRDPSRAPIInvitation::get_Revoked (rdpencomapi.h)
description: The revoked state of the invitation.
old-location: rdp\irdpsrapiinvitation_revoked.htm
tech.root: rdp
ms.assetid: a5a2d1a4-a51b-4fd4-b79c-3381f296d072
ms.date: 12/05/2018
ms.keywords: IRDPSRAPIInvitation interface [RDP],Revoked property, IRDPSRAPIInvitation.Revoked, IRDPSRAPIInvitation.get_Revoked, IRDPSRAPIInvitation::Revoked, IRDPSRAPIInvitation::get_Revoked, IRDPSRAPIInvitation::put_Revoked, RDPSRAPIInvitation object [RDP],Revoked property, Revoked property [RDP], Revoked property [RDP],IRDPSRAPIInvitation interface, Revoked property [RDP],RDPSRAPIInvitation object, get_Revoked, rdp.irdpsrapiinvitation_revoked, rdpencomapi/IRDPSRAPIInvitation::Revoked, rdpencomapi/IRDPSRAPIInvitation::get_Revoked, rdpencomapi/IRDPSRAPIInvitation::put_Revoked
f1_keywords:
- rdpencomapi/IRDPSRAPIInvitation.Revoked
dev_langs:
- c++
req.header: rdpencomapi.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows Vista [desktop apps \| UWP apps]
req.target-min-winversvr: Windows Server 2008 [desktop apps \| UWP apps]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: RdpEncomAPI.idl
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: RdpEncomAPI.tlb
req.lib: 
req.dll: RdpEncom.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- RdpEncom.dll
api_name:
- IRDPSRAPIInvitation.Revoked
- IRDPSRAPIInvitation.get_Revoked
- IRDPSRAPIInvitation.put_Revoked
- RDPSRAPIInvitation.Revoked
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IRDPSRAPIInvitation::get_Revoked


## -description


The revoked state of the invitation.

This property is read/write.


## -parameters


## -remarks



There is no way to delete an invitation, only to revoke it. This enables the application to check whether a ticket was issued before to ensure that each invitation has a unique ticket. If an invitation state is revoked,  no new attendees can connect by using that invitation.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/rdpencomapi/nn-rdpencomapi-irdpsrapiinvitation">IRDPSRAPIInvitation</a>
 

 

