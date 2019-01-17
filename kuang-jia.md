### 框架

###### 有关详细信息，请参阅[Frame object information](https://wow.gamepedia.com/UIOBJECT_Frame)。

###### Frame具有[UIObject](https://wow.gamepedia.com/Widget_API#UIObject)和[Region](https://wow.gamepedia.com/Widget_API#Region)的所有方法，以及以下内容：

[Frame:CreateFontString](https://wow.gamepedia.com/API_Frame_CreateFontString)\(\["name"\[,"[layer](https://wow.gamepedia.com/Layer)"\[,"inheritsFrom"\]\]\]\) - 创建并返回一个新的FontString作为此Frame的子级 - 可以在1.11中实例化虚拟。

Frame:CreateLine\(\["name"\[,"[layer](https://wow.gamepedia.com/Layer)"\[,"inheritsFrom"\[,subLayer\]\]\]\]\) - 创建并返回一个新Line作为此Frame的子级。

Frame:CreateMaskTexture\(\["name"\[,"[layer](https://wow.gamepedia.com/Layer)"\[,"inheritsFrom"\[,subLayer\]\]\]\]\) - 创建并返回一个新的MaskTexture作为此Frame的子级。

[Frame:CreateTexture](https://wow.gamepedia.com/API_Frame_CreateTexture)\(\["name"\[,"[layer](https://wow.gamepedia.com/Layer)"\[,"inheritsFrom"\[,subLayer\]\]\]\]\) - 创建并返回一个新的Texture作为此Frame的子级。

[Frame:CreateTitleRegion](https://wow.gamepedia.com/API_Frame_CreateTitleRegion)\(\) - 如果框架没有标题区域，则为框架创建。-  1.11中的新功能

Frame:DisableDrawLayer\("[layer](https://wow.gamepedia.com/Layer)"\) - 禁用在指定绘制图层中渲染“区域”（fontstrings，textures）。

Frame:EnableDrawLayer\("[layer](https://wow.gamepedia.com/Layer)"\) - 在指定的绘图层中启用“区域”（fontstrings，textures）的渲染。

[Frame:EnableKeyboard](https://wow.gamepedia.com/API_Frame_EnableKeyboard)\(enableFlag\) -设置此框架是否将获得键盘输入。

[Frame:EnableMouse](https://wow.gamepedia.com/API_Frame_EnableMouse)\(enableFlag\) - 设置此框架是否将获得鼠标输入。

Frame:EnableMouseWheel\(enableFlag\) - 设置此框架是否将获得鼠标滚轮通知。

[Frame:GetAttribute](https://wow.gamepedia.com/API_Frame_GetAttribute)\(prefix, name, suffix\) - 返回\(prefix..name..suffix\)的第一个现有属性，\(“\*”.. name..suffix\)，\(prefix..name ..“\*”\)，\(“\*”.. name ..“\*“\)， \(name\)。

Frame:GetBackdrop\(\) - 创建并返回适合在SetBackdrop中使用的背景表 -  1.11中的新增功能。

Frame:GetBackdropBorderColor\(\) - 获取框架的背景边框颜色（r，g，b，a） -  1.11中的新增内容。

Frame:GetBackdropColor\(\) - 获取框架的背景颜色（r，g，b，a） -  1.11中的新增内容。

[Frame:GetChildren](https://wow.gamepedia.com/API_Frame_GetChildren)\(\) - 获取此框架的“子”列表（框架和从框架派生的东西）。

[Frame:GetClampRectInsets](https://wow.gamepedia.com/API_Frame_GetClampRectInsets)\(\) - 获取用于将框架堆叠到屏幕的框架矩形的修饰符。

Frame:GetDepth\(\) - 3.0.8中的新功能

Frame:GetEffectiveAlpha\(\) - 返回框架的有效alpha。- 自2.1。

Frame:GetEffectiveDepth\(\) - 3.0.8中的新功能

[Frame:GetEffectiveScale](https://wow.gamepedia.com/API_Frame_GetEffectiveScale)\(\) - 获取此对象相对于根窗口的比例因子。

[Frame:GetFrameLevel](https://wow.gamepedia.com/API_Frame_GetFrameLevel)\(\) - 获得此框架的级别。

[Frame:GetFrameStrata](https://wow.gamepedia.com/API_Frame_GetFrameStrata)\(\) - 得到这个框架的层次。

[Frame:GetFrameType](https://wow.gamepedia.com/API_Frame_GetFrameType)\(\) - 获取此框架的类型。

Frame:GetHitRectInsets\(\) - 获取框架的命中矩形插入距离（l，r，t，b） -  1.11中的新值。

[Frame:GetID](https://wow.gamepedia.com/API_Frame_GetID)\(\) - 获取此框架的ID。

Frame:GetMaxResize\(\) - 获取框架的最大允许调整大小边界（w，h） -  1.11中的新值。

Frame:GetMinResize\(\) - 获取框架的最小允许调整大小边界（w，h） -  1.11中的新值。

Frame:GetNumChildren\(\) - 获取此框架具有的“children”（框架和从框架派生的东西）的数量。

Frame:GetNumRegions\(\) - 返回属于此框架的“区域”（fontstrings，textures）的数量。

[Frame:GetPropagateKeyboardInput](https://wow.gamepedia.com/API_Frame_GetPropagateKeyboardInput)\(\) - 返回键盘输入是否正在传播。

Frame:GetRegions\(\) - 返回属于此框架的框架的“区域”（fontstrings，textures）（多个返回值）。

Frame:GetScale\(\) - 获取此对象相对于其父对象的比例因子。

Frame:GetScript\("handler"\) - 获取此框架处理程序之一的功能。

Frame:GetTitleRegion\(\) - 返回框架的标题区域 -  1.11中的新增内容。

Frame:HasScript\("handler"\) - 如果框架可以被赋予指定类型的处理程序，则返回true（不管它是否真的是一个，使用GetScript） - 从1.8开始。

[Frame:HookScript](https://wow.gamepedia.com/API_Frame_HookScript)\("handler", function\) - 挂钩安全框架脚本。

Frame:IgnoreDepth\(ignoreFlag\) - 3.0.8中的新功能

[Frame:IsClampedToScreen](https://wow.gamepedia.com/API_Frame_IsClampedToScreen)\(\) - 获取是否禁止将框架拖出屏幕。

[Frame:IsEventRegistered](https://wow.gamepedia.com/API_Frame_IsEventRegistered)\("event"\) - 如果给定事件已注册到框架，则返回true。

[Frame:IsFrameType](https://wow.gamepedia.com/API_Frame_IsFrameType)\("type"\) - 确定此框架是否为指定类型或该类型的子类。

Frame:IsIgnoringDepth\(\) - 3.0.8中的新功能

Frame:IsKeyboardEnabled\(\) - 获取此框架是否将获得键盘输入。-  1.11中的新功能。

Frame:IsMouseEnabled\(\) - 获取此框架是否将获得鼠标输入。-  1.11中的新功能。

Frame:IsMouseWheelEnabled\(\) - 获取此框架是否将获得鼠标滚轮通知。1.11中的新功能。

[Frame:IsMovable](https://wow.gamepedia.com/API_Frame_IsMovable)\(\) - 确定框架是否可以移动。

Frame:IsResizable\(\) - 确定是否可以调整框架的大小。

Frame:IsToplevel\(\) - 获取帧是否设置为toplevel  -  1.10.2中的新增内容。

[Frame:IsUserPlaced](https://wow.gamepedia.com/API_Frame_IsUserPlaced)\(\) - 确定用户是否已重新定位此框架。

Frame:Lower\(\) - 将此框架放在其他框架后面。

Frame:Raise\(\) - 将此框架提升到其他框架上方。

[Frame:RegisterAllEvents](https://wow.gamepedia.com/API_Frame_RegisterAllEvents)\(\) - 注册此框架以接收所有事件（仅用于调试目的！）

[Frame:RegisterEvent](https://wow.gamepedia.com/API_Frame_RegisterEvent)\("event"\) - 指示事件发生时应通知此框架。

[Frame:RegisterUnitEvent](https://wow.gamepedia.com/API_Frame_RegisterUnitEvent)\("event", "unit1"\[, "unit2"\]\) - 指示仅在指定单元发生事件时应通知此框架。（5.0.4中的新功能）

[Frame:RegisterForDrag](https://wow.gamepedia.com/API_Frame_RegisterForDrag)\("buttonType"\[,"buttonType"...\]\) - 指示应该通知此框架指定按钮的拖动事件。

Frame:SetAttribute\("name", value\) - Sets an attribute on the frame.

[Frame:SetBackdrop](https://wow.gamepedia.com/API_Frame_SetBackdrop)\(\[backdropTable\]\) - Set the backdrop of the frame according to the specification provided.

[Frame:SetBackdropBorderColor](https://wow.gamepedia.com/API_Frame_SetBackdropBorderColor)\(r, g, b\[, a\]\) - Set the frame's backdrop's border's color.

[Frame:SetBackdropColor](https://wow.gamepedia.com/API_Frame_SetBackdropColor)\(r, g, b\[, a\]\) - Set the frame's backdrop color.

[Frame:SetClampedToScreen](https://wow.gamepedia.com/API_Frame_SetClampedToScreen)\(clamped\) - Set whether the frame is prohibited from being dragged off screen.

[Frame:SetClampRectInsets](https://wow.gamepedia.com/API_Frame_SetClampRectInsets)\(left, right, top, bottom\) - Modify the frame's rectangle used to prevent dragging offscreen.

Frame:SetClipsChildren\(clipped\) - Set the frame clipping its children.

Frame:SetDepth\(depth\) - New in 3.0.8

[Frame:SetFrameLevel](https://wow.gamepedia.com/API_Frame_SetFrameLevel)\(level\) - Set the level of this frame \(determines which of overlapping frames shows on top\).

[Frame:SetFrameStrata](https://wow.gamepedia.com/API_Frame_SetFrameStrata)\("strata"\) - Set the strata of this frame.

[Frame:SetHitRectInsets](https://wow.gamepedia.com/API_Frame_SetHitRectInsets)\(left, right, top, bottom\) - Set the inset distances for the frame's hit rectangle.

[Frame:SetID](https://wow.gamepedia.com/API_Frame_SetID)\(id\) - Set the ID of this frame.

[Frame:SetMaxResize](https://wow.gamepedia.com/API_Frame_SetMaxResize)\(maxWidth, maxHeight\) - Set the maximum dimensions this frame can be resized to.

[Frame:SetMinResize](https://wow.gamepedia.com/API_Frame_SetMinResize)\(minWidth, minHeight\) - Set the minimum dimensions this frame can be resized to.

[Frame:SetMovable](https://wow.gamepedia.com/API_Frame_SetMovable)\(isMovable\) - Set whether the frame can be moved.

[Frame:SetPropagateKeyboardInput](https://wow.gamepedia.com/API_Frame_SetPropagateKeyboardInput)\(propagate\) - Sets whether to propagate keyboard input to other frames.Note: Only OnKeyDown will fire and only for non-modifier keys

Frame:SetResizable\(isResizable\) - Set whether the frame can be resized.

[Frame:SetScale](https://wow.gamepedia.com/API_Frame_SetScale)\(scale\) - Set the scale factor of this frame relative to its parent.

[Frame:SetScript](https://wow.gamepedia.com/API_Frame_SetScript)\("handler", function\) - Set the function to use for a handler on this frame.

Frame:SetToplevel\(isTopLevel\) - Set whether the frame should raise itself when clicked - New in 1.10.2.

[Frame:SetUserPlaced](https://wow.gamepedia.com/API_Frame_SetUserPlaced)\(isUserPlaced\) - Set whether the frame has been relocated by the user \(and will thus be saved in the layout cache\).

[Frame:StartMoving](https://wow.gamepedia.com/API_Frame_StartMoving)\(\) - Start moving this frame.

Frame:StartSizing\("point"\) - Start sizing this frame using the specified anchor point.

[Frame:StopMovingOrSizing](https://wow.gamepedia.com/API_Frame_StopMovingOrSizing)\(\) - Stop moving and/or sizing this frame.

[Frame:UnregisterAllEvents](https://wow.gamepedia.com/API_Frame_UnregisterAllEvents)\(\) - Indicate that this frame should no longer be notified when any events occur.

[Frame:UnregisterEvent](https://wow.gamepedia.com/API_Frame_UnregisterEvent)\("event"\) - Indicate that this frame should no longer be notified when event occurs.

