### UI对象

###### 这是一个无法实际创建的抽象UI对象类型。它是所有UI对象的基础，并汇集了一些常用方法，这些方法在所有窗口小部件类型中具有相同的行为。

Object:GetParent\(\) - 移自Region:GetParent\(\). 这与旧版本基本相同，只是您不能再假设您的对象在其某个层次结构中具有Frame类型。

UIObject:GetAlpha\(\) - 返回此对象的alpha（不透明度）值。

UIObject:GetName\(\) - 返回对象名称。

UIObject:GetObjectType\(\) - 返回对象类型。

[UIObject:IsForbidden](https://wow.gamepedia.com/API_UIObject_IsForbidden)\(\) - 返回是否禁止与窗口小部件的不安全交互。

UIObject:IsObjectType\("type"\) - 确定此对象是指定类型还是该类型的子类。

[UIObject:SetAlpha](https://wow.gamepedia.com/API_UIObject_SetAlpha)\(alpha\) - 设置对象的alpha（不透明度）值。

