---
title: "OmrEngine"
second_title: "Aspose.OMR لـ .NET مرجع API"
description: "محرك OMR. يتعامل مع إنشاء فئات القالب ومعالجة الصور ومكونات واجهة المستخدم الرسومية."
type: docs
weight: 20
url: /ar/net/aspose.omr.api/omrengine/
---
## OmrEngine class

محرك OMR. يتعامل مع إنشاء فئات القالب ومعالجة الصور ومكونات واجهة المستخدم الرسومية.

```csharp
public class OmrEngine
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [OmrEngine](omrengine)(PoolFactory) | إنشاء مثيل من OmrEngine لتخزين داخلي من أجل كفاءة الذاكرة. أعد استخدام نفس المصنع لعدة مثيلات من OmrEngine لتحسين الأداء. |

## طرق

| الاسم | الوصف |
| --- | --- |
| [AddPlugin](../../aspose.omr.api/omrengine/addplugin)(IPlugin) | تسجيل مكوّن إضافي جديد |
| [Generate](../../aspose.omr.api/omrengine/generate#generate_3)(string[], GlobalPageSettings, ImageCollection) | ينشئ [`GenerationResult`](../../aspose.omr.generation/generationresult) الذي يحتوي على القالب (.omr) وصورة القالب بناءً على محتوى العلامات. |
| [Generate](../../aspose.omr.api/omrengine/generate#generate)(TemplateConfig, GlobalPageSettings, ImageCollection) | ينشئ [`GenerationResult`](../../aspose.omr.generation/generationresult) الذي يحتوي على القالب (.omr) وصورة القالب بناءً على محتوى العلامات. |
| [Generate](../../aspose.omr.api/omrengine/generate#generate_1)(Stream, GlobalPageSettings, ImageCollection, Encoding) | ينشئ [`GenerationResult`](../../aspose.omr.generation/generationresult) الذي يحتوي على القالب (.omr) وصورة القالب بناءً على تدفق العلامات. |
| [Generate](../../aspose.omr.api/omrengine/generate#generate_2)(string, GlobalPageSettings, string[], Encoding) | ينشئ [`GenerationResult`](../../aspose.omr.generation/generationresult) الذي يحتوي على القالب (.omr) وصورة القالب بناءً على محتوى العلامات المخزن في المسار المحدد. |
| [GetCorrectionControl](../../aspose.omr.api/omrengine/getcorrectioncontrol)(TemplateProcessor) | ينشئ مثيل [`CorrectionControl`](../../aspose.omr.correctionui/correctioncontrol) الذي يتيح العمل مع OMR API باستخدام واجهة المستخدم الرسومية. يأخذ [`TemplateProcessor`](../templateprocessor) كمعامل ويعمل فقط مع الصور التي تم إنشاؤها باستخدام القالب المحدد. |
| [GetTemplateProcessor](../../aspose.omr.api/omrengine/gettemplateprocessor#gettemplateprocessor_1)(string, FormValidationLogic) | ينشئ مثيل [`TemplateProcessor`](../templateprocessor) الذي يتيح العمل مع القالب المحدد. |
| [GetTemplateProcessor](../../aspose.omr.api/omrengine/gettemplateprocessor#gettemplateprocessor)(MemoryStream, Encoding, FormValidationLogic) | ينشئ مثيل [`TemplateProcessor`](../templateprocessor) الذي يتيح العمل مع القالب المحدد. |

### أمثلة

```csharp
// احصل على معالج القالب
OmrEngine engine = new OmrEngine();
TemplateProcessor templateProcessor = engine.GetTemplateProcessor(templatePath);
```

```csharp
// احصل على عنصر تحكم GUI للتصحيح
OmrEngine engine = new OmrEngine();
TemplateProcessor templateProcessor = engine.GetTemplateProcessor(templatePath);
CorrectionControl control = engine.GetCorrectionControl(templateProcessor);
```

```csharp
// إنشاء القالب
OmrEngine engine = new OmrEngine();
GenerationResult result = engine.GenerateTemplate(markupPath);
if(result.ErrorCode == 0)
{
    result.Save(folderPath, templateName);
}
```

### انظر أيضًا

* namespace [Aspose.OMR.Api](../../aspose.omr.api)
* assembly [Aspose.OMR](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ Aspose.OMR.dll -->
