### 消息框架

###### 消息框架具有[UIObject](https://wow.gamepedia.com/Widget_API#UIObject)，[Region](https://wow.gamepedia.com/Widget_API#Region)和[Frame](https://wow.gamepedia.com/Widget_API#Frame)的所有方法，以及以下内容：

[MessageFrame:AddMessage](https://wow.gamepedia.com/API_MessageFrame_AddMessage)\("text", r, g, b, messageGroup, holdTime\) - 向框架添加消息，最终会消失。

MessageFrame:Clear\(\) - 清除框架中的消息 -  1.11中的新功能。

MessageFrame:GetFadeDuration\(\) - 以秒为单位获取渐变持续时间 - 1.11中的新功能。

MessageFrame:GetFading\(\) - 确定框架是否褪色 - 1.11中的新功能。

MessageFrame:GetInsertMode\(\) - 获取框架的插入模式 - 1.11中的新功能。

MessageFrame:GetTimeVisible\(\) - 以秒为单位获取消息可见性时间 -1.11中的新功能。

MessageFrame:SetFadeDuration\(seconds\) -设置淡入淡出持续时间 - 1.11中的新功能。

MessageFrame:SetFading\(status\) - 设置框架是否淡出消息 - 1.11中的新功能。

MessageFrame:SetInsertMode\("TOP" or "BOTTOM"\) - 设置插入新消息的位置 - 1.11中的新功能。

MessageFrame:SetTimeVisible\(seconds\) - 设置消息可见性时间  1.11中的新功能。

