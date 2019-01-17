### 动画

###### 这是一种基本动画类型。这可以处理所有动画计时和簿记。动画标记必须始终由AnimationGroup标记作为父级。

Animation:Play\(\) - 播放动画。

Animation:Pause\(\) - 暂停动画。

Animation:Stop\(\) - 停止动画。

Animation:IsDone\(\) - 如果动画播放完毕，则返回true。

Animation:IsPlaying\(\) - 如果正在播放动画，则返回true。

Animation:IsPaused\(\) - 如果正在动画已经暂停，则返回true。

Animation:IsStopped\(\) - 如果正在动画已经停止，则返回true。

Animation:IsDelaying\(\) - Returns true if the animation is in the middle of a start or end delay.

Animation:GetElapsed\(\) - Gets the amount of time in seconds that the animation has been playing for.

Animation:SetStartDelay\(delaySec\) - Set the number of seconds that the animation delays before it starts to progress.

Animation:GetStartDelay\(\) - Get the number of seconds that the animation delays before it starts to progress.

Animation:SetEndDelay\(delaySec\) - Set the number of seconds the animation delays after finishing.

Animation:GetEndDelay\(\) - Get the number of seconds the animation delays after finishing.

Animation:SetDuration\(durationSec\) - Set the number of seconds it takes for the animation to progress from start to finish.

Animation:GetDuration\(\) - Get the number of seconds it takes for the animation to progress from start to finish.

Animation:GetProgress\(\) - Returns the progress of the animation as a unit value \[0,1\]. Ignores start and end delay.

Animation:GetSmoothProgress\(\) - Returns a smoothed, \[0,1\] progress value for the animation.

Animation:GetProgressWithDelay\(\) - Returns the progress of the animation combined with its start and end delay.

Animation:SetOrder\(order\) - Sets the order that the animation plays within its parent group. Range is \[1,100\].

Animation:GetOrder\(\) - Gets the order of the animation within its parent group.

Animation:SetSmoothing\(smoothType\) - Sets the smoothing type for the animation. Input is \[IN,OUT, or IN\_OUT\].

Animation:GetSmoothing\(\) - Gets the smoothing type for the animation.

Animation:SetParent\(animGroup or "animGroupName"\) - Sets the parent for the animation. If the animation was not already a child of the parent, the parent will insert the animation into the proper order amongst its children.

Animation:GetRegionParent\(\) - Gets the Region object that the animation operates on. The region object is this Animation's parent's parent \(the AnimationGroup's parent\).

Animation:HasScript\("handler"\) - Same as Frame:HasScript, Input is \[OnLoad, OnPlay, OnPaused, OnStop, OnFinished, OnUpdate\].

Animation:GetScript\("handler"\) - Same as Frame:GetScript, Input is \[OnLoad, OnPlay, OnPaused, OnStop, OnFinished, OnUpdate\].

Animation:SetScript\("handler"\) - Same as Frame:SetScript, Input is \[OnLoad, OnPlay, OnPaused, OnStop, OnFinished, OnUpdate\].

