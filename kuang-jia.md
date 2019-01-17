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

Frame:GetBackdrop\(\) - Creates and returns a backdrop table suitable for use in SetBackdrop - New in 1.11.

Frame:GetBackdropBorderColor\(\) - Gets the frame's backdrop border color \(r, g, b, a\)- New in 1.11.

Frame:GetBackdropColor\(\) - Gets the frame's backdrop color \(r, g, b, a\)- New in 1.11.

[Frame:GetChildren](https://wow.gamepedia.com/API_Frame_GetChildren)\(\) - Get the list of "children" \(frames and things derived from frames\) of this frame.

[Frame:GetClampRectInsets](https://wow.gamepedia.com/API_Frame_GetClampRectInsets)\(\) - Gets the modifiers to the frame's rectangle used for clamping the frame to screen.

Frame:GetDepth\(\) - New in 3.0.8

Frame:GetEffectiveAlpha\(\) - Returns the effective alpha of a frame. - Since 2.1.

Frame:GetEffectiveDepth\(\) - New in 3.0.8

[Frame:GetEffectiveScale](https://wow.gamepedia.com/API_Frame_GetEffectiveScale)\(\) - Get the scale factor of this object relative to the root window.

[Frame:GetFrameLevel](https://wow.gamepedia.com/API_Frame_GetFrameLevel)\(\) - Get the level of this frame.

[Frame:GetFrameStrata](https://wow.gamepedia.com/API_Frame_GetFrameStrata)\(\) - Get the strata of this frame.

[Frame:GetFrameType](https://wow.gamepedia.com/API_Frame_GetFrameType)\(\) - Get the type of this frame.

Frame:GetHitRectInsets\(\) - Gets the frame's hit rectangle inset distances \(l, r, t, b\) - new in 1.11.

[Frame:GetID](https://wow.gamepedia.com/API_Frame_GetID)\(\) - Get the ID of this frame.

Frame:GetMaxResize\(\) - Gets the frame's maximum allowed resize bounds \(w, h\) - new in 1.11.

Frame:GetMinResize\(\) - Gets the frame's minimum allowed resize bounds \(w, h\) - new in 1.11.

Frame:GetNumChildren\(\) - Get the number of "children" \(frames and things derived from frames\) this frame has.

Frame:GetNumRegions\(\) - Return the number of "regions" \(fontstrings, textures\) belonging to this frame.

[Frame:GetPropagateKeyboardInput](https://wow.gamepedia.com/API_Frame_GetPropagateKeyboardInput)\(\) - Returns if keyboard inputs are being propagated.

Frame:GetRegions\(\) - Return the "regions" \(fontstrings, textures\) of the frame \(multiple return values\) belonging to this frame.

Frame:GetScale\(\) - Get the scale factor of this object relative to its parent.

Frame:GetScript\("handler"\) - Get the function for one of this frame's handlers.

Frame:GetTitleRegion\(\) - Return the frame's title region - New in 1.11.

Frame:HasScript\("handler"\) - Return true if the frame can be given a handler of the specified type \(NOT whether it actually HAS one, use GetScript for that\) - Since 1.8.

[Frame:HookScript](https://wow.gamepedia.com/API_Frame_HookScript)\("handler", function\) - Hook a secure frame script.

Frame:IgnoreDepth\(ignoreFlag\) - New in 3.0.8

[Frame:IsClampedToScreen](https://wow.gamepedia.com/API_Frame_IsClampedToScreen)\(\) - Gets whether the frame is prohibited from being dragged off screen.

[Frame:IsEventRegistered](https://wow.gamepedia.com/API_Frame_IsEventRegistered)\("event"\) - Returns true if the given event is registered to the frame.

[Frame:IsFrameType](https://wow.gamepedia.com/API_Frame_IsFrameType)\("type"\) - Determine if this frame is of the specified type, or a subclass of that type.

Frame:IsIgnoringDepth\(\) - New in 3.0.8

Frame:IsKeyboardEnabled\(\) - Get whether this frame will get keyboard input. - New in 1.11.

Frame:IsMouseEnabled\(\) - Get whether this frame will get mouse input. - New in 1.11.

Frame:IsMouseWheelEnabled\(\) - Get whether this frame will get mouse wheel notifications. New in 1.11.

[Frame:IsMovable](https://wow.gamepedia.com/API_Frame_IsMovable)\(\) - Determine if the frame can be moved.

Frame:IsResizable\(\) - Determine if the frame can be resized.

Frame:IsToplevel\(\) - Get whether the frame is set as toplevel - New in 1.10.2.

[Frame:IsUserPlaced](https://wow.gamepedia.com/API_Frame_IsUserPlaced)\(\) - Determine if this frame has been relocated by the user.

Frame:Lower\(\) - Lower this frame behind other frames.

Frame:Raise\(\) - Raise this frame above other frames.

[Frame:RegisterAllEvents](https://wow.gamepedia.com/API_Frame_RegisterAllEvents)\(\) - Register this frame to receive all events \(For debugging purposes only!\)

[Frame:RegisterEvent](https://wow.gamepedia.com/API_Frame_RegisterEvent)\("event"\) - Indicate that this frame should be notified when event occurs.

[Frame:RegisterUnitEvent](https://wow.gamepedia.com/API_Frame_RegisterUnitEvent)\("event", "unit1"\[, "unit2"\]\) - Indicate that this frame should be notified when event occur for specified units only. \(New in 5.0.4\)

[Frame:RegisterForDrag](https://wow.gamepedia.com/API_Frame_RegisterForDrag)\("buttonType"\[,"buttonType"...\]\) - Inidicate that this frame should be notified of drag events for the specified buttons.

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

