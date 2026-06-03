---
title: "ScoreDisplay"
second_title: "Aspose.OMR 适用于 .NET API 参考"
description: "控制分数值的显示。"
type: docs
weight: 720
url: /zh/net/aspose.omr.generation.config.enums/scoredisplay/
---
## ScoreDisplay enumeration

控制分数值的显示。

```csharp
public enum ScoreDisplay
```

### Values

| 名称 | Value | 描述 |
| --- | --- | --- |
| DontDisplay | `0` | 分数值将对用户隐藏。分数值仍参与识别和总分计数。计数将被忽略。 |
| DisplayAsExtraColumn | `1` | 分数值将显示为额外列并对用户可见。分数值参与识别和总分计数。计数将标记分数列在其他列中的位置。请仅使用一个此类标题。 |
| DisplayInsideCell | `2` | 分数值将显示在每个单元格内。分数值将放置在每个气泡中。在当前版本中——每个气泡只能放置一位数字，否则将抛出异常。计数将被忽略。 |

### 另请参阅

* namespace [Aspose.OMR.Generation.Config.Enums](../../aspose.omr.generation.config.enums)
* assembly [Aspose.OMR](../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OMR.dll 生成 -->
