### 区域

###### 这是一种无法实际创建的抽象对象类型。它汇集了许多常见方法，这些方法在所有窗口小部件类型中具有相同的行为。此对象包含一组与窗口小部件的大小，位置和可见性相关的方法。请注意，它与Frame:GetRegions\(\)等没有直接关系。

###### Region具有[UIObject](https://wow.gamepedia.com/Widget_API#UIObject)的所有方法，以及以下内容：

[Region:ClearAllPoints](https://wow.gamepedia.com/API_Region_ClearAllPoints)\(\) - 清除此对象的所有附着点。

Region:CreateAnimationGroup\(\["name"\[,"inheritsFrom"\]\]\) - 创建一个新的AnimationGroup并将其作为此Region的子项返回。-  3.1.0中的新功能

[Region:IsMouseOver](https://wow.gamepedia.com/API_Region_IsMouseOver)\(\[top, bottom, left, right\]\) - 检查鼠标是否在框架上（或在指定的偏移量内）。

Region:GetAnimationGroups\(\) - 返回作为此Region的子项的所有AnimationGroup。-  3.1.0中的新功能

[Region:GetBottom](https://wow.gamepedia.com/API_Region_GetBottom)\(\) - 获取此框架底边的y位置 - 于1.10移除。

Region:GetCenter\(\) - 获取此框架中心的坐标 - 于1.10移除。

[Region:GetHeight](https://wow.gamepedia.com/API_Region_GetHeight)\(\) - 获取此对象的高度。

[Region:GetLeft](https://wow.gamepedia.com/API_Region_GetLeft)\(\) - 获取此框架左边缘的x位置- 于1.10移除。

Region:GetNumPoints\(\) - 获取此框架的锚点数 - 1.10的新功能.

[Region:GetPoint](https://wow.gamepedia.com/API_Region_GetPoint)\(pointNum\) - 获取此框架的锚点的详细信息（point，relativeTo，relativePoint，xofs，yofs） - 1.10的新功能.

Region:GetRect\(\) - 获取框架的左，底部，宽度，高度。

[Region:GetRight](https://wow.gamepedia.com/API_Region_GetRight)\(\) - 获取此框架右边缘的x位置 - 于1.10移除。

[Region:GetTop](https://wow.gamepedia.com/API_Region_GetTop)\(\) - 获取此框架上边缘的y位置 - 于1.10移除。

[Region:GetWidth](https://wow.gamepedia.com/API_Region_GetWidth)\(\) - 获取此对象的宽度。

[Region:Hide](https://wow.gamepedia.com/API_Region_Hide)\(\) - 将此对象设置为隐藏（它及其所有子项将消失）。

Region:IsDragging\(\) - 如果正在拖动此Region或其Parent，则为True。-  3.1.0中的新功能

[Region:IsProtected](https://wow.gamepedia.com/API_Region_IsProtected)\(\) -确定是否可以通过战斗中受污染的代码以某种方式操纵此对象

[Region:IsShown](https://wow.gamepedia.com/API_Region_IsShown)\(\) - 确定是否显示此对象（如果其父级可见，则可见）。

[Region:IsVisible](https://wow.gamepedia.com/API_Region_IsVisible)\(\) - 获取对象是否在屏幕上可见（逻辑上（IsShown\(\) and GetParent\(\):sVisible\(\)））;

[Region:SetAllPoints](https://wow.gamepedia.com/API_Region_SetAllPoints)\(frame or "frameName"\) - 设置所有锚点以匹配指定框架的边缘 - Moved in 1.10.

[Region:SetHeight](https://wow.gamepedia.com/API_Region_SetHeight)\(height\) - 设置对象的高度。

Region:SetParent\(parent or "parentName"\) - 设置此框架的父级 - 于1.10移除。

[Region:SetPoint](https://wow.gamepedia.com/API_Region_SetPoint)\("point"\[,"relativeFrame" or relativeObject\[,"relativePoint"\[, xOfs\[, yOfs\]\]\]\]\) - 设置此对象的连接点 - 在1.10中更新。2.2坐标现在相对于最接近的锚点

Region:SetSize\(width,height\) - 将对象的宽度和高度设置为SetHeight和SetWidth，但是在一个函数中。

[Region:SetShown](https://wow.gamepedia.com/API_Region_SetShown)\(shownFlag\) - 显示或隐藏该区域。

[Region:SetWidth](https://wow.gamepedia.com/API_Region_SetWidth)\(width\) - 设置对象的宽度。

[Region:Show](https://wow.gamepedia.com/API_Region_Show)\(\) - 将此对象设置为显示（如果其父对象可见，则会显示该对象）。

Region:StopAnimating\(\) - 停止Region及其子节点上的所有活动动画。-  3.1.0中的新功能

