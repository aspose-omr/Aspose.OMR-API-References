---
title: Class License
second_title: Aspose.OMR لمرجع .NET API
description: Aspose.OMR.License فصل. يوفر طرقًا لترخيص المكون.
type: docs
weight: 770
url: /ar/net/aspose.omr/license/
---
## License class

يوفر طرقًا لترخيص المكون.

```csharp
public class License
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [License](license/)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Embedded](../../aspose.omr/license/embedded/) { get; set; } | تمت إضافة رقم الترخيص كمورد مضمن . |

## طُرق

| اسم | وصف |
| --- | --- |
| [SetLicense](../../aspose.omr/license/setlicense/#setlicense)(Stream) | تراخيص المكون . |
| [SetLicense](../../aspose.omr/license/setlicense/#setlicense_1)(string) | تراخيص المكون . |

### أمثلة

في هذا المثال ، سيتم إجراء محاولة للعثور على ملف ترخيص يسمى MyLicense.lic في المجلد الذي يحتوي على المكون ، في المجلد الذي يحتوي على التجميع الاستدعاء ، في مجلد تجميع الإدخال ثم في المجلد المضمن موارد التجمع المتصل.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### أنظر أيضا

* مساحة الاسم [Aspose.OMR](../../aspose.omr/)
* المجسم [Aspose.OMR](../../)


