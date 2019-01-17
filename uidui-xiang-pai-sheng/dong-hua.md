### 动画

###### 这是一种基本动画类型。这可以处理所有动画计时和簿记。动画标记必须始终由AnimationGroup标记作为父级。

Animation:Play\(\) - 播放动画。

Animation:Pause\(\) - 暂停动画。

Animation:Stop\(\) - 停止动画。

Animation:IsDone\(\) - 如果动画播放完毕，则返回true。

Animation:IsPlaying\(\) - 如果正在播放动画，则返回true。

Animation:IsPaused\(\) - 如果正在动画已经暂停，则返回true。

Animation:IsStopped\(\) - 如果正在动画已经停止，则返回true。

Animation:IsDelaying\(\) - 如果动画处于开始或结束延迟的中间，则返回true。

Animation:GetElapsed\(\) - 获取动画播放的时间量（以秒为单位）。

Animation:SetStartDelay\(delaySec\) - 设置动画在开始进度之前延迟的秒数。

Animation:GetStartDelay\(\) - 获取动画在开始进度之前延迟的秒数。

Animation:SetEndDelay\(delaySec\) - 设置完成后动画延迟的秒数。

Animation:GetEndDelay\(\) - 获取完成后动画延迟的秒数。

Animation:SetDuration\(durationSec\) -设置动画从开始到结束所需的秒数。

Animation:GetDuration\(\) - 获取动画从开始到结束所需的秒数。

Animation:GetProgress\(\) - 以单位值\[0,1\]的形式返回动画的进度。忽略开始和结束延迟。

Animation:GetSmoothProgress\(\) - 返回动画的平滑的\[0,1\]进度值。

Animation:GetProgressWithDelay\(\) - 返回动画的进度及其开始和结束延迟。

Animation:SetOrder\(order\) - 设置动画在其父组中播放的顺序。范围是\[1,100\]。

Animation:GetOrder\(\) - 获取其父组中动画的顺序。

Animation:SetSmoothing\(smoothType\) - 设置动画的平滑类型。输入为\[IN，OUT或IN\_OUT\]。

Animation:GetSmoothing\(\) - 获取动画的平滑类型。

Animation:SetParent\(animGroup or "animGroupName"\) -设置动画的父级。如果动画还不是父动画的子动画，则父动画将在其子动画中按顺序插入动画。

Animation:GetRegionParent\(\) - 获取动画操作的Region对象。region对象是此Animation的父级父级（AnimationGroup的父级）。

Animation:HasScript\("handler"\) - 与Frame:HasScript相同, 输入为\[OnLoad, OnPlay, OnPaused, OnStop, OnFinished, OnUpdate\].

Animation:GetScript\("handler"\) - 与Frame:GetScript相同, 输入为\[OnLoad, OnPlay, OnPaused, OnStop, OnFinished, OnUpdate\].

Animation:SetScript\("handler"\) - 与Frame:SetScript相同, 输入为\[OnLoad, OnPlay, OnPaused, OnStop, OnFinished, OnUpdate\].

