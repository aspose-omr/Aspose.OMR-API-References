---
title: "BubbleArrayConfig"
second_title: "Aspose.OMR 适用于 .NET API 参考"
description: "将可能的答案显示为每个圆形气泡内的选项。只能在 CustomRowConfig./customrowconfig 中使用。"
type: docs
weight: 310
url: /zh/net/aspose.omr.generation.config.elements.customanswersheet/bubblearrayconfig/
---
## BubbleArrayConfig class

将可能的答案显示为每个圆形（气泡）内的选项。只能在 [`CustomRowConfig`](../customrowconfig) 中使用。

```csharp
public class BubbleArrayConfig : BaseConfig
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [BubbleArrayConfig](bubblearrayconfig)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AnswersValues](../../aspose.omr.generation.config.elements.customanswersheet/bubblearrayconfig/answersvalues) { get; set; } | 每个值表示显示在气泡内部的符号以及气泡的数量。如果显示值与识别值不一致，请参阅 [`RecognitionValues`](./recognitionvalues)。示例：new string[] {"A", "B", "C", "D"} 示例：new string[] {"1", "2", "3", "4"} |
| [BubbleSize](../../aspose.omr.generation.config.elements.customanswersheet/bubblearrayconfig/bubblesize) { get; set; } | 气泡的大小 |
| [BubbleType](../../aspose.omr.generation.config.elements.customanswersheet/bubblearrayconfig/bubbletype) { get; set; } | 气泡的类型 |
| [FontFamily](../../aspose.omr.generation.config.elements.customanswersheet/bubblearrayconfig/fontfamily) { get; set; } | 文本的字体族 |
| [FontSize](../../aspose.omr.generation.config.elements.customanswersheet/bubblearrayconfig/fontsize) { get; set; } | 文本字体的大小 |
| [FontStyle](../../aspose.omr.generation.config.elements.customanswersheet/bubblearrayconfig/fontstyle) { get; set; } | 文本的样式 |
| [Height](../../aspose.omr.generation.config.elements.customanswersheet/bubblearrayconfig/height) { get; set; } | 覆盖气泡数组行的像素高度。部分可见或溢出的内容将被移除。详情请参阅 - [`Clip`](../../aspose.omr.generation.overflowactions/clip)。默认值为 -1。默认情况下，气泡数组的高度将自动缩放。 |
| [HorizontalPadding](../../aspose.omr.generation.config.elements.customanswersheet/bubblearrayconfig/horizontalpadding) { get; set; } | 气泡行内部左右两侧的额外像素数，默认值为 0 |
| override [Name](../../aspose.omr.generation.config.elements.customanswersheet/bubblearrayconfig/name) { get; set; } | 气泡数组的名称。不会参与元素的显示或生成。 |
| [RecognitionValues](../../aspose.omr.generation.config.elements.customanswersheet/bubblearrayconfig/recognitionvalues) { get; set; } | 每个条目会覆盖识别结果中的值，以关联 [`AnswersValues`](./answersvalues)，但不影响显示的值。如果未设置值，识别结果将使用来自 [`AnswersValues`](./answersvalues) 的显示值填充。示例：new List(4) {"A", "B", "C", "D"} 示例：new List(4) {"Dog", "Cat", "Turtle", "Dragon"} |
| [Threshold](../../aspose.omr.generation.config.elements.customanswersheet/bubblearrayconfig/threshold) { get; set; } | 覆盖在识别期间提供的全局阈值。像素百分比从 0 到 100，超过该比例的气泡被视为已标记。默认值为 -1。默认情况下将使用全局阈值。 |
| override [Type](../../aspose.omr.generation.config.elements.customanswersheet/bubblearrayconfig/type) { get; set; } | OMR 元素的类型。JSON 序列化所需的字段。 |
| [VerticalPadding](../../aspose.omr.generation.config.elements.customanswersheet/bubblearrayconfig/verticalpadding) { get; set; } | 气泡行内部上下两侧的额外像素数，默认值为 0。 |

### 另请参阅

* class [BaseConfig](../../aspose.omr.generation.config/baseconfig)
* namespace [Aspose.OMR.Generation.Config.Elements.CustomAnswerSheet](../../aspose.omr.generation.config.elements.customanswersheet)
* assembly [Aspose.OMR](../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OMR.dll 生成 -->
