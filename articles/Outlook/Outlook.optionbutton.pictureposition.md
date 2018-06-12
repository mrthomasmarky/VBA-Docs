---
title: OptionButton.PicturePosition Property (Outlook Forms Script)
ms.prod: outlook
ms.assetid: e159fe5c-99fa-979b-570b-2984839aed19
ms.date: 06/08/2017
---


# OptionButton.PicturePosition Property (Outlook Forms Script)

Returns or sets an  **Integer** that specifies the location of the picture relative to its caption. Read/write.


## Syntax

 _expression_. **PicturePosition**

 _expression_A variable that represents an  **OptionButton** object.


## Remarks

The settings for  **PicturePosition** are:



|**Value**|**Description**|
|:-----|:-----|
|0|The picture appears to the left of the caption. The caption is aligned with the top of the picture.|
|1|The picture appears to the left of the caption. The caption is centered relative to the picture.|
|2|The picture appears to the left of the caption. The caption is aligned with the bottom of the picture.|
|3|The picture appears to the right of the caption. The caption is aligned with the top of the picture.|
|4|The picture appears to the right of the caption. The caption is centered relative to the picture.|
|5|The picture appears to the right of the caption. The caption is aligned with the bottom of the picture.|
|6|The picture appears above the caption. The caption is aligned with the left edge of the picture.|
|7|The picture appears above the caption. The caption is centered below the picture (default).|
|8|The picture appears above the caption. The caption is aligned with the right edge of the picture.|
|9|The picture appears below the caption. The caption is aligned with the left edge of the picture.|
|10|The picture appears below the caption. The caption is centered above the picture.|
|11|The picture appears below the caption. The caption is aligned with the right edge of the picture.|
|12|The picture appears in the center of the control. The caption is centered horizontally and vertically on top of the picture.|
The picture and the caption, as a unit, are centered on the control. If no caption exists, the picture's location is relative to the center of the control.

This property is ignored if the  **[Picture](Outlook.optionbutton.picture.md)** property does not specify a picture.

