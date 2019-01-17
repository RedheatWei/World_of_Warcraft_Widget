### 按钮

###### Button具有[UIObject](https://wow.gamepedia.com/Widget_API#UIObject)，[Region](https://wow.gamepedia.com/Widget_API#Region)和[Frame](https://wow.gamepedia.com/Widget_API#Frame)的所有方法，以及以下内容：

[Button:Click](https://wow.gamepedia.com/API_Button_Click)\(\) - Execute the click action of the button.

Button:Disable\(\) - Disable the Button so that it cannot be clicked.

Button:Enable\(\) - Enable to the Button so that it may be clicked.

Button:GetButtonState\(\) - Return the current state \("PUSHED","NORMAL"\) of the Button.

Button:GetDisabledFontObject\(\) - Return the font object for the Button when disabled - New in 1.10.

Button:GetDisabledTexture\(\) - Get the texture for this button when disabled - New in 1.11.

Button:GetFontString\(\) - Get this button's label FontString - New in 1.11.

Button:GetHighlightFontObject\(\) - Return the font object for the Button when highlighted - New in 1.10.

[Button:GetHighlightTexture](https://wow.gamepedia.com/API_Button_GetHighlightTexture)\(\) - Get the texture for this button when highlighted.

Button:GetMotionScriptsWhileDisabled\(\) - Get whether the button is allowed to run its OnEnter and OnLeave scripts even while disabled - New in 3.3.

Button:GetNormalTexture\(\) - Get the normal texture for this button - New in 1.11.

[Button:GetNormalFontObject](https://wow.gamepedia.com/API_Button_GetNormalFontObject)\(\) - Get the Font Object of the button.

Button:GetPushedTextOffset\(\) - Get the text offset when this button is pushed \(x, y\) - New in 1.11.

Button:GetPushedTexture\(\) - Get the texture for this button when pushed - New in 1.11.

[Button:GetText](https://wow.gamepedia.com/API_Button_GetText)\(\) - Get the text label for the Button.

Button:GetTextHeight\(\) - Get the height of the Button's text.

Button:GetTextWidth\(\) - Get the width of the Button's text.

[Button:IsEnabled](https://wow.gamepedia.com/API_Button_IsEnabled)\(\) - Determine whether the Button is enabled.

Button:LockHighlight\(\) - Set the Button to always be drawn highlighted.

[Button:RegisterForClicks](https://wow.gamepedia.com/API_Button_RegisterForClicks)\("clickType"\[,"clickType"...\]\) - Specify which mouse button up/down actions cause this button to receive an OnClick notification.

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



