### 纹理

###### 有关详细信息，请参阅[Texture object information](https://wow.gamepedia.com/UIOBJECT_Texture)。纹理具有[UIObject](https://wow.gamepedia.com/Widget_API#UIObject)，[Region](https://wow.gamepedia.com/Widget_API#Region),[LayeredRegion](https://wow.gamepedia.com/Widget_API#LayeredRegion)的所有方法，以及以下内容：

Texture:AddMaskTexture\(maskTexture\)

[Texture:GetBlendMode](https://wow.gamepedia.com/API_Texture_GetBlendMode)\(\) - 返回SetBlendMode（）设置的混合模式

Texture:GetTexCoord\(\) - 获取映射到纹理角的8个纹理坐标 -  1.11中的新功能。

[Texture:GetTexture](https://wow.gamepedia.com/API_Texture_GetTexture)\(\) - 获取此纹理的当前纹理路径。

Texture:GetVertexColor\(\) - 获取纹理的顶点颜色。

[Texture:IsDesaturated](https://wow.gamepedia.com/API_Texture_IsDesaturated)\(\) - 获取此纹理的去饱和状态。-  1.11中的新功能

Texture:RemoveMaskTexture\(maskTexture\)

[Texture:SetBlendMode](https://wow.gamepedia.com/API_Texture_SetBlendMode)\("mode"\) - 设置纹理的[alphaMode](https://wow.gamepedia.com/AlphaMode).

[Texture:SetDesaturated](https://wow.gamepedia.com/API_Texture_SetDesaturated)\(flag\) - 设置是否应该在没有饱和的情况下显示此纹理（注意：这具有返回值）

[Texture:SetHorizTile](https://wow.gamepedia.com/API_Texture_SetHorizTile)\(horizTile\) - 设置窗口小部件是否应根据纹理和窗口小部件尺寸调整水平纹理坐标。

Texture:SetGradient\("orientation", minR, minG, minB, maxR, maxG, maxB\)

Texture:SetGradientAlpha\("orientation", minR, minG, minB, minA, maxR, maxG, maxB, maxA\)

[Texture:SetRotation](https://wow.gamepedia.com/API_Texture_SetRotation)\(angle, \[,cx, cy\]\) - Applies a counter-clockwise rotation to the texture.

[Texture:SetTexCoord](https://wow.gamepedia.com/API_Texture_SetTexCoord)\(minX, maxX, minY, maxY or ULx, ULy, LLx, LLy, URx, URy, LRx, LRy\) - 修改“纹理”小组件绘制的纹理区域。

[Texture:SetTexture](https://wow.gamepedia.com/API_Texture_SetTexture)\("filepath" or fileDataID\[, horizWrap\[, vertWrap\[, filterMode\]\]\]\) - 更改“纹理”小部件显示的纹理。

[Texture:SetColorTexture](https://wow.gamepedia.com/API_Texture_SetColorTexture)\(r, g, b\[, a\]\) - 更改纹理的颜色。

[Texture:SetHorizTile](https://wow.gamepedia.com/API_Texture_SetVertTile)\(horizTile\) - 设置窗口小部件是否应根据纹理和窗口小部件尺寸调整垂直纹理坐标。



##### 以下2个[API](https://wow.gamepedia.com/API)函数不是Texture方法，但也可能有用：

SetPortraitTexture\(texture, "unit"\) - 使用指定单位的肖像绘制Texture对象。

[SetPortraitToTexture](https://wow.gamepedia.com/API_SetPortraitToTexture)\(texture or "texture", "texturePath"\) - 设置要从应用圆形不透明蒙版的文件显示的纹理，使其看起来像人像。

  


  




