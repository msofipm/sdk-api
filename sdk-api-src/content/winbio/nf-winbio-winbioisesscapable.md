---
UID: NF:winbio.WinBioIsESSCapable
title: WinBioIsESSCapable function (winbio.h)
description: Retrieves a value that specifies whether the device meets all the requirements for Enhanced-Sign In Security (ESS).
helpviewer_keywords: ["WinBioIsESSCapable","WinBioIsESSCapable function [Windows Biometric Framework API]","winbio/WinBioIsESSCapable"]
old-location: pending
tech.root: pending
ms.assetid: pending
ms.date: 10/02/2023
ms.keywords: WinBioIsESSCapable, WinBioIsESSCapable function [Windows Biometric Framework API], winbio/WinBioIsESSCapable
req.header: winbio.h
req.include-header: Winbio.h
req.target-type: Windows
req.target-min-winverclnt: Windows 11 more specific pending
req.target-min-winversvr: pending
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Winbio.lib
req.dll: Winbio.dll
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: pending
f1_keywords:
 - WinBioIsESSCapable
 - winbio/WinBioIsESSCapable
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - DllExport
api_location:
 - Winbio.dll
 - winbioext.dll
 - Ext-MS-Win-BioMetrics-WinBio-Core-L1-1-1.dll
api_name:
 - WinBioIsESSCapable
---

# WinBioIsESSCapable function


## -description

Retrieves a value that specifies whether the device meets all the requirements for Enhanced-Sign In Security (ESS).

## -parameters

### -param Value [out]

Pointer to a Boolean value that specifies whether the device is ESS capable.


## -returns

If the function succeeds, it returns S_OK. If the function fails, it returns an <b>HRESULT</b> value that indicates the error. For a list of common error codes, see <a href="/windows/desktop/SecCrypto/common-hresult-values">Common HRESULT Values</a>.

## -see-also

<a href="/windows/desktop/SecBioMet/client-application-functions">Client Application Functions</a>
