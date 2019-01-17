### 区域

###### 这是一种无法实际创建的抽象对象类型。它汇集了许多常见方法，这些方法在所有窗口小部件类型中具有相同的行为。此对象包含一组与窗口小部件的大小，位置和可见性相关的方法。请注意，它与Frame:GetRegions\(\)等没有直接关系。

###### Region具有[UIObject](https://wow.gamepedia.com/Widget_API#UIObject)的所有方法，以及以下内容：

[Region:ClearAllPoints](https://wow.gamepedia.com/API_Region_ClearAllPoints)\(\) - 清除此对象的所有附着点。

Region:CreateAnimationGroup\(\["name"\[,"inheritsFrom"\]\]\) - 创建一个新的AnimationGroup并将其作为此Region的子项返回。-  3.1.0中的新功能

[Region:IsMouseOver](https://wow.gamepedia.com/API_Region_IsMouseOver)\(\[top, bottom, left, right\]\) - 检查鼠标是否在框架上（或在指定的偏移量内）。

Region:GetAnimationGroups\(\) - 返回作为此Region的子项的所有AnimationGroup。-  3.1.0中的新功能

[Region:GetBottom](https://wow.gamepedia.com/API_Region_GetBottom)\(\) - 获取此框架底边的y位置 - Moved in 1.10。

Region:GetCenter\(\) - 获取此框架中心的坐标 - Moved in 1.10.

[Region:GetHeight](https://wow.gamepedia.com/API_Region_GetHeight)\(\) - 获取此对象的高度。

[Region:GetLeft](https://wow.gamepedia.com/API_Region_GetLeft)\(\) - 获取此框架左边缘的x位置- Moved in 1.10.

Region:GetNumPoints\(\) - 获取此框架的锚点数 - 1.10的新功能.

[Region:GetPoint](https://wow.gamepedia.com/API_Region_GetPoint)\(pointNum\) - 获取此框架的锚点的详细信息（point，relativeTo，relativePoint，xofs，yofs） - 1.10的新功能.

Region:GetRect\(\) - 获取框架的左，底部，宽度，高度。

[Region:GetRight](https://wow.gamepedia.com/API_Region_GetRight)\(\) - 获取此框架右边缘的x位置 - Moved in 1.10.

[Region:GetTop](https://wow.gamepedia.com/API_Region_GetTop)\(\) - 获取此框架上边缘的y位置 - Moved in 1.10.

[Region:GetWidth](https://wow.gamepedia.com/API_Region_GetWidth)\(\) - 获取此对象的宽度。

[Region:Hide](https://wow.gamepedia.com/API_Region_Hide)\(\) - Set this object to hidden \(it and all of its children will disappear\).

Region:IsDragging\(\) - True if this Region or its Parent is being dragged. - New in 3.1.0

[Region:IsProtected](https://wow.gamepedia.com/API_Region_IsProtected)\(\) - Determine if this object can be manipulated in certain ways by tainted code in combat or not

[Region:IsShown](https://wow.gamepedia.com/API_Region_IsShown)\(\) - Determine if this object is shown \(would be visible if its parent was visible\).

[Region:IsVisible](https://wow.gamepedia.com/API_Region_IsVisible)\(\) - Get whether the object is visible on screen \(logically \(IsShown\(\) and GetParent\(\):IsVisible\(\)\)\);

[Region:SetAllPoints](https://wow.gamepedia.com/API_Region_SetAllPoints)\(frame or "frameName"\) - Set all anchors to match edges of specified frame - Moved in 1.10.

[Region:SetHeight](https://wow.gamepedia.com/API_Region_SetHeight)\(height\) - Set the height of the object.

Region:SetParent\(parent or "parentName"\) - Set the parent for this frame - Moved in 1.10.

[Region:SetPoint](https://wow.gamepedia.com/API_Region_SetPoint)\("point"\[,"relativeFrame" or relativeObject\[,"relativePoint"\[, xOfs\[, yOfs\]\]\]\]\) - Set an attachment point of this object - Updated in 1.10. Since 2.2 cooordinates are now relative to the closest anchor point

Region:SetSize\(width,height\) - Sets the width and the height of the object as SetHeight and SetWidth do, but in one function.

[Region:SetShown](https://wow.gamepedia.com/API_Region_SetShown)\(shownFlag\) - Shows or hides the region.

[Region:SetWidth](https://wow.gamepedia.com/API_Region_SetWidth)\(width\) - Set the width of the object.

[Region:Show](https://wow.gamepedia.com/API_Region_Show)\(\) - Set this object to shown \(it will appear if its parent is visible\).

Region:StopAnimating\(\) - Stops any active animations on the Region and its children. - New in 3.1.

