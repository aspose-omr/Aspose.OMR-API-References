---
title: "FormValidationLogic"
second_title: "Aspose.OMR لـ .NET مرجع API"
description: "الأنماط التي تتحكم في سلوك الحالات غير القياسية أثناء عملية التعرف."
type: docs
weight: 1050
url: /ar/net/aspose.omr.recognition.enums/formvalidationlogic/
---
## FormValidationLogic enumeration

أنماط تتحكم في سلوك الحالات غير القياسية (خطأ) أثناء عملية التعرف.

```csharp
public enum FormValidationLogic
```

### Values

| الاسم | Value | الوصف |
| --- | --- | --- |
| undefined | `0` | لم يتم تحديد أي منطق - سيتم استخدام القيمة الافتراضية (Ignore=1) |
| Ignore | `1` | محرك التعرف سيتجاهل جميع الأخطاء مع منطق التحقق الذي تم إعداده بواسطة قالب markdown. تم وضع علامات على إجابات متعددة لكل سؤال، على الرغم من أن اختيار متعدد تم تعيينه إلى false. في هذه الحالة - سيتم إرجاع جميع القيم المعلَّمة كما هي. |
| Exception | `2` | محرك التعرف سيطرح استثناءً مشتقًا من [`OMRException`](../../aspose.omr.exceptions/omrexception). نوع الاستثناء يعتمد على القاعدة المكسورة. تم وضع علامات على إجابات متعددة لكل سؤال، على الرغم من أن اختيار متعدد تم تعيينه إلى false. سيتم طرح الاستثناء [`MultiselectException`](../../aspose.omr.exceptions/multiselectexception). |

### انظر أيضًا

* namespace [Aspose.OMR.Recognition.Enums](../../aspose.omr.recognition.enums)
* assembly [Aspose.OMR](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ Aspose.OMR.dll -->
