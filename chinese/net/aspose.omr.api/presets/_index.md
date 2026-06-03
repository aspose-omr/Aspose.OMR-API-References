---
title: "预设"
second_title: "Aspose.OMR 适用于 .NET API 参考"
description: "提供用于快速生成和识别具有预定义设计的 OMR 表单的简写命令。此 API 使得在无需学习 Aspose.OMR 标记语言的情况下创建表单，并在无需模式文件的情况下进行表单识别。若需对表单设计和识别进行高级控制，请使用 OmrEngine./omrengine。"
type: docs
weight: 40
url: /zh/net/aspose.omr.api/presets/
---
## Presets class

提供用于快速生成和识别具有预定义设计的 OMR 表单的简写命令。此 API 使得在无需学习 Aspose.OMR 标记语言的情况下创建表单，并在无需模式文件的情况下进行表单识别。若需对表单设计和识别进行高级控制，请使用 [`OmrEngine`](../omrengine)。

```csharp
public static class Presets
```

## 方法

| 名称 | 描述 |
| --- | --- |
| static [CreateBubbleSheet](../../aspose.omr.api/presets/createbubblesheet)(string, int, int, int, string, BubbleType, BubbleSize, GlobalPageSettings) | 生成带可选标题的简易气泡答题卡。 |
| static [CreateSurvey](../../aspose.omr.api/presets/createsurvey)(string, string, GlobalPageSettings, params ChoiceBoxConfig[]) | 将问题组合成一个简易调查。 |
| static [CreateSurveyQuestion](../../aspose.omr.api/presets/createsurveyquestion)(string, params string[]) | 创建一个具有可变答案数量的问题。用于 !:CreateSurvey(string, GlobalPageSettings, ChoiceBoxConfig[]) |
| static [RecognizeBubbleSheet](../../aspose.omr.api/presets/recognizebubblesheet)(string, int, int, int, string, BubbleType, BubbleSize, GlobalPageSettings) | 识别使用[`CreateBubbleSheet`](./createbubblesheet)方法生成的气泡表。为保持表单识别的一致性，请提供与[`CreateBubbleSheet`](./createbubblesheet)方法相同的参数。 |
| static [RecognizeSurvey](../../aspose.omr.api/presets/recognizesurvey)(string, string, GlobalPageSettings, params ChoiceBoxConfig[]) | 识别使用[`CreateSurvey`](./createsurvey)方法生成的调查表。为保持表单识别的一致性，请提供与[`CreateSurvey`](./createsurvey)方法相同的参数。 |

### 另请参阅

* namespace [Aspose.OMR.Api](../../aspose.omr.api)
* assembly [Aspose.OMR](../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OMR.dll 生成 -->
