---
title: "قائم على القياس"
second_title: "مرجع API لـ Aspose.OMR للـ .NET"
description: "يوفر طرقًا لتعيين المفتاح القائم على القياس."
type: docs
weight: 10
url: /ar/net/aspose.omr/metered/
---
## Metered class

يوفر طرقًا لتعيين المفتاح القائم على القياس.

```csharp
public class Metered
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Metered](metered)() | يقوم بتهيئة نسخة جديدة من هذه الفئة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [SetMeteredKey](../../aspose.omr/metered/setmeteredkey)(string, string) | يضبط المفتاح القائم على القياس العام والخاص |
| static [GetConsumptionCredit](../../aspose.omr/metered/getconsumptioncredit)() | يحصل على رصيد الاستهلاك |
| static [GetConsumptionQuantity](../../aspose.omr/metered/getconsumptionquantity)() | يحصل على حجم ملف الاستهلاك |

### الأمثلة

في هذا المثال، ستتم محاولة تعيين المفتاح القائم على القياس العام والخاص

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

ملف jar الخاص بالمكوّن:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### انظر أيضًا

* namespace [Aspose.OMR](../../aspose.omr)
* assembly [Aspose.OMR](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ Aspose.OMR.dll -->
