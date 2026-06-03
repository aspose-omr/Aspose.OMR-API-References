---
title: "VerticalChoiceBoxConfig"
second_title: "Aspose.OMR 适用于 .NET API 参考"
description: "VerticalChoiceBox 由一个 AnswerConfig./answerconfig 元素组成，该元素包含简短的响应，以及 ContentConfig../aspose.omr.generation.config.elements/contentconfig 元素，详细描述响应选项。它还可以包含一个 WriteInConfig../aspose.omr.generation.config.elements/writeinconfig 元素，用户可以在其中输入自己的答案。"
type: docs
weight: 460
url: /zh/net/aspose.omr.generation.config.elements.parents/verticalchoiceboxconfig/
---
## VerticalChoiceBoxConfig class

VerticalChoiceBox 由一个 [`AnswerConfig`](../answerconfig) 元素组成，该元素包含简短的响应，以及 [`ContentConfig`](../../aspose.omr.generation.config.elements/contentconfig) 元素，详细描述响应选项。它还可以包含一个 [`WriteInConfig`](../../aspose.omr.generation.config.elements/writeinconfig) 元素，用户可以在其中输入自己的答案。

```csharp
public class VerticalChoiceBoxConfig : ParentConfig
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [VerticalChoiceBoxConfig](verticalchoiceboxconfig)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| override [Children](../../aspose.omr.generation.config.elements.parents/verticalchoiceboxconfig/children) { get; set; } | 子 OMR 元素。大多数情况下位于父元素内部或下方。 |
| override [Name](../../aspose.omr.generation.config.elements.parents/verticalchoiceboxconfig/name) { get; set; } | Question 的值 |
| [Threshold](../../aspose.omr.generation.config.elements.parents/verticalchoiceboxconfig/threshold) { get; set; } | 气泡被视为已标记的像素百分比。如果提供，则覆盖识别期间提供的全局阈值 |
| [TopPadding](../../aspose.omr.generation.config.elements.parents/verticalchoiceboxconfig/toppadding) { get; set; } | 像素数量。可用于在元素上方添加额外空间。或通过设置负值（例如 -40）移除已有空间 |
| override [Type](../../aspose.omr.generation.config.elements.parents/verticalchoiceboxconfig/type) { get; set; } | OMR 元素的类型。JSON 序列化所需的字段。 |

### 另请参阅

* class [ParentConfig](../../aspose.omr.generation.config/parentconfig)
* namespace [Aspose.OMR.Generation.Config.Elements.Parents](../../aspose.omr.generation.config.elements.parents)
* assembly [Aspose.OMR](../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OMR.dll 生成 -->
