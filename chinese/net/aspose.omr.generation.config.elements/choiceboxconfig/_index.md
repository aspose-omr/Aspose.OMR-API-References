---
title: "ChoiceBoxConfig"
second_title: "Aspose.OMR 适用于 .NET API 参考"
description: "选择框是一个基本元素，表示具有固定数量答案的单个问题。"
type: docs
weight: 280
url: /zh/net/aspose.omr.generation.config.elements/choiceboxconfig/
---
## ChoiceBoxConfig class

选择框是一个基本元素，表示具有固定数量答案的单个问题。

```csharp
public class ChoiceBoxConfig : ParentConfig
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ChoiceBoxConfig](choiceboxconfig)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| override [Children](../../aspose.omr.generation.config.elements/choiceboxconfig/children) { get; set; } | 子 OMR 元素。[`ChoiceBoxAnswerConfig`](../choiceboxanswerconfig) |
| [Color](../../aspose.omr.generation.config.elements/choiceboxconfig/color) { get; set; } | 文本颜色 |
| [DisplayQuestionNumber](../../aspose.omr.generation.config.elements/choiceboxconfig/displayquestionnumber) { get; set; } | 是否显示此问题的编号。默认值为 true。 |
| [FontFamily](../../aspose.omr.generation.config.elements/choiceboxconfig/fontfamily) { get; set; } | 文本的字体族 |
| [FontSize](../../aspose.omr.generation.config.elements/choiceboxconfig/fontsize) { get; set; } | 文本字体的大小 |
| [FontStyle](../../aspose.omr.generation.config.elements/choiceboxconfig/fontstyle) { get; set; } | 文本的样式 |
| [Multiselect](../../aspose.omr.generation.config.elements/choiceboxconfig/multiselect) { get; set; } | 允许每个问题选择多个答案，覆盖 [`Multiselect`](../../aspose.omr.generation/globalpagesettings/multiselect) 中的默认设置。 |
| override [Name](../../aspose.omr.generation.config.elements/choiceboxconfig/name) { get; set; } | Choice 框的名称。用于显示的值为 [`QuestionText`](./questiontext)。 |
| [QuestionText](../../aspose.omr.generation.config.elements/choiceboxconfig/questiontext) { get; set; } | 获取或设置 ChoiceBox 元素的问题文本 |
| [TextAlignment](../../aspose.omr.generation.config.elements/choiceboxconfig/textalignment) { get; set; } | 文本对齐，指示文本应在页面上的绘制位置 |
| override [Type](../../aspose.omr.generation.config.elements/choiceboxconfig/type) { get; set; } | OMR 元素的类型。JSON 序列化所需的字段。 |

### 另请参阅

* class [ParentConfig](../../aspose.omr.generation.config/parentconfig)
* namespace [Aspose.OMR.Generation.Config.Elements](../../aspose.omr.generation.config.elements)
* assembly [Aspose.OMR](../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OMR.dll 生成 -->
