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

EditBox:GetMaxBytes\(\) - 获取EditBox中允许的最大字节数 -  1.11中的新增功能。

EditBox:GetMaxLetters\(\) - 获取EditBox中允许的最大字母数 -  1.11中的新增功能。

EditBox:GetNumLetters\(\) - 获取框中的字母数。

[EditBox:GetNumber](https://wow.gamepedia.com/API_EditBox_GetNumber)\(\)

[EditBox:GetText](https://wow.gamepedia.com/API_EditBox_GetText)\(\) - 获取编辑框中包含的当前文本。

[EditBox:GetTextInsets](https://wow.gamepedia.com/API_EditBox_GetTextInsets)\(\) - 获取编辑框的文本显示插入 -  1.11中的新增功能。

EditBox:HasFocus\(\) - 返回当前是否正在编辑编辑框（具有编辑焦点）。

[EditBox:HighlightText](https://wow.gamepedia.com/API_EditBox_HighlightText)\(\[startPos, endPos\]\) - 将突出显示设置为全部或部分编辑框文本。

[EditBox:Insert](https://wow.gamepedia.com/API_EditBox_Insert)\("text"\) - 将文本插入编辑框。

EditBox:IsAutoFocus\(\) - 确定EditBox是否启用了自动对焦 -  1.11中的新增功能。

EditBox:IsMultiLine\(\) - 确定EditBox是否接受多行 -  1.11中的新增内容。

EditBox:IsNumeric\(\) - 确定EditBox是否只接受数字输入 -  1.11中的新增内容。

EditBox:IsPassword\(\) - 确定EditBox是否执行密码屏蔽 -  1.11中的新增功能。

EditBox:SetAltArrowKeyMode\(enable\) - 只使用alt +箭头键可以导航编辑框，而不是单独使用箭头键。

[EditBox:SetAutoFocus](https://wow.gamepedia.com/API_EditBox_SetAutoFocus)\(state\) - 设置编辑框是否会在显示时尝试获取输入焦点（默认值：是） -  1.11中的新增内容。

EditBox:SetBlinkSpeed

[EditBox:SetCursorPosition](https://wow.gamepedia.com/API_EditBox_SetCursorPosition)\(position\) - 在EditBox中设置光标的位置 -  2.3中的新增内容。

EditBox:SetFocus\(\) - 将输入焦点（光标）移动到此编辑框

[EditBox:SetFont](https://wow.gamepedia.com/API_EditBox_SetFont)\("font", size\[,"flags"\]\) - 设置用于显示的字体。

EditBox:SetHistoryLines\(\) - 设置要记住的历史记录行数。

[EditBox:SetHyperlinksEnabled](https://wow.gamepedia.com/API_EditBox_SetHyperlinksEnabled)\(enableFlag\) - 设置EditBox是否触发超链接脚本处理程序。

EditBox:SetMaxBytes\(maxBytes\) - 设置输入文本的最大字节大小。

[EditBox:SetMaxLetters](https://wow.gamepedia.com/API_EditBox_SetMaxLetters)\(maxLetters\) - 设置输入文本的最大字母数。

EditBox:SetMultiLine\(state\) - 设置EditBox的多行状态 -  1.11中的新建。

EditBox:SetNumber\(number\)

EditBox:SetNumeric\(state\) - 如果EditBox仅接受数字输入，则设置 -  1.11中的新建。

EditBox:SetPassword\(state\) - 设置EditBox的密码屏蔽状态 -  1.11中的新建。

[EditBox:SetText](https://wow.gamepedia.com/API_EditBox_SetText)\("text"\) - 设置编辑框中包含的文本。

[EditBox:SetTextInsets](https://wow.gamepedia.com/API_EditBox_SetTextInsets)\(l, r, t, b\)

EditBox:ToggleInputLanguage\(\)

