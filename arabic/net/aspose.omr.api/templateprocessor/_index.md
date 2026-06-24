---
title: "TemplateProcessor"
second_title: "Aspose.OMR لـ .NET مرجع API"
description: "فئة لمعالجة القوالب والصور. كل مثال من هذه الفئة يعمل مع قالب OMR واحد. يمكنه التعرف على صور القالب المحدد في المُنشئ."
type: docs
weight: 50
url: /ar/net/aspose.omr.api/templateprocessor/
---
## TemplateProcessor class

فئة لمعالجة القوالب والصور. كل مثال من هذه الفئة يعمل مع قالب OMR واحد. يمكنه التعرف على صور القالب المحدد في المُنشئ.

```csharp
public class TemplateProcessor
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Recalculate](../../aspose.omr.api/templateprocessor/recalculate)(RecognitionResult, int) | يقوم بتحديث نتيجة التعرف باستخدام معلمات مُضبوطة بدقة. |
| [Recognize](../../aspose.omr.api/templateprocessor/recognize#recognize)(Stream, int) | التعرف على ملف من التدفق |
| [Recognize](../../aspose.omr.api/templateprocessor/recognize#recognize_1)(Stream[], int) | التعرف على مجموعة من الملفات من التدفقات |
| [Recognize](../../aspose.omr.api/templateprocessor/recognize#recognize_2)(string, int) | يتعرف على ملف |
| [Recognize](../../aspose.omr.api/templateprocessor/recognize#recognize_3)(string[], int) | تعرّف على ملفات متعددة كملف متعدد الصفحات واحد |
| [RecognizeFolder](../../aspose.omr.api/templateprocessor/recognizefolder)(string, int) | يتعرف على الصور من المجلد |

## الحقول

| الاسم | الوصف |
| --- | --- |
| [ApplyLightShadeProcessing](../../aspose.omr.api/templateprocessor/applylightshadeprocessing) | إعداد التعرف الاختياري. عند ضبطه على true ستتضمن جميع طرق Recognize معالجة مسبقة إضافية. هذه المعالجة المسبقة مفيدة لتسليط الضوء على العلامات بظل خفيف جداً. مثال: علامات قلم رصاص خفيفة. |

### أمثلة

```csharp
OmrEngine engine = new OmrEngine();
TemplateProcessor templateProcessor = engine.GetTemplateProcessor(templatePath);
RecognitionResult result = templateProcessor.Recognize(imagePath);
string csvResult = result.GetCsv();
```

### انظر أيضًا

* namespace [Aspose.OMR.Api](../../aspose.omr.api)
* assembly [Aspose.OMR](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ Aspose.OMR.dll -->
