---
title: IPrinterBidiSchemaResponses AddText method
description: The AddText method adds a new response of type BIDI\_TEXT to the collection.
MSHAttr:
- 'PreferredSiteName:MSDN'
- 'PreferredLib:/library/windows/hardware'
ms.assetid: 2421D77A-E0B2-4114-A27E-59E0D9A88E7C
keywords: ["AddText method Print Devices", "AddText method Print Devices , IPrinterBidiSchemaResponses interface", "IPrinterBidiSchemaResponses interface Print Devices , AddText method"]
topic_type:
- apiref
api_name:
- IPrinterBidiSchemaResponses.AddText
api_type:
- COM
---

# IPrinterBidiSchemaResponses::AddText method


The AddText method adds a new response of type BIDI\_TEXT to the collection.

Syntax
------

```ManagedCPlusPlus
HRESULT AddText(
  [in] BSTR bstrSchema,
  [in] BSTR bstrValue
);
```

Parameters
----------

*bstrSchema* \[in\]  
The schema.

*bstrValue* \[in\]  
The text.

Return value
------------

This method returns an **HRESULT** value.

Requirements
------------

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Target platform</p></td>
<td>Desktop</td>
</tr>
<tr class="even">
<td><p>Version</p></td>
<td><p>Windows 8</p></td>
</tr>
</tbody>
</table>

## <span id="see_also"></span>See also


[**IPrinterBidiSchemaResponses**](iprinterbidischemaresponses.md)

 

 

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bprint\print%5D:%20IPrinterBidiSchemaResponses::AddText%20method%20%20RELEASE:%20%281/8/2018%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")




