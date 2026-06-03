---
title: "RecognizeBubbleSheet"
second_title: "Aspose.OMR لـ .NET مرجع API"
description: "تعرّف على ورقة الفقاعات التي تم إنشاؤها باستخدام طريقة CreateBubbleSheetaspose.omr.api/presets/createbubblesheet. للحفاظ على التناسق في التعرف على النماذج، قدم نفس المعلمات كما هي في طريقة CreateBubbleSheetaspose.omr.api/presets/createbubblesheet."
type: docs
weight: 40
url: /ar/net/aspose.omr.api/presets/recognizebubblesheet/
---
## Presets.RecognizeBubbleSheet method

تعرّف على ورقة الفقاعات التي تم إنشاؤها باستخدام طريقة [`CreateBubbleSheet`](../createbubblesheet). للحفاظ على التناسق في التعرف على النماذج، قدم نفس المعلمات كما هي في طريقة [`CreateBubbleSheet`](../createbubblesheet).

```csharp
public static string RecognizeBubbleSheet(string fullPath, int elementsCount, int columns, 
    int answersCount, string title = null, BubbleType bubbleType = BubbleType.Round, 
    BubbleSize bubbleSize = BubbleSize.Normal, GlobalPageSettings settings = null)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fullPath | سلسلة | مسار نسبي أو مطلق إلى صورة النموذج المكتمل. |
| elementsCount | Int32 | إجمالي عدد الأسئلة في التقييم التكميلي. |
| columns | Int32 | عدد الأعمدة التي تُرتب فيها الأسئلة. |
| answersCount | Int32 | إجمالي عدد الفقاعات (الإجابات) لكل سؤال. |
| title | سلسلة | عنوان ورقة الفقاعات. |
| bubbleType | BubbleType | نمط الفقاعات. |
| bubbleSize | BubbleSize | حجم الفقاعات. |
| الإعدادات | GlobalPageSettings | إعدادات تخطيط الصفحة. |

### قيمة الإرجاع

محتوى بتنسيق CSV (معرّف السؤال والإجابة)

### أمثلة

```csharp
var settings = new GlobalPageSettings() { PaperSize = PaperSize.Letter }
Presets.RecognizeBubbleSheet("response.png", 100, 3, 5, "100 Questions", BubbleType.Square, BubbleSize.ExtraLarge, settings);
```

### انظر أيضًا

* enum [BubbleType](../../../aspose.omr.generation.config.enums/bubbletype)
* enum [BubbleSize](../../../aspose.omr.generation/bubblesize)
* class [GlobalPageSettings](../../../aspose.omr.generation/globalpagesettings)
* class [Presets](../../presets)
* namespace [Aspose.OMR.Api](../../presets)
* assembly [Aspose.OMR](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ Aspose.OMR.dll -->
