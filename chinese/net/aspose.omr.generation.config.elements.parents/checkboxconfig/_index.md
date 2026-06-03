---
title: "CheckBoxConfig"
second_title: "Aspose.OMR 适用于 .NET API 参考"
description: "表示 CheckBox 元素。"
type: docs
weight: 410
url: /zh/net/aspose.omr.generation.config.elements.parents/checkboxconfig/
---
## CheckBoxConfig class

表示 CheckBox 元素。

```csharp
public class CheckBoxConfig : ParentConfig
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [CheckBoxConfig](checkboxconfig)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BubbleSize](../../aspose.omr.generation.config.elements.parents/checkboxconfig/bubblesize) { get; set; } | 每个选项（子项）的矩形尺寸 |
| [BubbleType](../../aspose.omr.generation.config.elements.parents/checkboxconfig/bubbletype) { get; set; } | 气泡的类型 |
| override [Children](../../aspose.omr.generation.config.elements.parents/checkboxconfig/children) { get; set; } | 子 OMR 元素。大多数情况下位于父元素内部或下方。 |
| [FontFamily](../../aspose.omr.generation.config.elements.parents/checkboxconfig/fontfamily) { get; set; } | 文本的字体族 |
| [FontSize](../../aspose.omr.generation.config.elements.parents/checkboxconfig/fontsize) { get; set; } | 文本字体的大小 |
| [FontStyle](../../aspose.omr.generation.config.elements.parents/checkboxconfig/fontstyle) { get; set; } | 文本的样式 |
| [HideName](../../aspose.omr.generation.config.elements.parents/checkboxconfig/hidename) { get; set; } | 控制模板中复选框名称的显示 |
| [Multiselect](../../aspose.omr.generation.config.elements.parents/checkboxconfig/multiselect) { get; set; } | 允许每个问题选择多个答案，覆盖 [`Multiselect`](../../aspose.omr.generation/globalpagesettings/multiselect) 中的默认设置。 |
| override [Name](../../aspose.omr.generation.config.elements.parents/checkboxconfig/name) { get; set; } | 复选框的名称。默认显示在第一个复选框之前。可通过 [`HideName`](./hidename) 隐藏 |
| [Orientation](../../aspose.omr.generation.config.elements.parents/checkboxconfig/orientation) { get; set; } | 控制子元素的位置。目前仅支持水平布局 |
| [Threshold](../../aspose.omr.generation.config.elements.parents/checkboxconfig/threshold) { get; set; } | 自定义识别标记。默认设置为 3%。如果复选框区域的 3% 被填充，则视为已标记。可自定义为其他阈值。不会影响全局阈值 |
| override [Type](../../aspose.omr.generation.config.elements.parents/checkboxconfig/type) { get; set; } | OMR 元素的类型。JSON 序列化所需的字段。 |

### 另请参阅

* class [ParentConfig](../../aspose.omr.generation.config/parentconfig)
* namespace [Aspose.OMR.Generation.Config.Elements.Parents](../../aspose.omr.generation.config.elements.parents)
* assembly [Aspose.OMR](../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OMR.dll 生成 -->
