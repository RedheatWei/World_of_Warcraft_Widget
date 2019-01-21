### 模型

###### 用于显示真实的3D网格几何图形作为UI的一部分。有关详细信息，请参阅[模型对象](https://wow.gamepedia.com/UIOBJECT_Model)

###### 模型具有[UIObject](https://wow.gamepedia.com/Widget_API#UIObject)，[Region](https://wow.gamepedia.com/Widget_API#Region)和[Frame](https://wow.gamepedia.com/Widget_API#Frame)的所有方法，以及以下内容：

Model:AdvanceTime\(\)

Model:ClearFog\(\) - 删除渲染中当前处于活动状态的所有雾化效果。

Model:ClearModel\(\) - 从模型中删除所有几何体（即使其为空）

[Model:GetFacing](https://wow.gamepedia.com/API_Model_GetFacing)\(\) - 返回模型面向的方向。

Model:GetFogColor\(\) - 获取雾颜色（r，g，b，a） -  1.11中新增。

Model:GetFogFar\(\) - 获取雾远距离 - 1.11中新增。

Model:GetFogNear\(\) - 获取距离附近的雾 - 1.11中新增。

Model:GetLight\(\) -获取模型的灯光规范，返回与SetLight方法兼容的结果列表 - 1.11中新增。

[Model:GetModelFileID](https://wow.gamepedia.com/API_Model_GetModelFileID)\(\) - 获取此Model的模型文件ID -  7.0新增, 替换 Model:GetModel\(\).

Model:GetModelScale\(\) - 返回当前网格缩放系数。

Model:GetPosition\(\) - 将网格的当前位置返回为x，y，z

Model:ReplaceIconTexture\("texture"\)

[Model:SetCamera](https://wow.gamepedia.com/API_Model_SetCamera)\(index\) - 选择预定义的摄像头。

[Model:SetFacing](https://wow.gamepedia.com/API_Model_SetFacing)\(facing\) - 设置模型面向的方向。

[Model:SetFogColor](https://wow.gamepedia.com/API_Model_SetFogColor)\(r, g, b\[, a\]\) - 设置雾色并启用雾化。

[Model:SetFogFar](https://wow.gamepedia.com/API_Model_SetFogFar)\(value\) - 设置雾化的远剪裁平面距离。

[Model:SetFogNear](https://wow.gamepedia.com/API_Model_SetFogNear)\(value\) - 设置雾化的近剪裁平面距离。

Model:SetGlow\(...\) -

[Model:SetLight](https://wow.gamepedia.com/API_Model_SetLight)\(enabled\[, omni, dirX, dirY, dirZ, ambIntensity\[, ambR, ambG, ambB\[, dirIntensity\[, dirR, dirG, dirB\]\]\]\]\) - 放置用于渲染的光源

[Model:SetModel](https://wow.gamepedia.com/API_Model_SetModel)\("file"\) - 设置框架中显示的网格。

[Model:SetModelByFileID](https://wow.gamepedia.com/API_Model_SetModelByFileID)\("fileID"\) - 使用文件ID设置框架中显示的网格。

Model:SetModelScale\(scale\) - 在渲染之前设置网格的比例因子。

[Model:SetPosition](https://wow.gamepedia.com/API_Model_SetPosition)\(x, y, z\) - 在网格坐标系内设置网格的位置。

[Model:SetSequence](https://wow.gamepedia.com/API_Model_SetSequence)\(sequence\) - 设置要播放的动画。

Model:SetSequenceTime\(sequence, time\)

[Model:SetAnimation](https://wow.gamepedia.com/API_Model_SetAnimation)\(animationID, \[variationID\]\)

[Model:HasAnimation](https://wow.gamepedia.com/API_Model_HasAnimation)\(animationID\)

[Mode:FreezeAnimation](https://wow.gamepedia.com/API_Model_FreezeAnimation)\(animationID, \[variationID\], \[animationFrame\]\)

