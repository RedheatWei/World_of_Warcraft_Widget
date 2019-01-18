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

Button:SetButtonState\("state"\[, lock\]\) - Set the state of the Button \("PUSHED", "NORMAL"\) and whether it is locked.

Button:SetDisabledFontObject\(\[font\]\) - Set the font object for settings when disabled - New in 1.10.

Button:SetDisabledTexture\(texture or "texturePath"\) - Set the disabled texture for the Button - Updated in 1.10.

[Button:SetFont](https://wow.gamepedia.com/API_Button_SetFont)\("font", size\[,"flags"\]\) - Set the font to use for display.

Button:SetFontString\(fontString\) - Set the button's label FontString - New in 1.11.

Button:SetFormattedText\("formatstring"\[, ...\]\) - Set the formatted text label for the Button. - New in 2.3.

Button:SetHighlightFontObject\(\[font\]\) - Set the font object for settings when highlighted - New in 1.10.

Button:SetHighlightTexture\(texture or "texturePath"\[,alphaMode\]\) - Set the highlight texture for the Button.

Button:SetMotionScriptsWhileDisabled\(\[bool\]\) - Set whether button should fire its OnEnter and OnLeave scripts even while disabled - New in 3.3.

[Button:SetNormalTexture](https://wow.gamepedia.com/API_Button_SetNormalTexture)\(texture or "texturePath"\) - Set the normal texture for the Button - Updated in 1.10.

[Button:SetNormalFontObject](https://wow.gamepedia.com/API_Button_SetNormalFontObject)\(FontObject\) - Set the Font Object of the button.

Button:SetPushedTextOffset\(x, y\) - Set the text offset for this button when pushed - New in 1.11.

Button:SetPushedTexture\(texture or "texturePath"\) - Set the pushed texture for the Button - Updated in 1.10.

[Button:SetText](https://wow.gamepedia.com/API_Button_SetText)\("text"\) - Set the text label for the Button.

Button:UnlockHighlight\(\) - Set the Button to not always be drawn highlighted.

