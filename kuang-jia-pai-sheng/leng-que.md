### 冷却

###### 冷却具有[UIObject](https://wow.gamepedia.com/Widget_API#UIObject)，[Region](https://wow.gamepedia.com/Widget_API#Region)和[Frame](https://wow.gamepedia.com/Widget_API#Frame)的所有方法，以及以下内容：

[Cooldown:SetCooldown](https://wow.gamepedia.com/API_Cooldown_SetCooldown)\(start, duration\[, modRate\]\) - 显示冷却动画。

[duration = Cooldown:GetCooldownDuration](https://wow.gamepedia.com/API_Cooldown_GetCooldownDuration)\(\) - 返回冷却框架当前显示的持续时间（以毫秒为单位）

startTime, duration = Cooldown:GetCooldownTimes\(\) - 以毫秒为单位返回冷却帧的开始时间和持续时间

[Cooldown:SetReverse](https://wow.gamepedia.com/API_Cooldown_SetReverse)\(boolean\) - 控制冷却动画的方向。

[Cooldown:SetBlingDuration](https://wow.gamepedia.com/API_Cooldown_SetBlingDuration)\(duration\) - （5.2的新内容）

Cooldown:GetDrawBling\(\) - 

enabled = Cooldown:GetDrawEdge\(\) - 返回是否应在冷却动画的移动边缘上绘制亮线

Cooldown:GetDrawSwipe\(\) -

enabled = Cooldown:GetReverse\(\) - 返回是否应该反转冷却动画的亮部和暗部

Cooldown:SetBlingTexture\(\) - 

Cooldown:SetCooldownDuration\(\) -

Cooldown:SetCooldownUNIX\(\) - 

Cooldown:SetDrawBling\(\) -

Cooldown:SetDrawEdge\(enable\) - 设置是否应在冷却动画的移动边缘上绘制亮线

Cooldown:SetDrawSwipe\(\) - 

Cooldown:SetEdgeTexture\(\) - 

Cooldown:SetHideCountdownNumbers\(hide\) - 显示或隐藏文本冷却时间

Cooldown:SetSwipeColor\(\) - 

Cooldown:SetSwipeTexture\(\) - 

