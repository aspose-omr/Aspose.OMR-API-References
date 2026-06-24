---
title: "GenerationResult"
second_title: "Aspose.OMR لـ .NET مرجع API"
description: "نتيجة توليد القالب. تحتوي على صورة القالب وملف json الخاص بالقالب الذي يصف موقع العناصر على الصورة."
type: docs
weight: 810
url: /ar/net/aspose.omr.generation/generationresult/
---
## GenerationResult class

نتيجة إنشاء القالب. يحتوي على صورة القالب والقالب (json الذي يصف موقع العناصر على الصورة).

```csharp
public class GenerationResult
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ErrorCode](../../aspose.omr.generation/generationresult/errorcode) { get; set; } | يحصل أو يعيّن رمز الخطأ. يساوي 0 إذا لم تحدث أخطاء. |
| [ErrorMessage](../../aspose.omr.generation/generationresult/errormessage) { get; set; } | يحصل أو يعيّن الرسالة التي تصف الخطأ. تكون فارغة إذا لم تحدث أخطاء. |
| [Template](../../aspose.omr.generation/generationresult/template) { get; set; } | يحصل أو يعيّن سلسلة Template JSON |
| [TemplateImage](../../aspose.omr.generation/generationresult/templateimage) { get; set; } | يحصل أو يعيّن Template Image المولدة |
| [Warnings](../../aspose.omr.generation/generationresult/warnings) { get; set; } | يحصل أو يعيّن قائمة رسائل التحذير التي تصف الأخطاء غير الحرجة التي ظهرت أثناء التوليد. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Save](../../aspose.omr.generation/generationresult/save)(string, string) | احفظ صور القالب والقالب في المجلد المحدد بصيغة .png |
| [SaveAsInteractivePdf](../../aspose.omr.generation/generationresult/saveasinteractivepdf)(string, string) | احفظ نموذجًا إلى ملف PDF تفاعلي، مما يتيح للمستخدمين ملء الحقول مباشرة على حواسيبهم أو هواتفهم الذكية وإرسالها إلكترونيًا. |
| [SaveAsPdf](../../aspose.omr.generation/generationresult/saveaspdf)(string, string) | احفظ صور القالب في المجلد المحدد بصيغة .pdf. القوالب متعددة الصفحات تُحفظ كملف .pdf واحد يحتوي على عدة صفحات. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| [MultipageTemplateImages](../../aspose.omr.generation/generationresult/multipagetemplateimages) | يحصل أو يعيّن مجموعة الصور المولدة لقالب متعدد الصفحات. |

### انظر أيضًا

* namespace [Aspose.OMR.Generation](../../aspose.omr.generation)
* assembly [Aspose.OMR](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ Aspose.OMR.dll -->
