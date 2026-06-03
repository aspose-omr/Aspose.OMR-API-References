---
title: "CreateSurvey"
second_title: "Aspose.OMR لـ .NET مرجع API"
description: "دمج الأسئلة في استبيان بسيط."
type: docs
weight: 20
url: /ar/net/aspose.omr.api/presets/createsurvey/
---
## Presets.CreateSurvey method

دمج الأسئلة في استبيان بسيط.

```csharp
public static void CreateSurvey(string fullPath, string title = null, 
    GlobalPageSettings settings = null, params ChoiceBoxConfig[] questions)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fullPath | سلسلة | مسار نسبي أو مطلق إلى صورة الاستبيان المُولدة. |
| title | سلسلة | عنوان اختياري للاستبيان. |
| الإعدادات | GlobalPageSettings | إعدادات تخطيط الصفحة الاختيارية. |
| questions | ChoiceBoxConfig[] | قائمة من الأسئلة، مُكوَّنة باستخدام [`CreateSurveyQuestion`](../createsurveyquestion). |

### أمثلة

```csharp
var question1 = Presets.CreateSurveyQuestion("Are satisfied with your experience?", "Yes", "No", "Not sure");
var question2 = Presets.CreateSurveyQuestion("Rate our service:", "Great", "Good", "Mediocre", "Bad");
var settings = new GlobalPageSettings() { PaperSize = PaperSize.Letter }
Presets.CreateSurvey("C:\survey.png", "Customer satisfaction survey", settings, question1, question2);
```

### انظر أيضًا

* class [GlobalPageSettings](../../../aspose.omr.generation/globalpagesettings)
* class [ChoiceBoxConfig](../../../aspose.omr.generation.config.elements/choiceboxconfig)
* class [Presets](../../presets)
* namespace [Aspose.OMR.Api](../../presets)
* assembly [Aspose.OMR](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ Aspose.OMR.dll -->
