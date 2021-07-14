# 简介

我不知道这个东西应该叫什么名字，是多年前做工厂控制相关时开发的一个组件，他用于配置设备平面图，以及显示设备状态的控制面板。

组件采用WinForm的GDI+技术进行绘图，技术上有点陈旧，不过设计还算马虎，后来我有使用相同的设计比较容易的移植到HTML5的Canvas中。

# 基本功能

- 支持移动缩放
- 支持多图层
- 正向和反向框选
- 元素调整大小
- 元素状态动态刷新
- 鼠标悬停检测
- 元素快速定位
- 支持数万元素显示
- 等等...

![image](https://user-images.githubusercontent.com/7581981/125632732-811618bc-d8fd-4ec0-ae41-a26e0d1bc477.png)


# 文件夹

- Canvas

画布核心代码，提供缩放，框选等组件的和兴功能

- Painter

业务中使用的组件，图层等代码，可以在这里进行扩展需要显示的元素
