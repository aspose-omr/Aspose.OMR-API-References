---
title: "تعرّف"
second_title: "Aspose.OMR لـ .NET مرجع API"
description: "التعرف على مجلد أو ملف"
type: docs
weight: 20
url: /ar/net/aspose.omr.batchprocessings/batchtemplateprocessor/recognize/
---
## Recognize(string, int) {#recognize_2}

التعرف على مجلد أو ملف

```csharp
public BatchRecognitionResult Recognize(string path, int recognitionThreshold = -100)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| المسار | String | المسار إلى مجلد أو ملف |
| recognitionThreshold | Int32 | (اختياري) عتبة التعرف في النطاق (0..100). فقط العناصر المملوءة فوق العتبة ستحسب كمملوءة. |

### قيمة الإرجاع

نتيجة التعرف الدفعي لملف أو جميع الملفات داخل المجلد

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| FileNotFoundException | إذا كان المسار غير صالح للمجلد أو الملف |

### انظر أيضًا

* class [BatchRecognitionResult](../../batchrecognitionresult)
* class [BatchTemplateProcessor](../../batchtemplateprocessor)
* namespace [Aspose.OMR.BatchProcessings](../../batchtemplateprocessor)
* assembly [Aspose.OMR](../../../)

---

## Recognize(Stream, int) {#recognize_1}

التعرف على قالب واحد من التدفق

```csharp
public BatchRecognitionResult Recognize(Stream stream, int recognitionThreshold = -100)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| دفق | Stream | دفق قابل للقراءة مع قالب واحد |
| recognitionThreshold | Int32 | (اختياري) عتبة التعرف في النطاق (0..100). فقط العناصر المملوءة فوق العتبة ستحسب كمملوءة. |

### قيمة الإرجاع

نتيجة التعرف الدفعي على نموذج قالب واحد

### انظر أيضًا

* class [BatchRecognitionResult](../../batchrecognitionresult)
* class [BatchTemplateProcessor](../../batchtemplateprocessor)
* namespace [Aspose.OMR.BatchProcessings](../../batchtemplateprocessor)
* assembly [Aspose.OMR](../../../)

---

## Recognize(IEnumerable&lt;string&gt;, int) {#recognize}

التعرف على عدة ملفات

```csharp
public BatchRecognitionResult Recognize(IEnumerable<string> files, int recognitionThreshold = -100)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| ملفات | IEnumerable`1 | مجموعة من المسارات الكاملة للملفات |
| recognitionThreshold | Int32 | (اختياري) عتبة التعرف في النطاق (0..100). فقط العناصر المملوءة فوق العتبة ستحسب كمملوءة. |

### قيمة الإرجاع

نتيجة التعرف الدفعي على نماذج متعددة

### انظر أيضًا

* class [BatchRecognitionResult](../../batchrecognitionresult)
* class [BatchTemplateProcessor](../../batchtemplateprocessor)
* namespace [Aspose.OMR.BatchProcessings](../../batchtemplateprocessor)
* assembly [Aspose.OMR](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ Aspose.OMR.dll -->
