### 编辑框

###### 有关详细信息，请参阅[EditBox object information](https://wow.gamepedia.com/UIOBJECT_EditBox)。

###### 编辑框具有[UIObject](https://wow.gamepedia.com/Widget_API#UIObject)，[Region](https://wow.gamepedia.com/Widget_API#Region)和[Frame](https://wow.gamepedia.com/Widget_API#Frame)的所有方法，以及以下内容：

[EditBox:AddHistoryLine](https://wow.gamepedia.com/API_EditBox_AddHistoryLine)\("text"\) - 将文本添加到编辑历史记录中。

[EditBox:ClearFocus](https://wow.gamepedia.com/API_EditBox_ClearFocus)\(\)

[EditBox:GetAltArrowKeyMode](https://wow.gamepedia.com/API_EditBox_GetAltArrowKeyMode)\(\) - 返回是否只有alt +箭头键可用于导航编辑框，而不只是箭头键。

EditBox:GetBlinkSpeed\(\) - 以秒为单位获取EditBox的闪烁速度 -  1.11中的新增速度。

[EditBox:GetCursorPosition](https://wow.gamepedia.com/API_EditBox_GetCursorPosition)\(\) - 获取EditBox中的光标位置 -  2.3中的新建。

EditBox:GetHistoryLines\(\) - 获取此编辑框的历史记录行数

[EditBox:GetHyperlinksEnabled](https://wow.gamepedia.com/API_EditBox_GetHyperlinksEnabled)\(\) -返回EditBox是否触发超链接脚本处理程序。

[EditBox:GetInputLanguage](https://wow.gamepedia.com/API_EditBox_GetInputLanguage)\(\) - 获取输入语言（不基于游戏的语言环境）

EditBox:GetMaxBytes\(\) - 获取EditBox中允许的最大字节数 -  1.11中的新增。

EditBox:GetMaxLetters\(\) - 获取EditBox中允许的最大字母数 -  1.11中的新增字母。

EditBox:GetNumLetters\(\) - 获取框中的字母数。

[EditBox:GetNumber](https://wow.gamepedia.com/API_EditBox_GetNumber)\(\)

[EditBox:GetText](https://wow.gamepedia.com/API_EditBox_GetText)\(\) - Get the current text contained in the edit box.

[EditBox:GetTextInsets](https://wow.gamepedia.com/API_EditBox_GetTextInsets)\(\) - Gets the text display insets for the EditBox - New in 1.11.

EditBox:HasFocus\(\) - Returns whether the edit box is currently being edited \(has edit focus\).

[EditBox:HighlightText](https://wow.gamepedia.com/API_EditBox_HighlightText)\(\[startPos, endPos\]\) - Set the highlight to all or some of the edit box text.

[EditBox:Insert](https://wow.gamepedia.com/API_EditBox_Insert)\("text"\) - Insert text into the edit box.

EditBox:IsAutoFocus\(\) - Determine if the EditBox has autofocus enabled - New in 1.11.

EditBox:IsMultiLine\(\) - Determine if the EditBox accepts multiple lines - New in 1.11.

EditBox:IsNumeric\(\) - Determine if the EditBox only accepts numeric input - New in 1.11.

EditBox:IsPassword\(\) - Determine if the EditBox performs password masking - New in 1.11.

EditBox:SetAltArrowKeyMode\(enable\) - Make only alt+arrow keys work for navigating the edit box, not arrow keys alone.

[EditBox:SetAutoFocus](https://wow.gamepedia.com/API_EditBox_SetAutoFocus)\(state\) - Set whether or not the editbox will attempt to get input focus when it gets shown \(default: yes\) - New in 1.11.

EditBox:SetBlinkSpeed

[EditBox:SetCursorPosition](https://wow.gamepedia.com/API_EditBox_SetCursorPosition)\(position\) - Set the position of the cursor within the EditBox - New in 2.3.

EditBox:SetFocus\(\) - Move input focus \(the cursor\) to this editbox

[EditBox:SetFont](https://wow.gamepedia.com/API_EditBox_SetFont)\("font", size\[,"flags"\]\) - Set the font to use for display.

EditBox:SetHistoryLines\(\) - Set the number of history lines to remember.

[EditBox:SetHyperlinksEnabled](https://wow.gamepedia.com/API_EditBox_SetHyperlinksEnabled)\(enableFlag\) - Set whether the EditBox triggers hyperlink script handlers.

EditBox:SetMaxBytes\(maxBytes\) - Set the maximum byte size for entered text.

[EditBox:SetMaxLetters](https://wow.gamepedia.com/API_EditBox_SetMaxLetters)\(maxLetters\) - Set the maximum number of letters for entered text.

EditBox:SetMultiLine\(state\) - Set the EditBox's multi-line state - New in 1.11.

EditBox:SetNumber\(number\)

EditBox:SetNumeric\(state\) - Set if the EditBox only accepts numeric input - New in 1.11.

EditBox:SetPassword\(state\) - Set the EditBox's password masking state - New in 1.11.

[EditBox:SetText](https://wow.gamepedia.com/API_EditBox_SetText)\("text"\) - Set the text contained in the edit box.

[EditBox:SetTextInsets](https://wow.gamepedia.com/API_EditBox_SetTextInsets)\(l, r, t, b\)

EditBox:ToggleInputLanguage\(\)



