# 编辑序列帧动画

我们刚刚了解了属性帧的操作，现在来看看具体怎么创建一个帧动画。

## 为节点新增 Sprite 组件

首先我们需要让节点正常显示纹理，所以需要为节点添加 Sprite 组件。在 **层级管理器** 中选中节点，然后点击 **属性检查器** 最下方的 **添加组件** 按钮，选择 **渲染组件 -> Sprite**，即可添加 Sprite 组件到节点上。

## 在属性列表中添加 cc.Sprite.spriteFrame

节点可以正常显示纹理后，还需要为纹理创建一个动画轨道。在 **动画编辑器** 中点击 **Add Property**，然后选择 `cc.Sprite.spriteFrame`。

## 添加帧

从 **资源管理器** 中将纹理拖拽到属性帧区域，放在 `cc.Sprite.spriteFrame`  轨道上。再将下一帧需要显示的纹理拖到指定位置，然后点击播放就可以预览刚刚创建的动画了。