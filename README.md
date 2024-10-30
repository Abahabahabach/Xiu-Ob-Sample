## 介绍

- 第一次尝试制作一个obsidian的插件，功能很简单，但恰好可以满足我自己的需求
- 调用 Mathpix 的 OCR，将你笔记内的图片转换为 Latex 公式
- 可以的单个转换、自动转换和批量转换

----

## 基本使用

### 设置项

填入你的 Mathpix 密钥即可开始使用

### 单个转换

选中图片链接，在命令面板使用命令`OCR选中图片`，即可让 OCR 识别的结果直接替换图片

### 批量转换

在笔记内部打开命令面板，选择`OCR笔记中的所有图片`，即可替换该篇笔记内所有的图片为识别的结果

### 自动转换

在侧边按钮启用`切换自动OCR模式`，这会检测任何你在笔记内添加图片的行为，并且自动将你插入的图片替换为OCR的结果。再次点击则关闭该功能。