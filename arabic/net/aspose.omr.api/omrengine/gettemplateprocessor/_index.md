---
title: "GetTemplateProcessor"
second_title: "Aspose.OMR لـ .NET مرجع API"
description: "ينشئ كائن TemplateProcessoraspose.omr.api/templateprocessor الذي يسمح بالعمل مع القالب المحدد."
type: docs
weight: 50
url: /ar/net/aspose.omr.api/omrengine/gettemplateprocessor/
---
## GetTemplateProcessor(MemoryStream, Encoding, FormValidationLogic) {#gettemplateprocessor}

ينشئ كائن [`TemplateProcessor`](../../templateprocessor) الذي يسمح بالعمل مع القالب المحدد.

```csharp
public TemplateProcessor GetTemplateProcessor(MemoryStream templateContent, Encoding textEncoding, 
    FormValidationLogic logic = FormValidationLogic.Ignore)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| templateContent | MemoryStream | دفق الذاكرة مع محتوى نص القالب |
| textEncoding | الترميز | ترميز محتوى القالب |
| logic | FormValidationLogic | Enum الذي يتحكم في السلوك في حال كسر أحد قواعد التحقق من القالب |

### قيمة الإرجاع

كائن [`TemplateProcessor`](../../templateprocessor)

### انظر أيضًا

* class [TemplateProcessor](../../templateprocessor)
* enum [FormValidationLogic](../../../aspose.omr.recognition.enums/formvalidationlogic)
* class [OmrEngine](../../omrengine)
* namespace [Aspose.OMR.Api](../../omrengine)
* assembly [Aspose.OMR](../../../)

---

## GetTemplateProcessor(string, FormValidationLogic) {#gettemplateprocessor_1}

ينشئ كائن [`TemplateProcessor`](../../templateprocessor) الذي يسمح بالعمل مع القالب المحدد.

```csharp
public TemplateProcessor GetTemplateProcessor(string templatePath, 
    FormValidationLogic logic = FormValidationLogic.Ignore)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| templatePath | سلسلة | المسار إلى ملف قالب OMR |
| logic | FormValidationLogic | Enum الذي يتحكم في السلوك في حال كسر أحد قواعد التحقق من القالب |

### قيمة الإرجاع

كائن [`TemplateProcessor`](../../templateprocessor)

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
