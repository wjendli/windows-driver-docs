---
title: PlatenColor element
description: The required PlatenColor element contains a list of ColorEntry elements that describe the color processing capabilities of the platen.
ms.assetid: 97fd9926-e49d-4b4f-95aa-eb4142c353a3
keywords: ["PlatenColor element Imaging Devices"]
topic_type:
- apiref
api_name:
- wscn PlatenColor
api_type:
- Schema
ms.author: windowsdriverdev
ms.date: 11/28/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-devices
---

# PlatenColor element


The required **PlatenColor** element contains a list of [**ColorEntry**](colorentry.md) elements that describe the color processing capabilities of the platen.

Usage
-----

``` syntax
<wscn:PlatenColor>
  child elements
</wscn:PlatenColor>
```

Attributes
----------

There are no attributes.

## Child elements


<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th>Element</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>[<strong>ColorEntry</strong>](colorentry.md)</p></td>
</tr>
</tbody>
</table>

## Parent elements


<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th>Element</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>[<strong>Platen</strong>](platen.md)</p></td>
</tr>
</tbody>
</table>

Remarks
-------

The **PlatenColor** element contains the information needed to determine the type of color processing and acquisition that the flatbed platen supports. The amount of information that is needed to describe each pixel depends on the specific [**ColorEntry**](colorentry.md) keyword. Black and white images require only one bit per pixel (bpp), whereas grayscale and color images require significantly more information. The exact amount of information is determined by the color space and technical capabilities of the scan device.

Another important aspect of the returned scan data is the photometric interpretation of the acquired data. All image data that the scan device returns is required to be black on white, where black is represented by 0 and white is represented by 1.

## <span id="see_also"></span>See also


[**ColorEntry**](colorentry.md)

[**Platen**](platen.md)

 

 

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bimage\image%5D:%20PlatenColor%20element%20%20RELEASE:%20%2811/8/2017%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")





