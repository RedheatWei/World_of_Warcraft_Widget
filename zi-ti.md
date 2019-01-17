### 字体

###### 这个对象是在1.10中引入来替换虚拟FontStrings的，它允许动态继承字体模板的变化。GameFontNormal等标准UI字体现在是Font对象。

###### Font拥有[UIObject](https://wow.gamepedia.com/Widget_API#UIObject)和[FontInstance](https://wow.gamepedia.com/Widget_API#FontInstance)的所有方法，以及以下内容：

Font:CopyFontObject\(otherFont\) - 将此字体的属性设置为其他字体对象的副本。

###### 以下[Frame Derivatives](https://wow.gamepedia.com/Widget_API#Frame_Derivatives)还继承[FontInstance](https://wow.gamepedia.com/Widget_API#FontInstance)类型的所有函数：

* [EditBox](https://wow.gamepedia.com/Widget_API#EditBox)
* [MessageFrame](https://wow.gamepedia.com/Widget_API#MessageFrame)
* [ScrollingMessageFrame](https://wow.gamepedia.com/Widget_API#ScrollingMessageFrame)

###### 以下[LayeredRegion Derivatives](https://wow.gamepedia.com/Widget_API#LayeredRegion_Derivatives)还继承了[FontInstance](https://wow.gamepedia.com/Widget_API#FontInstance)类型的所有函数：

* [FontString](https://wow.gamepedia.com/Widget_API#FontString)



