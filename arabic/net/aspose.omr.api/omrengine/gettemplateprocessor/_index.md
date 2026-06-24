---
title: "GetTemplateProcessor"
second_title: "Aspose.OMR لـ .NET مرجع API"
description: "ينشئ مثيل TemplateProcessoraspose.omr.api/templateprocessor الذي يسمح بالعمل مع القالب المحدد."
type: docs
weight: 50
url: /ar/net/aspose.omr.api/omrengine/gettemplateprocessor/
---
## GetTemplateProcessor(MemoryStream, Encoding, FormValidationLogic) {#gettemplateprocessor}

ينشئ مثيل [`TemplateProcessor`](../../templateprocessor) الذي يسمح بالعمل مع القالب المحدد.

```csharp
public TemplateProcessor GetTemplateProcessor(MemoryStream templateContent, Encoding textEncoding, 
    FormValidationLogic logic = FormValidationLogic.Ignore)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| templateContent | MemoryStream | دفق الذاكرة مع محتوى نص القالب |
| textEncoding | الترميز | ترميز محتوى القالب |
| logic | FormValidationLogic | تعداد يتحكم في السلوك في حالة كسر أحد قواعد التحقق من القالب |

### قيمة الإرجاع

مثيل [`TemplateProcessor`](../../templateprocessor)

### انظر أيضًا

* class [TemplateProcessor](../../templateprocessor)
* enum [FormValidationLogic](../../../aspose.omr.recognition.enums/formvalidationlogic)
* class [OmrEngine](../../omrengine)
* namespace [Aspose.OMR.Api](../../omrengine)
* assembly [Aspose.OMR](../../../)

---

## GetTemplateProcessor(string, FormValidationLogic) {#gettemplateprocessor_1}

ينشئ مثيل [`TemplateProcessor`](../../templateprocessor) الذي يسمح بالعمل مع القالب المحدد.

```csharp
public TemplateProcessor GetTemplateProcessor(string templatePath, 
    FormValidationLogic logic = FormValidationLogic.Ignore)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| templatePath | String | المسار إلى ملف قالب OMR |
| logic | FormValidationLogic | تعداد يتحكم في السلوك في حالة كسر أحد قواعد التحقق من القالب |

### قيمة الإرجاع

مثيل [`TemplateProcessor`](../../templateprocessor)

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| FileNotFoundException | في حالة عدم إشارة templatePath إلى ملف موجود |

### انظر أيضًا

* class [TemplateProcessor](../../templateprocessor)
* enum [FormValidationLogic](../../../aspose.omr.recognition.enums/formvalidationlogic)
* class [OmrEngine](../../omrengine)
* namespace [Aspose.OMR.Api](../../omrengine)
* assembly [Aspose.OMR](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ Aspose.OMR.dll -->
