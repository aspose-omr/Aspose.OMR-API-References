---
title: "WriteInConfig"
second_title: "Aspose.OMR 适用于 .NET API 参考"
description: "表示手写输入元素。用于手写字段。识别后剪裁为图片并放置在文件夹中。"
type: docs
weight: 580
url: /zh/net/aspose.omr.generation.config.elements/writeinconfig/
---
## WriteInConfig class

表示手写输入元素。用于手写字段。识别后剪裁为图片并放置在文件夹中。

```csharp
public class WriteInConfig : BaseConfig
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [WriteInConfig](writeinconfig)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Adaptive](../../aspose.omr.generation.config.elements/writeinconfig/adaptive) { get; set; } | 将绘制行为设置为自适应。自适应行为根据父级高度绘制writeIn。 |
| [Color](../../aspose.omr.generation.config.elements/writeinconfig/color) { get; set; } | [`Hint`](./hint) 的颜色 |
| [FontFamily](../../aspose.omr.generation.config.elements/writeinconfig/fontfamily) { get; set; } | [`Hint`](./hint) 的字体系列 |
| [FontSize](../../aspose.omr.generation.config.elements/writeinconfig/fontsize) { get; set; } | [`Hint`](./hint) 字体的大小 |
| [FontStyle](../../aspose.omr.generation.config.elements/writeinconfig/fontstyle) { get; set; } | [`Hint`](./hint) 的样式 |
| [Hint](../../aspose.omr.generation.config.elements/writeinconfig/hint) { get; set; } | 写入区域后的文本。默认使用 \"write-in\" |
| override [Name](../../aspose.omr.generation.config.elements/writeinconfig/name) { get; set; } | 写入区域的名称以及识别后图片的名称。 |
| [Required](../../aspose.omr.generation.config.elements/writeinconfig/required) { get; set; } | 是否需要裁剪写入字段 |
| override [Type](../../aspose.omr.generation.config.elements/writeinconfig/type) { get; set; } | OMR 元素的类型。JSON 序列化所需的字段。 |

### 另请参阅

* class [BaseConfig](../../aspose.omr.generation.config/baseconfig)
* namespace [Aspose.OMR.Generation.Config.Elements](../../aspose.omr.generation.config.elements)
* assembly [Aspose.OMR](../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OMR.dll 生成 -->
