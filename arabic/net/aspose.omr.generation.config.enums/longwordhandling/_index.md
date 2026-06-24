---
title: "LongWordHandling"
second_title: "Aspose.OMR لـ .NET مرجع API"
description: "يصف سلوك إنشاء القالب عند مواجهة كلمة أبعادها أكبر من الحاوية الأصلية. في هذه الحالة لا يمكن عرض الكلمة بشكل صحيح داخل الحاوية الأصلية ولا يمكن لفها."
type: docs
weight: 690
url: /ar/net/aspose.omr.generation.config.enums/longwordhandling/
---
## LongWordHandling enumeration

يصف سلوك إنشاء القالب عند مواجهة كلمة أبعادها أكبر من الحاوية الأصلية. في هذه الحالة لا يمكن عرض الكلمة بشكل صحيح داخل الحاوية الأصلية ولا يمكن لفها.

```csharp
public enum LongWordHandling
```

### Values

| الاسم | Value | الوصف |
| --- | --- | --- |
| undefined | `0` | لم يتم تعيين الإعدادات. سيتم استخدام القيمة الافتراضية. |
| DrawOver | `1` | القيمة الافتراضية. سيتم عرض الكلمة كما هي، متجاوزة حدود العنصر الأب. |
| ThrowException | `2` | بعد قياس الكلمة على أنها تتجاوز العنصر الأب - سيتم إلقاء استثناء. |
| Hyphenation | `3` | قسّم الكلمة الطويلة إلى أحرف وعرض باقي الأحرف في سطر جديد |

### انظر أيضًا

* namespace [Aspose.OMR.Generation.Config.Enums](../../aspose.omr.generation.config.enums)
* assembly [Aspose.OMR](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ Aspose.OMR.dll -->
