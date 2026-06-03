---
title: "AnswerSheetConfig"
second_title: "Aspose.OMR 适用于 .NET API 参考"
description: "表示 AnswerSheet 元素。它允许在列和行中添加选择框。如果希望在页面上容纳大量问题，因为这些问题彼此靠近，请使用答案表。"
type: docs
weight: 250
url: /zh/net/aspose.omr.generation.config.elements/answersheetconfig/
---
## AnswerSheetConfig class

表示 AnswerSheet 元素。它允许在列和行中添加选择框。如果希望在页面上容纳大量问题，因为这些问题彼此靠近，请使用答案表。

```csharp
public class AnswerSheetConfig : BaseConfig
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [AnswerSheetConfig](answersheetconfig)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AnswersCount](../../aspose.omr.generation.config.elements/answersheetconfig/answerscount) { get; set; } | 答题卡中每个问题的答案选项数量。 |
| [AnswersValues](../../aspose.omr.generation.config.elements/answersheetconfig/answersvalues) { get; set; } | 每个值表示气泡内的符号。必须与 [`AnswersCount`](./answerscount) 的数量相同。示例：new string[] {\"A\", \"B\", \"C\", \"D\"} 示例：new string[] {\"1\", \"2\", \"3\", \"4\"} |
| [BubbleType](../../aspose.omr.generation.config.elements/answersheetconfig/bubbletype) { get; set; } | 气泡的类型 |
| [Column](../../aspose.omr.generation.config.elements/answersheetconfig/column) { get; set; } | 指示在第几列绘制答题卡 |
| [ColumnsCount](../../aspose.omr.generation.config.elements/answersheetconfig/columnscount) { get; set; } | 设置要绘制的列数。 |
| [ElementsCount](../../aspose.omr.generation.config.elements/answersheetconfig/elementscount) { get; set; } | 确定答题卡中的问题总数。 |
| [Multiselect](../../aspose.omr.generation.config.elements/answersheetconfig/multiselect) { get; set; } | 允许每个问题选择多个答案，覆盖 [`Multiselect`](../../aspose.omr.generation/globalpagesettings/multiselect) 中的默认设置。 |
| override [Name](../../aspose.omr.generation.config.elements/answersheetconfig/name) { get; set; } | 答题卡名称 |
| [StartId](../../aspose.omr.generation.config.elements/answersheetconfig/startid) { get; set; } | 问题编号的起始索引 |
| override [Type](../../aspose.omr.generation.config.elements/answersheetconfig/type) { get; set; } | OMR 元素的类型。JSON 序列化所需的字段。 |
| [VerticalMargin](../../aspose.omr.generation.config.elements/answersheetconfig/verticalmargin) { get; set; } | 答题卡的垂直边距。以像素为单位设置。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| [BubbleSize](../../aspose.omr.generation.config.elements/answersheetconfig/bubblesize) | 气泡的大小 |

### 另请参阅

* class [BaseConfig](../../aspose.omr.generation.config/baseconfig)
* namespace [Aspose.OMR.Generation.Config.Elements](../../aspose.omr.generation.config.elements)
* assembly [Aspose.OMR](../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OMR.dll 生成 -->
