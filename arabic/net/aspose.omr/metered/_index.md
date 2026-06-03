---
title: "Metered"
second_title: "Aspose.OMR لـ .NET مرجع API"
description: "يوفر طرقًا لتعيين المفتاح المقيس."
type: docs
weight: 1020
url: /ar/net/aspose.omr/metered/
---
## Metered class

يوفر طرقًا لتعيين المفتاح المقيس.

```csharp
public class Metered
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Metered](metered)() | المنشئ الافتراضي. |

## طرق

| الاسم | الوصف |
| --- | --- |
| [GetProductName](../../aspose.omr/metered/getproductname)() | احصل على اسم المنتج |
| [SetMeteredKey](../../aspose.omr/metered/setmeteredkey)(string, string) | يضبط المفتاح العام والخاص للترخيص القائم على الاستهلاك. إذا قمت بشراء ترخيص قائم على الاستهلاك، عند بدء التطبيق، يجب استدعاء هذه الواجهة البرمجية، عادةً هذا يكفي. ومع ذلك، إذا فشل دائمًا تحميل بيانات الاستهلاك وتجاوز 24 ساعة، سيتم تعيين الترخيص إلى حالة التقييم، لتجنب هذه الحالة، يجب عليك فحص حالة الترخيص بانتظام، إذا كانت في حالة التقييم، استدعِ هذه الواجهة البرمجية مرة أخرى. |
| static [GetConsumptionCredit](../../aspose.omr/metered/getconsumptioncredit)() | يحصل على رصيد الاستهلاك |
| static [GetConsumptionQuantity](../../aspose.omr/metered/getconsumptionquantity)() | يحصل على حجم ملف الاستهلاك |
| static [IsMeteredLicensed](../../aspose.omr/metered/ismeteredlicensed)() | تحقق مما إذا كان الترخيص القائم على الاستهلاك مفعلًا |

### أمثلة

في هذا المثال، سيتم محاولة ضبط المفتاح العام والخاص للترخيص القائم على الاستهلاك

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### انظر أيضًا

* namespace [Aspose.OMR](../../aspose.omr)
* assembly [Aspose.OMR](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ Aspose.OMR.dll -->
