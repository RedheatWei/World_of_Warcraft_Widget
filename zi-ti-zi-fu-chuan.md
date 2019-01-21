### 字体字符串

###### 有关详细信息，请参阅[FontString object information](https://wow.gamepedia.com/UIOBJECT_FontString)。

###### 纹理具有[UIObject](https://wow.gamepedia.com/Widget_API#UIObject)，[FontInstance](https://wow.gamepedia.com/Widget_API#FontInstance)，[Region](https://wow.gamepedia.com/Widget_API#Region),和[LayeredRegion](https://wow.gamepedia.com/Widget_API#LayeredRegion)的所有方法，以及以下内容：

###### 请注意，FontString：Get / SetWidth\(\)和Get / SetHeight\(\)对于fontstrings的行为有很大不同;查看对象信息。

FontString:CanNonSpaceWrap\(\) - 获取是否包含或截断没有空格的长字符串 -  1.11中的新增内容。

[FontString:GetStringHeight](https://wow.gamepedia.com/API_FontString_GetStringHeight)\(\) - 返回当前字体中当前字符串的高度（以像素为单位）。-  2.3中的新功能。

[FontString:GetStringWidth](https://wow.gamepedia.com/API_FontString_GetStringWidth)\(\) - 返回当前字体中当前字符串的宽度（不包括换行符）。

[FontString:GetText](https://wow.gamepedia.com/API_FontString_GetText)\(\) - 获取显示的文本。

[FontString:SetAlphaGradient](https://wow.gamepedia.com/API_FontString_SetAlphaGradient)\(start, length\) - 在文本上创建或删除Alpha渐变。

[FontString:SetFormattedText](https://wow.gamepedia.com/API_FontString_SetFormattedText)\("formatstring"\[, ...\]\) - 设置格式化的显示文本。-  2.3中的新功能。

[FontString:SetNonSpaceWrap](https://wow.gamepedia.com/API_FontString_SetNonSpaceWrap)\(wrapFlag\) - 设置是否包含或截断没有空格的长字符串。

[FontString:SetText](https://wow.gamepedia.com/API_FontString_SetText)\("text"\) - 设置显示文本。

[FontString:SetTextHeight](https://wow.gamepedia.com/API_FontString_SetTextHeight)\(pixelHeight\) - 通过缩放图形设置文本的高度（注意：可以扭曲文本）。

