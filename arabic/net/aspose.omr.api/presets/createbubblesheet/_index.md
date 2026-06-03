---
title: "CreateBubbleSheet"
second_title: "Aspose.OMR لـ .NET مرجع API"
description: "ينشئ ورقة فقاعة بسيطة مع عنوان اختياري."
type: docs
weight: 10
url: /ar/net/aspose.omr.api/presets/createbubblesheet/
---
## Presets.CreateBubbleSheet method

ينشئ ورقة فقاعة بسيطة مع عنوان اختياري.

```csharp
public static void CreateBubbleSheet(string fullPath, int elementsCount, int columns, 
    int answersCount, string title = null, BubbleType bubbleType = BubbleType.Round, 
    BubbleSize bubbleSize = BubbleSize.Normal, GlobalPageSettings settings = null)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fullPath | سلسلة | المسار النسبي أو المطلق إلى صورة النموذج المُنشأة. |
| elementsCount | Int32 | إجمالي عدد الأسئلة في التقييم التكميلي. |
| columns | Int32 | عدد الأعمدة لترتيب الأسئلة فيها. استخدم عدة أعمدة لجعل الورقة أكثر تكثيفًا. |
| answersCount | Int32 | إجمالي عدد الفقاعات (الإجابات) لكل سؤال. |
| title | سلسلة | العنوان الاختياري لورقة الفقاعات. |
| bubbleType | BubbleType | نمط الفقاعات (اختياري). |
| bubbleSize | BubbleSize | حجم الفقاعات (اختياري). |
| الإعدادات | GlobalPageSettings | إعدادات تخطيط الصفحة الاختيارية. |

### أمثلة

```csharp
var settings = new GlobalPageSettings() { PaperSize = PaperSize.Letter }
Presets.CreateBubbleSheet("bubble_sheet.png", 100, 3, 5, "100 Questions", BubbleType.Square, BubbleSize.ExtraLarge, settings);
```

### انظر أيضًا

* enum [BubbleType](../../../aspose.omr.generation.config.enums/bubbletype)
* enum [BubbleSize](../../../aspose.omr.generation/bubblesize)
* class [GlobalPageSettings](../../../aspose.omr.generation/globalpagesettings)
* class [Presets](../../presets)
* namespace [Aspose.OMR.Api](../../presets)
* assembly [Aspose.OMR](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ Aspose.OMR.dll -->
