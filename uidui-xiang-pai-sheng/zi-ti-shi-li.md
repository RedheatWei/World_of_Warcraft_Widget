### 字体实例

###### 这是另一种抽象对象类型，它将多个其他窗口小部件类型使用的许多字体相关方法组合在一起。这与UI对象没有直接关联。FontInstance具有[UIObject](https://wow.gamepedia.com/Widget_API#UIObject)的所有方法，以及以下内容：

[FontInstance:GetFont](https://wow.gamepedia.com/API_FontInstance_GetFont)\(\) - 返回字体文件，高度和标志。

[FontInstance:GetFontObject](https://wow.gamepedia.com/API_FontInstance_GetFontObject)\(\) - 返回'parent'Font对象，如果没有，则返回nil。

FontInstance:GetJustifyH\(\) - 返回水平文本对齐。

FontInstance:GetJustifyV\(\) - 返回垂直文本对齐。

FontInstance:GetShadowColor\(\) - Returns the color of text shadow \(r, g, b, a\).

FontInstance:GetShadowOffset\(\) - Returns the text shadow offset \(x, y\).

FontInstance:GetSpacing\(\) - Returns the text spacing.

[FontInstance:GetTextColor](https://wow.gamepedia.com/API_FontInstance_GetTextColor)\(\) - Returns the default text color.

[FontInstance:SetFont](https://wow.gamepedia.com/API_FontInstance_SetFont)\("path", height\[,"flags"\]\) - Sets the font to use for text, returns 1 if the path was valid, nil otherwise \(no change occurs\).

[FontInstance:SetFontObject](https://wow.gamepedia.com/API_FontInstance_SetFontObject)\(fontObject\) - Sets the 'parent' Font object from which this object inherits properties.  
FontInstance:SetJustifyH\("justifyH"\) - Sets horizontal text justification \("LEFT","RIGHT", or "CENTER"\)

FontInstance:SetJustifyV\("justifyV"\) - Sets vertical text justification \("TOP","BOTTOM", or "MIDDLE"\)

FontInstance:SetShadowColor\(r, g, b\[, a\]\) - Sets the text shadow color.

FontInstance:SetShadowOffset\(x, y\) - Sets the text shadow offset.

FontInstance:SetSpacing\(spacing\) - Sets the spacing between lines of text in the object.

[FontInstance:SetTextColor](https://wow.gamepedia.com/API_FontInstance_SetTextColor)\(r, g, b\[, a\]\) - Sets the default text color.

  


