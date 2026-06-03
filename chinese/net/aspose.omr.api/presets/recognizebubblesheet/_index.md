---
title: "RecognizeBubbleSheet"
second_title: "Aspose.OMR 适用于 .NET API 参考"
description: "识别使用 CreateBubbleSheetaspose.omr.api/presets/createbubblesheet 方法生成的气泡表。为了在表单识别中保持一致性，请提供与 CreateBubbleSheetaspose.omr.api/presets/createbubblesheet 方法相同的参数。"
type: docs
weight: 40
url: /zh/net/aspose.omr.api/presets/recognizebubblesheet/
---
## Presets.RecognizeBubbleSheet method

识别使用[`CreateBubbleSheet`](../createbubblesheet)方法生成的气泡表。为了在表单识别中保持一致性，请提供与[`CreateBubbleSheet`](../createbubblesheet)方法相同的参数。

```csharp
public static string RecognizeBubbleSheet(string fullPath, int elementsCount, int columns, 
    int answersCount, string title = null, BubbleType bubbleType = BubbleType.Round, 
    BubbleSize bubbleSize = BubbleSize.Normal, GlobalPageSettings settings = null)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| fullPath | String | 已完成表单图像的相对或绝对路径。 |
| elementsCount | Int32 | 补充评估中的问题总数。 |
| columns | Int32 | 问题排列的列数。 |
| answersCount | Int32 | 每个问题的气泡（答案）总数。 |
| title | String | 气泡表的标题。 |
| bubbleType | BubbleType | 气泡样式。 |
| bubbleSize | BubbleSize | 气泡的大小。 |
| settings | 全局页面设置 | 页面布局设置。 |

### 返回值

CSV 格式的内容（问题 ID 和答案）

### 示例

```csharp
var settings = new GlobalPageSettings() { PaperSize = PaperSize.Letter }
Presets.RecognizeBubbleSheet("response.png", 100, 3, 5, "100 Questions", BubbleType.Square, BubbleSize.ExtraLarge, settings);
```

### 另请参阅

* enum [BubbleType](../../../aspose.omr.generation.config.enums/bubbletype)
* enum [BubbleSize](../../../aspose.omr.generation/bubblesize)
* class [GlobalPageSettings](../../../aspose.omr.generation/globalpagesettings)
* class [Presets](../../presets)
* namespace [Aspose.OMR.Api](../../presets)
* assembly [Aspose.OMR](../../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OMR.dll 生成 -->
