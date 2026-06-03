---
title: "CompositeGridConfig"
second_title: "Aspose.OMR 适用于 .NET API 参考"
description: "Grid 元素。生成气泡数组。每个填充的气泡代表复合值中的一个符号。所有标记的符号将连接成单一值。"
type: docs
weight: 290
url: /zh/net/aspose.omr.generation.config.elements/compositegridconfig/
---
## CompositeGridConfig class

Grid 元素。生成气泡数组。每个填充的气泡代表复合值中的一个符号。所有标记的符号将连接成单一值。

```csharp
public class CompositeGridConfig : BaseConfig
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [CompositeGridConfig](compositegridconfig)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BubbleType](../../aspose.omr.generation.config.elements/compositegridconfig/bubbletype) { get; set; } | 气泡的类型 |
| [Column](../../aspose.omr.generation.config.elements/compositegridconfig/column) { get; set; } | 当元素在多列父容器中绘制时 - 表示位置。 |
| [ColumnsCount](../../aspose.omr.generation.config.elements/compositegridconfig/columnscount) { get; set; } | 网格中的列数。每列代表结果值中的单个符号。列数必须等于 [`ExtraRow`](./extrarow) 的列数。 |
| [DisplayHint](../../aspose.omr.generation.config.elements/compositegridconfig/displayhint) { get; set; } | 是否显示此网格的名称 |
| [ExtraRow](../../aspose.omr.generation.config.elements/compositegridconfig/extrarow) { get; set; } | 列特定的值将放置在默认值之上 - [`Values`](./values)。以二维数组形式呈现。第一维 - 行。第二维 - 列。每个字符串表示气泡内的文本。如果字符串为 null，则不会放置气泡。列数必须等于 [`ColumnsCount`](./columnscount)。 |
| [GridAlignment](../../aspose.omr.generation.config.elements/compositegridconfig/gridalignment) { get; set; } | 网格对齐，指示网格应在页面上绘制的位置 |
| [GridOrientation](../../aspose.omr.generation.config.elements/compositegridconfig/gridorientation) { get; set; } | 网格方向：水平或垂直。指示子元素应如何定位 |
| [HeaderBorderColor](../../aspose.omr.generation.config.elements/compositegridconfig/headerbordercolor) { get; set; } | 方形边框颜色 |
| [HeaderBorderSize](../../aspose.omr.generation.config.elements/compositegridconfig/headerbordersize) { get; set; } | 方形边框大小 |
| [HeaderType](../../aspose.omr.generation.config.elements/compositegridconfig/headertype) { get; set; } | 指示在网格起始处绘制的元素类型 |
| override [Name](../../aspose.omr.generation.config.elements/compositegridconfig/name) { get; set; } | 网格名称。用于识别中的标识符 |
| [RotationAngle](../../aspose.omr.generation.config.elements/compositegridconfig/rotationangle) { get; set; } | 描述网格元素围绕自身轴的旋转。"90" - 将 CompositeGrid 旋转 90 度；"-90" - 将 CompositeGrid 旋转至 -90 度。 |
| override [Type](../../aspose.omr.generation.config.elements/compositegridconfig/type) { get; set; } | OMR 元素的类型。JSON 序列化所需的字段。 |
| [Values](../../aspose.omr.generation.config.elements/compositegridconfig/values) { get; set; } | 字符串集合，用于描述每列可能的符号。列特定的值放置在 [`ExtraRow`](./extrarow) 中。 |
| [XPosition](../../aspose.omr.generation.config.elements/compositegridconfig/xposition) { get; set; } | 页面上网格的 X 位置，覆盖对齐方式 |
| [YPosition](../../aspose.omr.generation.config.elements/compositegridconfig/yposition) { get; set; } | 页面上网格的 Y 位置，覆盖对齐方式 |

## 字段

| 名称 | 描述 |
| --- | --- |
| [BubbleSize](../../aspose.omr.generation.config.elements/compositegridconfig/bubblesize) | 气泡的大小 |
| [VerticalMargin](../../aspose.omr.generation.config.elements/compositegridconfig/verticalmargin) | 行间距 |

### 另请参阅

* class [BaseConfig](../../aspose.omr.generation.config/baseconfig)
* namespace [Aspose.OMR.Generation.Config.Elements](../../aspose.omr.generation.config.elements)
* assembly [Aspose.OMR](../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OMR.dll 生成 -->
