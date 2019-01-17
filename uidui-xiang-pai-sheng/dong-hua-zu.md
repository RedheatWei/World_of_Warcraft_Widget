### 动画组

###### 这管理其子动画的回放，顺序和循环。组中的动画将根据其顺序字段按升序播放（可通过SetOrder和GetOrder访问）。如果两个或多个动画具有相同的顺序值，则它们将同时播放。在完成具有该订单值的所有动画之前，下一个动画将不会播放。3.1.0中的新功能

AnimationGroup:Play\(\) - 开始播放此组中的动画。

AnimationGroup:Pause\(\) - 暂停此组中的动画。

AnimationGroup:Stop\(\) - 停止此组中的所有动画。

AnimationGroup:Finish\(\) - 当前循环周期完成后，通知该组停止播放。如果这个组没有播放，什么都不做。

AnimationGroup:GetProgress\(\) - 以单位值\[0,1\]的形式返回此动画的进度。

AnimationGroup:IsDone\(\) - 如果组已完成播放，则返回true。.

AnimationGroup:IsPlaying\(\) - 如果组正在播放，则返回true。

AnimationGroup:IsPaused\(\) - 如果组暂停，则返回true。

AnimationGroup:GetDuration\(\) - 获取该组将完成一个循环周期所需的所有子动画的总持续时间。

[AnimationGroup:GetIgnoreFramerateThrottle](https://wow.gamepedia.com/API_AnimationGroup_GetIgnoreFramerateThrottle)\(\) - 如果此动画组忽略全局动画帧速率限制，则返回true。

[AnimationGroup:SetIgnoreFramerateThrottle](https://wow.gamepedia.com/API_AnimationGroup_SetIgnoreFramerateThrottle)\(ignore\) - 设置此动画组是否忽略全局动画帧速率限制。

AnimationGroup:SetLooping\(loopType\) - 设置组的循环类型。输入为 \[NONE, REPEAT, 或BOUNCE\].

AnimationGroup:GetLooping\(\) - 获取组的循环类型。

AnimationGroup:GetLoopState\(\) - 获取组的当前循环状态。输出为\[NONE，FORWARD或REVERSE\]。

[AnimationGroup:CreateAnimation](https://wow.gamepedia.com/API_AnimationGroup_CreateAnimation)\("animationType", \["name"\[,"inheritsFrom"\]\]\) - 创建动画并将其作为此组的子项返回。

AnimationGroup:HasScript\("handler"\) - 与Frame:HasScript相同. 输入为\[OnLoad, OnPlay, OnPaused, OnStop, OnFinished, OnUpdate\].

AnimationGroup:GetScript\("handler"\) -与Frame:GetScript相同.输入为 \[OnLoad, OnPlay, OnPaused, OnStop, OnFinished, OnUpdate\].

AnimationGroup:SetScript\("handler", function\) - 与Frame:SetScript相同. 输入为\[OnLoad, OnPlay, OnPaused, OnStop, OnFinished, OnUpdate\].

