### 简单HTML

###### 有关详细信息，请参阅[SimpleHTML object information](https://wow.gamepedia.com/UIOBJECT_SimpleHTML)。

###### 滚动消息框架具有[UIObject](https://wow.gamepedia.com/Widget_API#UIObject)，[Region](https://wow.gamepedia.com/Widget_API#Region)和[Frame](https://wow.gamepedia.com/Widget_API#Frame)的所有方法，以及以下内容：

###### SimpleHTML似乎具有[FontInstance](https://wow.gamepedia.com/Widget_API#FontInstance)的所有方法，并且它们确实可以以相同的方式用于设置默认字体，但它们都具有可选的第一个参数，用于设置元素的字体（“h1”，“h2”，“p“等）。在您对框架上的SetText之前，Font实例方法不会反映在SimpleHTML框架中。看来你只能提供块元素而不是内联元素（即超链接不能用不同颜色着色）。除此之外，请参阅FontInstance以获取这些方法的文档。

SimpleHTML:GetFont\(\["element"\]\)

SimpleHTML:GetFontObject\(\["element"\]\)

SimpleHTML:GetHyperlinkFormat\(\) - 设置string.format格式以用于显示超链接 -  1.11中的新增内容。

SimpleHTML:GetHyperlinksEnabled\(\) - 3.0.8中的新功能

SimpleHTML:GetJustifyH\(\["element"\]\)

SimpleHTML:GetJustifyV\(\["element"\]\)

SimpleHTML:GetShadowColor\(\["element"\]\)

SimpleHTML:GetShadowOffset\(\["element"\]\)

SimpleHTML:GetSpacing\(\["element"\]\)

SimpleHTML:GetTextColor\(\["element"\]\)

SimpleHTML:SetFont\(\["element",\] "path", height\[,"flags"\]\)

SimpleHTML:SetFontObject\(\["element",\] fontObject\)

SimpleHTML:SetHyperlinkFormat\("format"\) - 设置string.format格式以用于显示超链接。

SimpleHTML:SetHyperlinksEnabled\(enableFlag\) - New in 3.0.8

SimpleHTML:SetJustifyH\(\["element",\] "justifyH"\)

SimpleHTML:SetJustifyV\(\["element",\] "justifyV"\)

SimpleHTML:SetShadowColor\(\["element",\] r, g, b\[, a\]\)

SimpleHTML:SetShadowOffset\(\["element",\] x, y\)

SimpleHTML:SetSpacing\(\["element",\] lineSpacing\)

[SimpleHTML:SetText](https://wow.gamepedia.com/API_SimpleHTML_SetText)\("text"\) - 设置要显示的HTML标记（注意：如果有任何标记错误，它将显示为纯文本）

SimpleHTML:SetTextColor\(\["element",\] r, g, b\[, a\]\)



