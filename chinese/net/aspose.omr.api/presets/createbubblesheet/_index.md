---
title: "CreateBubbleSheet"
second_title: "Aspose.OMR 适用于 .NET API 参考"
description: "生成带可选标题的简易气泡答题卡。"
type: docs
weight: 10
url: /zh/net/aspose.omr.api/presets/createbubblesheet/
---
## Presets.CreateBubbleSheet method

生成带可选标题的简易气泡答题卡。

```csharp
public static void CreateBubbleSheet(string fullPath, int elementsCount, int columns, 
    int answersCount, string title = null, BubbleType bubbleType = BubbleType.Round, 
    BubbleSize bubbleSize = BubbleSize.Normal, GlobalPageSettings settings = null)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| fullPath | String | 相对或绝对路径，指向生成的表单图像。 |
| elementsCount | Int32 | 补充评估中的问题总数。 |
| columns | Int32 | 用于排列问题的列数。使用多列可以使表格更紧凑。 |
| answersCount | Int32 | 每个问题的气泡（答案）总数。 |
| title | String | 气泡表的可选标题。 |
| bubbleType | BubbleType | 气泡样式（可选）。 |
| bubbleSize | BubbleSize | 气泡大小（可选）。 |
| settings | 全局页面设置 | 可选的页面布局设置。 |

### 示例

```csharp
var settings = new GlobalPageSettings() { PaperSize = PaperSize.Letter }
Presets.CreateBubbleSheet("bubble_sheet.png", 100, 3, 5, "100 Questions", BubbleType.Square, BubbleSize.ExtraLarge, settings);
```

### 另请参阅

* enum [BubbleType](../../../aspose.omr.generation.config.enums/bubbletype)
* enum [BubbleSize](../../../aspose.omr.generation/bubblesize)
* class [GlobalPageSettings](../../../aspose.omr.generation/globalpagesettings)
* class [Presets](../../presets)
* namespace [Aspose.OMR.Api](../../presets)
* assembly [Aspose.OMR](../../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OMR.dll 生成 -->
