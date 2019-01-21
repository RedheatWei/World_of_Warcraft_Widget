### 滑块

###### 有关详细信息，请参阅[Slider object information](https://wow.gamepedia.com/UIOBJECT_Slider)。

###### 滑块架具有[UIObject](https://wow.gamepedia.com/Widget_API#UIObject)，[Region](https://wow.gamepedia.com/Widget_API#Region)和[Frame](https://wow.gamepedia.com/Widget_API#Frame)的所有方法，以及以下内容：

Slider:Disable\(\) - 禁用滑块

Slider:Enable\(\) - 启用滑块

[Slider:GetMinMaxValues](https://wow.gamepedia.com/API_Slider_GetMinMaxValues)\(\) - 获取滑块的当前边界。

[Slider:GetObeyStepOnDrag](https://wow.gamepedia.com/API_Slider_GetObeyStepOnDrag)\(\) - 返回滑块在拖动时是否将值约束为值步长。

Slider:GetOrientation\(\) - 返回 "HORIZONTAL"或"VERTICAL".

Slider:GetThumbTexture\(\) - 获取此滑块拇指的纹理 -  1.11中的新增功能。

Slider:GetValue\(\) - 获取滑块的当前值。

[Slider:GetValueStep](https://wow.gamepedia.com/API_Slider_GetValueStep)\(\) - 获取滑块的当前步长。

[Slider:GetStepsPerPage](https://wow.gamepedia.com/API_Slider_GetStepsPerPage)\(\) - 返回单击滑块时滑块值更改的步数。

Slider:IsEnabled\(\) - 返回滑块的启用状态。

Slider:SetMinMaxValues\(min, max\) - 设置滑块的边界。

[Slider:SetObeyStepOnDrag](https://wow.gamepedia.com/API_Slider_SetObeyStepOnDrag)\(obeyStep\) - 设置滑块是否将值约束为拖动时的值步长。

Slider:SetOrientation\("orientation"\) - "HORIZONTAL" 或 "VERTICAL".

Slider:SetThumbTexture\(texture or "texturePath"\)

Slider:SetValue\(value\) - 设置滑块的值。也会导致拇指在第一次通话时显示。

[Slider:SetValueStep](https://wow.gamepedia.com/API_Slider_SetValueStep)\(value\) - 设置滑块的步长。

[Slider:SetStepsPerPage](https://wow.gamepedia.com/API_Slider_SetStepsPerPage)\(steps\) - 当用户在滑块的跟踪区域内单击时控制滑块行为。

