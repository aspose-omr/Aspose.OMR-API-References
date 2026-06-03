---
title: "ترخيص"
second_title: "Aspose.OMR لـ .NET مرجع API"
description: "يوفر طرقًا لترخيص المكوّن."
type: docs
weight: 1010
url: /ar/net/aspose.omr/license/
---
## License class

يوفر طرقًا لترخيص المكوّن.

```csharp
public class License
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [License](license)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Embedded](../../aspose.omr/license/embedded) { get; set; } | تم إضافة رقم الترخيص كموارد مدمجة. |

## طرق

| الاسم | الوصف |
| --- | --- |
| [SetLicense](../../aspose.omr/license/setlicense#setlicense)(Stream) | يرخص المكوّن. |
| [SetLicense](../../aspose.omr/license/setlicense#setlicense_1)(string) | يرخص المكوّن. |

### أمثلة

في هذا المثال، سيُجرى محاولة للعثور على ملف ترخيص يُدعى MyLicense.lic في المجلد الذي يحتوي على المكوّن، وفي المجلد الذي يحتوي على التجميع المستدعي، وفي مجلد التجميع الرئيسي، ثم في الموارد المضمَّنة للتجميع المستدعي.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### انظر أيضًا

* namespace [Aspose.OMR](../../aspose.omr)
* assembly [Aspose.OMR](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ Aspose.OMR.dll -->
