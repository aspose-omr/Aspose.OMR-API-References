---
title: "RecognizeSurvey"
second_title: "Aspose.OMR 适用于 .NET API 参考"
description: "识别使用 CreateSurveyaspose.omr.api/presets/createsurvey 方法生成的调查。为保持表单识别的一致性，请提供与 CreateSurveyaspose.omr.api/presets/createsurvey 方法相同的参数。"
type: docs
weight: 50
url: /zh/net/aspose.omr.api/presets/recognizesurvey/
---
## Presets.RecognizeSurvey method

识别使用 [`CreateSurvey`](../createsurvey) 方法生成的调查。为保持表单识别的一致性，请提供与 [`CreateSurvey`](../createsurvey) 方法相同的参数。

```csharp
public static string RecognizeSurvey(string fullPath, string title, 
    GlobalPageSettings settings = null, params ChoiceBoxConfig[] questions)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| fullPath | String | 生成的调查图像的相对或绝对路径。 |
| title | String | 调查标题。 |
| settings | 全局页面设置 | 页面布局设置。 |
| questions | ChoiceBoxConfig[] | 使用 !:CreateSurveyLine(string, string[]) 配置的一系列问题列表。 |

### 返回值

CSV 格式的内容（问题 ID 和答案）

### 示例

```csharp
var question1 = Presets.CreateSurveyQuestion("Are satisfied with your experience?", "Yes", "No", "Not sure");
var question2 = Presets.CreateSurveyQuestion("Rate our service:", "Great", "Good", "Mediocre", "Bad");
var settings = new GlobalPageSettings() { PaperSize = PaperSize.Letter }
Presets.RecognizeSurvey("C:\response.png", "Customer satisfaction survey", settings, question1, question2);
```

### 另请参阅

* class [GlobalPageSettings](../../../aspose.omr.generation/globalpagesettings)
* class [ChoiceBoxConfig](../../../aspose.omr.generation.config.elements/choiceboxconfig)
* class [Presets](../../presets)
* namespace [Aspose.OMR.Api](../../presets)
* assembly [Aspose.OMR](../../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OMR.dll 生成 -->
