### 动画组

###### 这管理其子动画的回放，顺序和循环。组中的动画将根据其顺序字段按升序播放（可通过SetOrder和GetOrder访问）。如果两个或多个动画具有相同的顺序值，则它们将同时播放。在完成具有该订单值的所有动画之前，下一个动画将不会播放。3.1.0中的新功能

AnimationGroup:Play\(\) - 开始播放此组中的动画。

AnimationGroup:Pause\(\) - 暂停此组中的动画。

AnimationGroup:Stop\(\) - 停止此组中的所有动画。

AnimationGroup:Finish\(\) - 当前循环周期完成后，通知该组停止播放。如果这个组没有播放，什么都不做。

AnimationGroup:GetProgress\(\) - 以单位值\[0,1\]的形式返回此动画的进度。

AnimationGroup:IsDone\(\) - 如果组已完成播放，则返回true。.

AnimationGroup:IsPlaying\(\) - Returns true if the group is playing.

AnimationGroup:IsPaused\(\) - Returns true if the group is paused.

AnimationGroup:GetDuration\(\) - Gets the total duration across all child Animations that the group will take to complete one loop cycle.

[AnimationGroup:GetIgnoreFramerateThrottle](https://wow.gamepedia.com/API_AnimationGroup_GetIgnoreFramerateThrottle)\(\) - Returns true if the global animation framerate throttle is ignored by this animation group.

[AnimationGroup:SetIgnoreFramerateThrottle](https://wow.gamepedia.com/API_AnimationGroup_SetIgnoreFramerateThrottle)\(ignore\) - Sets whether the global animation framerate throttle is ignored by this animation group.

AnimationGroup:SetLooping\(loopType\) - Sets the type of looping for the group. Input is \[NONE, REPEAT, or BOUNCE\].

AnimationGroup:GetLooping\(\) - Gets the type of looping for the group.

AnimationGroup:GetLoopState\(\) - Gets the current loop state of the group. Output is \[NONE, FORWARD, or REVERSE\].

[AnimationGroup:CreateAnimation](https://wow.gamepedia.com/API_AnimationGroup_CreateAnimation)\("animationType", \["name"\[,"inheritsFrom"\]\]\) - Create and return an Animation as a child of this group.

AnimationGroup:HasScript\("handler"\) - Same as Frame:HasScript. Input is \[OnLoad, OnPlay, OnPaused, OnStop, OnFinished, OnUpdate\].

AnimationGroup:GetScript\("handler"\) - Same as Frame:GetScript. Input is \[OnLoad, OnPlay, OnPaused, OnStop, OnFinished, OnUpdate\].

AnimationGroup:SetScript\("handler", function\) - Same as Frame:SetScript. Input is \[OnLoad, OnPlay, OnPaused, OnStop, OnFinished, OnUpdate\].

