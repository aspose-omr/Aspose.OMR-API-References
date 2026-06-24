---
title: "رخصة"
second_title: "مرجع API لـ Aspose.OMR للـ .NET"
description: "يوفر طرقًا لترخيص المكوّن."
type: docs
weight: 20
url: /ar/net/aspose.omr/license/
---
## License class

يوفر طرقًا لترخيص المكوّن.

```csharp
public class License
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [License](license)() | يقوم بتهيئة نسخة جديدة من هذه الفئة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Embedded](../../aspose.omr/license/embedded) { get; set; } | تم إضافة رقم الرخصة كموارد مضمّنة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [SetLicense](../../aspose.omr/license/setlicense#setlicense)(Stream) | يرخص المكوّن. |
| [SetLicense](../../aspose.omr/license/setlicense#setlicense_1)(string) | يرخص المكوّن. |

### الأمثلة

في هذا المثال، سيتم محاولة العثور على ملف رخصة باسم MyLicense.lic في المجلد الذي يحتوي على المكوّن، وفي المجلد الذي يحتوي على التجميع المستدعي، وفي مجلد التجميع الرئيسي، ثم في الموارد المضمّنة للتجميع المستدعي.

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
