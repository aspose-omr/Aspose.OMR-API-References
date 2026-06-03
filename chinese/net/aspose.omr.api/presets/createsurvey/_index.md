---
title: "CreateSurvey"
second_title: "Aspose.OMR 适用于 .NET API 参考"
description: "将问题组合成一个简易调查。"
type: docs
weight: 20
url: /zh/net/aspose.omr.api/presets/createsurvey/
---
## Presets.CreateSurvey method

将问题组合成一个简易调查。

```csharp
public static void CreateSurvey(string fullPath, string title = null, 
    GlobalPageSettings settings = null, params ChoiceBoxConfig[] questions)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| fullPath | String | 生成的调查图像的相对或绝对路径。 |
| title | String | 调查的可选标题。 |
| settings | 全局页面设置 | 可选的页面布局设置。 |
| questions | ChoiceBoxConfig[] | 使用[`CreateSurveyQuestion`](../createsurveyquestion)配置的问题列表。 |

### 示例

```csharp
var question1 = Presets.CreateSurveyQuestion("Are satisfied with your experience?", "Yes", "No", "Not sure");
var question2 = Presets.CreateSurveyQuestion("Rate our service:", "Great", "Good", "Mediocre", "Bad");
var settings = new GlobalPageSettings() { PaperSize = PaperSize.Letter }
Presets.CreateSurvey("C:\survey.png", "Customer satisfaction survey", settings, question1, question2);
```

### 另请参阅

* class [GlobalPageSettings](../../../aspose.omr.generation/globalpagesettings)
* class [ChoiceBoxConfig](../../../aspose.omr.generation.config.elements/choiceboxconfig)
* class [Presets](../../presets)
* namespace [Aspose.OMR.Api](../../presets)
* assembly [Aspose.OMR](../../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OMR.dll 生成 -->
