---
title: "CreateSurveyQuestion"
second_title: "Aspose.OMR 适用于 .NET API 参考"
description: "创建一个具有可变数量答案的问题。用于 CreateSurveystring GlobalPageSettings ChoiceBoxConfig。"
type: docs
weight: 30
url: /zh/net/aspose.omr.api/presets/createsurveyquestion/
---
## Presets.CreateSurveyQuestion method

创建一个具有可变答案数量的问题。用于 !:CreateSurvey(string, GlobalPageSettings, ChoiceBoxConfig[])

```csharp
public static ChoiceBoxConfig CreateSurveyQuestion(string question, params string[] answers)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| question | String | 问题文本。 |
| answers | String[] | 问题的答案。 |

### 返回值

表示一个问题及其所有答案的对象

### 示例

```csharp
var question = Presets.CreateSurveyQuestion("Are satisfied with your experience?", "Yes", "No", "Not sure");
```

### 另请参阅

* class [ChoiceBoxConfig](../../../aspose.omr.generation.config.elements/choiceboxconfig)
* class [Presets](../../presets)
* namespace [Aspose.OMR.Api](../../presets)
* assembly [Aspose.OMR](../../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OMR.dll 生成 -->
