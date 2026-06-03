---
title: "PageConfig"
second_title: "Aspose.OMR 适用于 .NET API 参考"
description: "表示 Page 元素。每页一个。必须放置在 TemplateConfig../aspose.omr.generation.config/templateconfig 内部。"
type: docs
weight: 430
url: /zh/net/aspose.omr.generation.config.elements.parents/pageconfig/
---
## PageConfig class

表示 Page 元素。每页一个。必须放置在 [`TemplateConfig`](../../aspose.omr.generation.config/templateconfig) 内部。

```csharp
public class PageConfig : ParentConfig
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PageConfig](pageconfig)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| override [Children](../../aspose.omr.generation.config.elements.parents/pageconfig/children) { get; set; } | 子 OMR 元素。大多数情况下位于父元素内部或下方。 |
| [LeftMargin](../../aspose.omr.generation.config.elements.parents/pageconfig/leftmargin) { get; set; } | 画布左侧的像素间距。覆盖由 [`PageMarginLeft`](../../aspose.omr.generation/globalpagesettings/pagemarginleft) 提供的值。 |
| override [Name](../../aspose.omr.generation.config.elements.parents/pageconfig/name) { get; set; } | 页面的名称 |
| [Orientation](../../aspose.omr.generation.config.elements.parents/pageconfig/orientation) { get; set; } | 此页面的方向。覆盖由 [`Orientation`](../../aspose.omr.generation/globalpagesettings/orientation) 提供的值。 |
| [PaperSize](../../aspose.omr.generation.config.elements.parents/pageconfig/papersize) { get; set; } | 此页面的纸张尺寸。覆盖由 [`PaperSize`](../../aspose.omr.generation/globalpagesettings/papersize) 提供的值。 |
| [RightMargin](../../aspose.omr.generation.config.elements.parents/pageconfig/rightmargin) { get; set; } | 画布右侧的像素间距。覆盖由 [`PageMarginRight`](../../aspose.omr.generation/globalpagesettings/pagemarginright) 提供的值。 |
| [RotationPointPosition](../../aspose.omr.generation.config.elements.parents/pageconfig/rotationpointposition) { get; set; } | 此页面所需的旋转点位置。如果未设置，将使用 TopRight1。覆盖由 !:GlobalPageSettings.RotationPointPosition 提供的值。 |
| override [Type](../../aspose.omr.generation.config.elements.parents/pageconfig/type) { get; set; } | OMR 元素的类型。JSON 序列化所需的字段。 |

### 另请参阅

* class [ParentConfig](../../aspose.omr.generation.config/parentconfig)
* namespace [Aspose.OMR.Generation.Config.Elements.Parents](../../aspose.omr.generation.config.elements.parents)
* assembly [Aspose.OMR](../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OMR.dll 生成 -->
