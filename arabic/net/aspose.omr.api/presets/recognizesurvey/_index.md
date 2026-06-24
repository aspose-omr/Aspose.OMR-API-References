---
title: "RecognizeSurvey"
second_title: "Aspose.OMR لـ .NET مرجع API"
description: "التعرف على استبيان تم إنشاؤه باستخدام طريقة CreateSurveyaspose.omr.api/presets/createsurvey. للحفاظ على التناسق في التعرف على النماذج، قدم نفس المعلمات كما هي في طريقة CreateSurveyaspose.omr.api/presets/createsurvey."
type: docs
weight: 50
url: /ar/net/aspose.omr.api/presets/recognizesurvey/
---
## Presets.RecognizeSurvey method

التعرف على استبيان تم إنشاؤه باستخدام طريقة [`CreateSurvey`](../createsurvey). للحفاظ على التناسق في التعرف على النماذج، قدم نفس المعلمات كما هي في طريقة [`CreateSurvey`](../createsurvey).

```csharp
public static string RecognizeSurvey(string fullPath, string title, 
    GlobalPageSettings settings = null, params ChoiceBoxConfig[] questions)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fullPath | String | المسار النسبي أو المطلق إلى صورة الاستبيان المُولدة. |
| title | String | عنوان الاستبيان. |
| الإعدادات | GlobalPageSettings | إعدادات تخطيط الصفحة. |
| الأسئلة | ChoiceBoxConfig[] | قائمة من الأسئلة، مُكوَّنة باستخدام !:CreateSurveyLine(string, string[]). |

### قيمة الإرجاع

محتوى بتنسيق CSV (معرّف السؤال والإجابة)

### أمثلة

```csharp
var question1 = Presets.CreateSurveyQuestion("Are satisfied with your experience?", "Yes", "No", "Not sure");
var question2 = Presets.CreateSurveyQuestion("Rate our service:", "Great", "Good", "Mediocre", "Bad");
var settings = new GlobalPageSettings() { PaperSize = PaperSize.Letter }
Presets.RecognizeSurvey("C:\response.png", "Customer satisfaction survey", settings, question1, question2);
```

### انظر أيضًا

* class [GlobalPageSettings](../../../aspose.omr.generation/globalpagesettings)
* class [ChoiceBoxConfig](../../../aspose.omr.generation.config.elements/choiceboxconfig)
* class [Presets](../../presets)
* namespace [Aspose.OMR.Api](../../presets)
* assembly [Aspose.OMR](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ Aspose.OMR.dll -->
