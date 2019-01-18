### 按钮

###### Button具有[UIObject](https://wow.gamepedia.com/Widget_API#UIObject)，[Region](https://wow.gamepedia.com/Widget_API#Region)和[Frame](https://wow.gamepedia.com/Widget_API#Frame)的所有方法，以及以下内容：

[Button:Click](https://wow.gamepedia.com/API_Button_Click)\(\) - 执行按钮的单击操作。

Button:Disable\(\) - 禁用按钮以使其无法单击。

Button:Enable\(\) - 启用按钮以便可以单击它。

Button:GetButtonState\(\) - 返回按钮的当前状态（“PUSHED”，“NORMAL”）。

Button:GetDisabledFontObject\(\) - 禁用时返回Button的字体对象 -  1.10中的新增功能。

Button:GetDisabledTexture\(\) - 禁用时获取此按钮的纹理 -  1.11中的新增功能。

Button:GetFontString\(\) - 获取此按钮的标签FontString  -  1.11中的新功能。

Button:GetHighlightFontObject\(\) - 突出显示时返回Button的字体对象 -  1.10中的新增内容。

[Button:GetHighlightTexture](https://wow.gamepedia.com/API_Button_GetHighlightTexture)\(\) - 突出显示时，获取此按钮的纹理。

Button:GetMotionScriptsWhileDisabled\(\) - 获取是否允许按钮在禁用时运行其OnEnter和OnLeave脚本 -  3.3中的新增功能。

Button:GetNormalTexture\(\) - 获取此按钮的正常纹理 -  1.11中的新增功能。

[Button:GetNormalFontObject](https://wow.gamepedia.com/API_Button_GetNormalFontObject)\(\) - 获取按钮的字体对象。

Button:GetPushedTextOffset\(\) - 按下此按钮时获取文本偏移量（x，y） -  1.11中的新增内容。

Button:GetPushedTexture\(\) - 按下时获取此按钮的纹理 -  1.11中的新增功能。

[Button:GetText](https://wow.gamepedia.com/API_Button_GetText)\(\) - 获取Button的文本标签。

Button:GetTextHeight\(\) - 获取Button文本的高度。

Button:GetTextWidth\(\) - 获取Button文本的宽度。

[Button:IsEnabled](https://wow.gamepedia.com/API_Button_IsEnabled)\(\) - 确定按钮是否已启用。

Button:LockHighlight\(\) - 将按钮设置为始终突出显示。

[Button:RegisterForClicks](https://wow.gamepedia.com/API_Button_RegisterForClicks)\("clickType"\[,"clickType"...\]\) - 指定哪个鼠标按钮向上/向下操作会导致此按钮接收OnClick通知。

Button:SetButtonState\("state"\[, lock\]\) - 设置按钮的状态（“PUSHED”，“NORMAL”）以及是否锁定。

Button:SetDisabledFontObject\(\[font\]\) - 禁用时设置“设置”的字体对象 -  1.10中的新增功能。

Button:SetDisabledTexture\(texture or "texturePath"\) - 为Button设置禁用的纹理 - 在1.10中更新。

[Button:SetFont](https://wow.gamepedia.com/API_Button_SetFont)\("font", size\[,"flags"\]\) - 设置用于显示的字体。

Button:SetFontString\(fontString\) - 设置按钮的标签FontString  -  1.11中的新增功能。

Button:SetFormattedText\("formatstring"\[, ...\]\) -  设置Button的格式化文本标签。-  2.3中的新功能。

Button:SetHighlightFontObject\(\[font\]\) - 突出显示时设置设置的字体对象 -  1.10中的新增内容。

Button:SetHighlightTexture\(texture or "texturePath"\[,alphaMode\]\) - 设置Button的高亮纹理。

Button:SetMotionScriptsWhileDisabled\(\[bool\]\) - 设置按钮是否应在禁用时触发其OnEnter和OnLeave脚本 -  3.3中的新增功能。

[Button:SetNormalTexture](https://wow.gamepedia.com/API_Button_SetNormalTexture)\(texture or "texturePath"\) - 设置按钮的正常纹理 - 在1.10中更新。

[Button:SetNormalFontObject](https://wow.gamepedia.com/API_Button_SetNormalFontObject)\(FontObject\) - 设置按钮的字体对象。

Button:SetPushedTextOffset\(x, y\) - 按下时设置此按钮的文本偏移量 -  1.11中的新值。

Button:SetPushedTexture\(texture or "texturePath"\) - 设置Button的推送纹理 - 在1.10中更新。

[Button:SetText](https://wow.gamepedia.com/API_Button_SetText)\("text"\) - 设置Button的文本标签。

Button:UnlockHighlight\(\) - 将按钮设置为不总是突出显示。

