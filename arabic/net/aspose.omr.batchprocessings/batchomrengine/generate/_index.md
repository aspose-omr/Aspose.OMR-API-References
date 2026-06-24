---
title: "توليد"
second_title: "Aspose.OMR لـ .NET مرجع API"
description: "إنشاء عدة قوالب باستخدام قالب التخطيط ومجموعة من إدخالات البيانات"
type: docs
weight: 30
url: /ar/net/aspose.omr.batchprocessings/batchomrengine/generate/
---
## Generate(DataSet, Stream, GlobalPageSettings, ImageCollection) {#generate}

إنشاء عدة قوالب باستخدام قالب التخطيط ومجموعة من إدخالات البيانات

```csharp
public BatchGenerationResult Generate(DataSet dataSet, Stream layoutStream, 
    GlobalPageSettings settings = null, ImageCollection collection = null)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| dataSet | DataSet | مجموعة من مجموعات البيانات المستخدمة في توليد نموذج القالب |
| layoutStream | Stream | دفق مع تخطيط القالب |
| الإعدادات | GlobalPageSettings | إعدادات الصفحة المستخدمة في كل توليد نموذج القالب |
| المجموعة | ImageCollection | مجموعة الصور المستخدمة في كل توليد نموذج القالب |

### قيمة الإرجاع

نتيجة توليد دفعة من القوالب

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | عند معالجة DataRecord بمعرف فارغ |

### انظر أيضًا

* class [BatchGenerationResult](../../batchgenerationresult)
* class [DataSet](../../dataset)
* class [GlobalPageSettings](../../../aspose.omr.generation/globalpagesettings)
* class [ImageCollection](../../../aspose.omr.api/imagecollection)
* class [BatchOmrEngine](../../batchomrengine)
* namespace [Aspose.OMR.BatchProcessings](../../batchomrengine)
* assembly [Aspose.OMR](../../../)

---

## Generate(DataSet, string, GlobalPageSettings, ImageCollection) {#generate_1}

إنشاء عدة قوالب باستخدام قالب التخطيط ومجموعة من إدخالات البيانات

```csharp
public BatchGenerationResult Generate(DataSet dataSet, string layoutPath, 
    GlobalPageSettings settings = null, ImageCollection collection = null)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| dataSet | DataSet | مجموعة من مجموعات البيانات المستخدمة في توليد نموذج القالب |
| layoutPath | String | مسار إلى ملف يحتوي على تخطيط القالب |
| الإعدادات | GlobalPageSettings | إعدادات الصفحة المستخدمة في كل توليد نموذج القالب |
| المجموعة | ImageCollection | مجموعة الصور المستخدمة في كل توليد نموذج القالب |

### قيمة الإرجاع

نتيجة توليد دفعة من القوالب

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| FileNotFoundException | عند عدم صحة layoutPath |
| ArgumentException | عند معالجة DataRecord بمعرف فارغ |

### انظر أيضًا

* class [BatchGenerationResult](../../batchgenerationresult)
* class [DataSet](../../dataset)
* class [GlobalPageSettings](../../../aspose.omr.generation/globalpagesettings)
* class [ImageCollection](../../../aspose.omr.api/imagecollection)
* class [BatchOmrEngine](../../batchomrengine)
* namespace [Aspose.OMR.BatchProcessings](../../batchomrengine)
* assembly [Aspose.OMR](../../../)

---

## Generate(DataSet, string[], GlobalPageSettings, ImageCollection) {#generate_2}

إنشاء عدة قوالب باستخدام قالب التخطيط ومجموعة من إدخالات البيانات

```csharp
public BatchGenerationResult Generate(DataSet dataSet, string[] layoutLines, 
    GlobalPageSettings settings = null, ImageCollection collection = null)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| dataSet | DataSet | مجموعة من مجموعات البيانات المستخدمة في توليد نموذج القالب |
| layoutLines | String[] | مصفوفة مرتبة من الأسطر تمثل تخطيط القالب |
| الإعدادات | GlobalPageSettings | إعدادات الصفحة المستخدمة في كل توليد نموذج القالب |
| المجموعة | ImageCollection | مجموعة الصور المستخدمة في كل توليد نموذج القالب |

### قيمة الإرجاع

نتيجة توليد دفعة من القوالب

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | عند معالجة DataRecord بمعرف فارغ |

### انظر أيضًا

* class [BatchGenerationResult](../../batchgenerationresult)
* class [DataSet](../../dataset)
* class [GlobalPageSettings](../../../aspose.omr.generation/globalpagesettings)
* class [ImageCollection](../../../aspose.omr.api/imagecollection)
* class [BatchOmrEngine](../../batchomrengine)
* namespace [Aspose.OMR.BatchProcessings](../../batchomrengine)
* assembly [Aspose.OMR](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ Aspose.OMR.dll -->
