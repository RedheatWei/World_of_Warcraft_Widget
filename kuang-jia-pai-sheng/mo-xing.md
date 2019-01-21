### 模型

###### 用于显示真实的3D网格几何图形作为UI的一部分。有关详细信息，请参阅[模型对象](https://wow.gamepedia.com/UIOBJECT_Model)

###### 模型具有[UIObject](https://wow.gamepedia.com/Widget_API#UIObject)，[Region](https://wow.gamepedia.com/Widget_API#Region)和[Frame](https://wow.gamepedia.com/Widget_API#Frame)的所有方法，以及以下内容：

Model:AdvanceTime\(\)

Model:ClearFog\(\) - 删除渲染中当前处于活动状态的所有雾化效果。

Model:ClearModel\(\) - 从模型中删除所有几何体（即使其为空）

[Model:GetFacing](https://wow.gamepedia.com/API_Model_GetFacing)\(\) - Returns the direction the model is facing.

Model:GetFogColor\(\) - Gets the fog color \(r, g, b, a\) - New in 1.11.

Model:GetFogFar\(\) - Gets the fog far distance - New in 1.11.

Model:GetFogNear\(\) - Gets the fog near distance - New in 1.11.

Model:GetLight\(\) - Gets the light specification for the model, returns a list of results compatible with the SetLight method - New in 1.11.

[Model:GetModelFileID](https://wow.gamepedia.com/API_Model_GetModelFileID)\(\) - Gets the model file ID for this Model - New in 7.0, replaces Model:GetModel\(\).

Model:GetModelScale\(\) - Returns the current mesh scaling factor.

Model:GetPosition\(\) - Returns the current position of the mesh as x, y, z

Model:ReplaceIconTexture\("texture"\)

[Model:SetCamera](https://wow.gamepedia.com/API_Model_SetCamera)\(index\) - Select a pre-defined camera.

[Model:SetFacing](https://wow.gamepedia.com/API_Model_SetFacing)\(facing\) - Set the direction that the model is facing.

[Model:SetFogColor](https://wow.gamepedia.com/API_Model_SetFogColor)\(r, g, b\[, a\]\) - Set the fog color and enable fogging.

[Model:SetFogFar](https://wow.gamepedia.com/API_Model_SetFogFar)\(value\) - Set the far-clipping plane distance for fogging.

[Model:SetFogNear](https://wow.gamepedia.com/API_Model_SetFogNear)\(value\) - Set the near-clipping plane distance for fogging.

Model:SetGlow\(...\) -

[Model:SetLight](https://wow.gamepedia.com/API_Model_SetLight)\(enabled\[, omni, dirX, dirY, dirZ, ambIntensity\[, ambR, ambG, ambB\[, dirIntensity\[, dirR, dirG, dirB\]\]\]\]\) - Place the light source used for rendering

[Model:SetModel](https://wow.gamepedia.com/API_Model_SetModel)\("file"\) - Set the mesh that is displayed in the frame.

[Model:SetModelByFileID](https://wow.gamepedia.com/API_Model_SetModelByFileID)\("fileID"\) - Set the mesh that is displayed in the frame using a file ID.

Model:SetModelScale\(scale\) - Sets the scale factor for the mesh before rendering.

[Model:SetPosition](https://wow.gamepedia.com/API_Model_SetPosition)\(x, y, z\) - Set the position of the mesh inside the frame's coordinate system.

[Model:SetSequence](https://wow.gamepedia.com/API_Model_SetSequence)\(sequence\) - Set the animation to be played.

Model:SetSequenceTime\(sequence, time\)

[Model:SetAnimation](https://wow.gamepedia.com/API_Model_SetAnimation)\(animationID, \[variationID\]\)

[Model:HasAnimation](https://wow.gamepedia.com/API_Model_HasAnimation)\(animationID\)

[Mode:FreezeAnimation](https://wow.gamepedia.com/API_Model_FreezeAnimation)\(animationID, \[variationID\], \[animationFrame\]\)

  


