### 滚动消息框架

###### 滚动消息框架具有[UIObject](https://wow.gamepedia.com/Widget_API#UIObject)，[FontInstance](https://wow.gamepedia.com/Widget_API#FontInstance)，[Region](https://wow.gamepedia.com/Widget_API#Region)和[Frame](https://wow.gamepedia.com/Widget_API#Frame)的所有方法，以及以下内容：

[ScrollingMessageFrame:AddMessage](https://wow.gamepedia.com/API_ScrollingMessageFrame_AddMessage)\("message"\[, r, g, b\[, ...\]\]\) - 使用可选颜色和任何其他数据在消息缓冲区的前面添加消息。

ScrollingMessageFrame:AdjustMessageColors\(transformFunction\)

ScrollingMessageFrame:AtBottom\(\) - Test whether frame is at the bottom.

ScrollingMessageFrame:AtTop\(\) - Test whether frame is at the top.

ScrollingMessageFrame:BackFillMessage\("message"\[, r, g, b\[, ...\]\]\) -使用可选颜色和任何其他数据在消息缓冲区的尾端添加消息。

ScrollingMessageFrame:Clear\(\) - Clear all lines from the frame.

ScrollingMessageFrame:GetFadeDuration\(\)

ScrollingMessageFrame:GetFading\(\)

ScrollingMessageFrame:GetInsertMode\(\) - 获取框架的当前插入模式。

ScrollingMessageFrame:GetMessageInfo\(messageIndex\)

ScrollingMessageFrame:GetMaxLines\(\) - 获取框架可以显示的最大行数。

ScrollingMessageFrame:GetMaxScrollRange\(\)

ScrollingMessageFrame:GetNumMessages\(\)

ScrollingMessageFrame:GetNumVisibleLines\(\)

ScrollingMessageFrame:GetScrollOffset\(\)

ScrollingMessageFrame:GetTimeVisible\(\)

ScrollingMessageFrame:PageDown\(\)

ScrollingMessageFrame:PageUp\(\)

ScrollingMessageFrame:RemoveMessagesByPredicate\(predicate\)

ScrollingMessageFrame:ScrollDown\(\)

ScrollingMessageFrame:ScrollToBottom\(\)

ScrollingMessageFrame:ScrollToTop\(\)

ScrollingMessageFrame:ScrollUp\(\)

[ScrollingMessageFrame:SetFadeDuration](https://wow.gamepedia.com/API_ScrollingMessageFrame_SetFadeDuration)\(fadeDurationSecs\) - 设置淡入淡出持续时间。

[ScrollingMessageFrame:SetFading](https://wow.gamepedia.com/API_ScrollingMessageFrame_SetFading)\(shouldFadeAfterInactivity\) - 设置是否启用淡入淡出。

[ScrollingMessageFrame:SetInsertMode](https://wow.gamepedia.com/API_ScrollingMessageFrame_SetInsertMode)\(insertMode\) - 设置将新字符串添加到框架的位置，1表示“顶部”，2表示“底部”。

[ScrollingMessageFrame:SetMaxLines](https://wow.gamepedia.com/API_ScrollingMessageFrame_SetMaxLines)\(maxLines\) - 设置最大显示行数。

ScrollingMessageFrame:SetScrollOffset\(offset\)

[ScrollingMessageFrame:SetTimeVisible](https://wow.gamepedia.com/API_ScrollingMessageFrame_SetTimeVisible)\(timeVisibleSecs\) - 设置线条保持可见的时长。.

  
  


