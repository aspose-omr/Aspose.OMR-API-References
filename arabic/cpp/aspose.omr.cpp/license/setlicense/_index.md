---
title: "SetLicense"
second_title: "مرجع API لـ Aspose.OMR لـ .NET"
description: "يرخص المكوّن."
type: docs
weight: 30
url: /ar/net/aspose.omr/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

يرخص المكوّن.

```csharp
public void SetLicense(string licenseName)
```

### ملاحظات

يحاول العثور على الرخصة في المواقع التالية:

1. مسار صريح.

2. المجلد الذي يحتوي على تجميع مكوّن Aspose.

3. المجلد الذي يحتوي على تجميع الاستدعاء الخاص بالعميل.

4. المجلد الذي يحتوي على التجميع (البدء).

5. مورد مضمن في تجميع الاستدعاء للعميل.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. مسار صريح.

2. مورد مضمن في تجميع الاستدعاء للعميل.

### الأمثلة

في هذا المثال، سيتم محاولة العثور على ملف رخصة يُدعى MyLicense.lic في المجلد الذي يحتوي على المكوّن، وفي المجلد الذي يحتوي على التجميع المستدعي، في مجلد التجميع الرئيسي، ثم في الموارد المضمّنة للتجميع المستدعي.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
```

يمكن أن يكون اسم ملف كامل أو قصير أو اسم مورد مضمن. استخدم سلسلة فارغة للتبديل إلى وضع التقييم.

### انظر أيضًا

* class [License](../../license)
* namespace [Aspose.OMR](../../license)
* assembly [Aspose.OMR](../../../)

---

## SetLicense(Stream) {#setlicense}

يرخص المكوّن.

```csharp
public void SetLicense(Stream stream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | دفق | دفق يحتوي على الترخيص. |

### ملاحظات

استخدم هذه الطريقة لتحميل الترخيص من دفق.

### الأمثلة

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

### انظر أيضًا

* class [License](../../license)
* namespace [Aspose.OMR](../../license)
* assembly [Aspose.OMR](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ Aspose.OMR.dll -->
