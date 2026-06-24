---
title: "الإعدادات المسبقة"
second_title: "Aspose.OMR لـ .NET مرجع API"
description: "يوفر أوامر مختصرة للتوليد السريع والتعرف على نماذج OMR بتصميم مسبق. يتيح هذا API إنشاء النماذج دون الحاجة لتعلم لغات العلامات Aspose.OMR والتعرف على النماذج دون ملف نمط. للتحكم المتقدم في تصميم النماذج والتعرف عليها استخدم OmrEngine./omrengine"
type: docs
weight: 40
url: /ar/net/aspose.omr.api/presets/
---
## Presets class

يوفر أوامر مختصرة للتوليد السريع والتعرف على نماذج OMR بتصميم مسبق. يتيح هذا API إنشاء النماذج دون الحاجة لتعلم لغات العلامات Aspose.OMR والتعرف على النماذج دون ملف نمط. للتحكم المتقدم في تصميم النماذج والتعرف عليها، استخدم [`OmrEngine`](../omrengine)

```csharp
public static class Presets
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [CreateBubbleSheet](../../aspose.omr.api/presets/createbubblesheet)(string, int, int, int, string, BubbleType, BubbleSize, GlobalPageSettings) | ينشئ ورقة فقاعة بسيطة مع عنوان اختياري. |
| static [CreateSurvey](../../aspose.omr.api/presets/createsurvey)(string, string, GlobalPageSettings, params ChoiceBoxConfig[]) | دمج الأسئلة في استبيان بسيط. |
| static [CreateSurveyQuestion](../../aspose.omr.api/presets/createsurveyquestion)(string, params string[]) | إنشاء سؤال بعدد متغيّر من الإجابات. يُستخدم في !:CreateSurvey(string, GlobalPageSettings, ChoiceBoxConfig[]) |
| static [RecognizeBubbleSheet](../../aspose.omr.api/presets/recognizebubblesheet)(string, int, int, int, string, BubbleType, BubbleSize, GlobalPageSettings) | تعرّف على ورقة الفقاعات التي تم إنشاؤها باستخدام طريقة [`CreateBubbleSheet`](./createbubblesheet). للحفاظ على التناسق في التعرف على النماذج، قدّم نفس المعلمات كما في طريقة [`CreateBubbleSheet`](./createbubblesheet). |
| static [RecognizeSurvey](../../aspose.omr.api/presets/recognizesurvey)(string, string, GlobalPageSettings, params ChoiceBoxConfig[]) | تعرّف على استبيان تم إنشاؤه باستخدام طريقة [`CreateSurvey`](./createsurvey). للحفاظ على التناسق في التعرف على النماذج، قدّم نفس المعلمات كما في طريقة [`CreateSurvey`](./createsurvey). |

### انظر أيضًا

* namespace [Aspose.OMR.Api](../../aspose.omr.api)
* assembly [Aspose.OMR](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ Aspose.OMR.dll -->
