---
title: "توليد"
second_title: "Aspose.OMR لـ .NET مرجع API"
description: "ينشئ GenerationResultaspose.omr.generation/generationresult الذي يحتوي على قالب .omr وصورة القالب بناءً على تدفق العلامات."
type: docs
weight: 30
url: /ar/net/aspose.omr.api/omrengine/generate/
---
## Generate(Stream, GlobalPageSettings, ImageCollection, Encoding) {#generate_1}

ينشئ [`GenerationResult`](../../../aspose.omr.generation/generationresult) الذي يحتوي على قالب (.omr) وصورة القالب بناءً على تدفق العلامات.

```csharp
public GenerationResult Generate(Stream markupStream, GlobalPageSettings settings = null, 
    ImageCollection collection = null, Encoding encoding = null)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| markupStream | Stream | تدفق قابل للقراءة يحتوي على سطور العلامات لتكوين القالب (txt أو json) |
| الإعدادات | GlobalPageSettings | الإعدادات العامة المستخدمة في إنشاء القالب لجميع الصفحات |
| مجموعة | ImageCollection | مجموعة من الصور التي يمكن استخدامها لإنشاء قالب. تسمح باستخدام الصور من MemoryStream بدلاً من نظام الملفات. |
| ترميز | الترميز | ترميز سطور العلامات، يُستخدم UTF-8 افتراضيًا |

### قيمة الإرجاع

نتيجة الإنشاء

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | markupPath |
| [RuntimeExceptionOMR](../../../aspose.omr.exceptions/runtimeexceptionomr) | إنشاء القالب |

### انظر أيضًا

* class [GenerationResult](../../../aspose.omr.generation/generationresult)
* class [GlobalPageSettings](../../../aspose.omr.generation/globalpagesettings)
* class [ImageCollection](../../imagecollection)
* class [OmrEngine](../../omrengine)
* namespace [Aspose.OMR.Api](../../omrengine)
* assembly [Aspose.OMR](../../../)

---

## Generate(string, GlobalPageSettings, string[], Encoding) {#generate_2}

ينشئ [`GenerationResult`](../../../aspose.omr.generation/generationresult) الذي يحتوي على قالب (.omr) وصورة القالب بناءً على محتوى العلامات المخزن في المسار المحدد

```csharp
public GenerationResult Generate(string markupPath, GlobalPageSettings settings = null, 
    string[] imagesPaths = null, Encoding encoding = null)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| markupPath | سلسلة | مسار إلى ملف يحتوي على سطور العلامات لتكوين القالب (txt أو json) |
| الإعدادات | GlobalPageSettings | الإعدادات العامة المستخدمة في إنشاء القالب لجميع الصفحات |
| imagesPaths | String[] | المسار إلى الصور التي ستُستخدم لتوليد قالب |
| ترميز | الترميز | ترميز سطور العلامات، يُستخدم UTF-8 افتراضيًا |

### قيمة الإرجاع

نتيجة الإنشاء

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | markupPath |
| FileNotFoundException | markupPath |
| [RuntimeExceptionOMR](../../../aspose.omr.exceptions/runtimeexceptionomr) | إنشاء القالب |

### انظر أيضًا

* class [GenerationResult](../../../aspose.omr.generation/generationresult)
* class [GlobalPageSettings](../../../aspose.omr.generation/globalpagesettings)
* class [OmrEngine](../../omrengine)
* namespace [Aspose.OMR.Api](../../omrengine)
* assembly [Aspose.OMR](../../../)

---

## Generate(string[], GlobalPageSettings, ImageCollection) {#generate_3}

ينشئ [`GenerationResult`](../../../aspose.omr.generation/generationresult) الذي يحتوي على القالب (.omr) وصورة القالب بناءً على محتوى العلامات

```csharp
public GenerationResult Generate(string[] markupContent, GlobalPageSettings settings = null, 
    ImageCollection collection = null)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| markupContent | String[] | مجموعة سطور العلامات لتكوين القالب (txt أو json) |
| الإعدادات | GlobalPageSettings | الإعدادات العامة المستخدمة في إنشاء القالب لجميع الصفحات |
| مجموعة | ImageCollection | مجموعة من الصور التي يمكن استخدامها لإنشاء قالب. تسمح باستخدام الصور من MemoryStream بدلاً من نظام الملفات. |

### قيمة الإرجاع

نتيجة الإنشاء

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException |  |
| [RuntimeExceptionOMR](../../../aspose.omr.exceptions/runtimeexceptionomr) | إنشاء القالب |

### انظر أيضًا

* class [GenerationResult](../../../aspose.omr.generation/generationresult)
* class [GlobalPageSettings](../../../aspose.omr.generation/globalpagesettings)
* class [ImageCollection](../../imagecollection)
* class [OmrEngine](../../omrengine)
* namespace [Aspose.OMR.Api](../../omrengine)
* assembly [Aspose.OMR](../../../)

---

## Generate(TemplateConfig, GlobalPageSettings, ImageCollection) {#generate}

ينشئ [`GenerationResult`](../../../aspose.omr.generation/generationresult) الذي يحتوي على القالب (.omr) وصورة القالب بناءً على محتوى العلامات

```csharp
public GenerationResult Generate(TemplateConfig config, GlobalPageSettings settings = null, 
    ImageCollection collection = null)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| config | TemplateConfig | تكوين القالب، |
| الإعدادات | GlobalPageSettings | الإعدادات العامة المستخدمة في إنشاء القالب لجميع الصفحات |
| مجموعة | ImageCollection | مجموعة من الصور التي يمكن استخدامها لإنشاء قالب. تسمح باستخدام الصور من MemoryStream بدلاً من نظام الملفات. |

### قيمة الإرجاع

نتيجة الإنشاء

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [RuntimeExceptionOMR](../../../aspose.omr.exceptions/runtimeexceptionomr) | إنشاء القالب |

### انظر أيضًا

* class [GenerationResult](../../../aspose.omr.generation/generationresult)
* class [TemplateConfig](../../../aspose.omr.generation.config/templateconfig)
* class [GlobalPageSettings](../../../aspose.omr.generation/globalpagesettings)
* class [ImageCollection](../../imagecollection)
* class [OmrEngine](../../omrengine)
* namespace [Aspose.OMR.Api](../../omrengine)
* assembly [Aspose.OMR](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ Aspose.OMR.dll -->
