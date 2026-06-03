---
title: "CreateSurveyQuestion"
second_title: "Aspose.OMR لـ .NET مرجع API"
description: "إنشاء سؤال بعدد متغيّر من الإجابات. يُستخدم في CreateSurveystring GlobalPageSettings ChoiceBoxConfig."
type: docs
weight: 30
url: /ar/net/aspose.omr.api/presets/createsurveyquestion/
---
## Presets.CreateSurveyQuestion method

إنشاء سؤال بعدد متغيّر من الإجابات. يُستخدم في !:CreateSurvey(string, GlobalPageSettings, ChoiceBoxConfig[])

```csharp
public static ChoiceBoxConfig CreateSurveyQuestion(string question, params string[] answers)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| question | سلسلة | نص السؤال. |
| answers | String[] | إجابات السؤال. |

### قيمة الإرجاع

كائن يمثل سؤالًا وجميع الإجابات.

### أمثلة

```csharp
var question = Presets.CreateSurveyQuestion("Are satisfied with your experience?", "Yes", "No", "Not sure");
```

### انظر أيضًا

* class [ChoiceBoxConfig](../../../aspose.omr.generation.config.elements/choiceboxconfig)
* class [Presets](../../presets)
* namespace [Aspose.OMR.Api](../../presets)
* assembly [Aspose.OMR](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ Aspose.OMR.dll -->
