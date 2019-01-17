### 字体实例

###### 这是另一种抽象对象类型，它将多个其他窗口小部件类型使用的许多字体相关方法组合在一起。这与UI对象没有直接关联。FontInstance具有[UIObject](https://wow.gamepedia.com/Widget_API#UIObject)的所有方法，以及以下内容：

[FontInstance:GetFont](https://wow.gamepedia.com/API_FontInstance_GetFont)\(\) - 返回字体文件，高度和标志。

[FontInstance:GetFontObject](https://wow.gamepedia.com/API_FontInstance_GetFontObject)\(\) - 返回'父'Font对象，如果没有，则返回nil。

FontInstance:GetJustifyH\(\) - 返回水平文本对齐。

FontInstance:GetJustifyV\(\) - 返回垂直文本对齐。

FontInstance:GetShadowColor\(\) - 返回文本阴影的颜色（r，g，b，a）。

FontInstance:GetShadowOffset\(\) - 返回文本阴影偏移量（x，y）。

FontInstance:GetSpacing\(\) - 返回文本间距。

[FontInstance:GetTextColor](https://wow.gamepedia.com/API_FontInstance_GetTextColor)\(\) - 返回默认文本颜色。

[FontInstance:SetFont](https://wow.gamepedia.com/API_FontInstance_SetFont)\("path", height\[,"flags"\]\) - 设置用于文本的字体，如果路径有效则返回1，否则返回nil（不发生更改）。

[FontInstance:SetFontObject](https://wow.gamepedia.com/API_FontInstance_SetFontObject)\(fontObject\) - 设置此对象从其继承属性的“父”Font对象。  
FontInstance:SetJustifyH\("justifyH"\) - 设置水平文本对齐（“​​LEFT”，“RIGHT”或“CENTER”）

FontInstance:SetJustifyV\("justifyV"\) - 设置垂直文本对齐（“​​TOP”，“BOTTOM”或“MIDDLE”）

FontInstance:SetShadowColor\(r, g, b\[, a\]\) - 设置文本阴影颜色。

FontInstance:SetShadowOffset\(x, y\) - 设置文本阴影偏移量。

FontInstance:SetSpacing\(spacing\) - 设置对象中文本行之间的间距。

[FontInstance:SetTextColor](https://wow.gamepedia.com/API_FontInstance_SetTextColor)\(r, g, b\[, a\]\) - 设置默认文本颜色。

