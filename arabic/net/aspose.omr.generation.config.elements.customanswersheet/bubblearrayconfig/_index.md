---
title: "BubbleArrayConfig"
second_title: "Aspose.OMR لـ .NET مرجع API"
description: "اعرض الإجابات المحتملة كخيارات كل منها داخل دائرة. لا يمكن استخدامها إلا داخل CustomRowConfig./customrowconfig"
type: docs
weight: 310
url: /ar/net/aspose.omr.generation.config.elements.customanswersheet/bubblearrayconfig/
---
## BubbleArrayConfig class

اعرض الإجابات المحتملة كخيارات كل منها داخل دائرة (فقاعة). لا يمكن استخدامها إلا داخل [`CustomRowConfig`](../customrowconfig)

```csharp
public class BubbleArrayConfig : BaseConfig
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [BubbleArrayConfig](bubblearrayconfig)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AnswersValues](../../aspose.omr.generation.config.elements.customanswersheet/bubblearrayconfig/answersvalues) { get; set; } | كل قيمة تمثل رمزًا يُعرض داخل الفقاعة وعدد الفقاعات. في حالة وجود اختلاف بين القيمة المعروضة والقيمة المُعترف بها راجع [`RecognitionValues`](./recognitionvalues). مثال: new string[] {"A", "B", "C", "D"}. مثال: new string[] {"1", "2", "3", "4"} |
| [BubbleSize](../../aspose.omr.generation.config.elements.customanswersheet/bubblearrayconfig/bubblesize) { get; set; } | حجم الفقاعة |
| [BubbleType](../../aspose.omr.generation.config.elements.customanswersheet/bubblearrayconfig/bubbletype) { get; set; } | نوع الفقاعة |
| [FontFamily](../../aspose.omr.generation.config.elements.customanswersheet/bubblearrayconfig/fontfamily) { get; set; } | عائلة الخط للنص |
| [FontSize](../../aspose.omr.generation.config.elements.customanswersheet/bubblearrayconfig/fontsize) { get; set; } | حجم خط النص |
| [FontStyle](../../aspose.omr.generation.config.elements.customanswersheet/bubblearrayconfig/fontstyle) { get; set; } | نمط النص |
| [Height](../../aspose.omr.generation.config.elements.customanswersheet/bubblearrayconfig/height) { get; set; } | يتجاوز ارتفاع صف مصفوفة الفقاعات بالبكسل. سيتم إزالة المحتوى الجزئي المرئي أو المتجاوز. للتفاصيل راجع - [`Clip`](../../aspose.omr.generation.overflowactions/clip). القيمة الافتراضية هي -1. بشكل افتراضي سيتم تعديل ارتفاع مصفوفة الفقاعات تلقائيًا. |
| [HorizontalPadding](../../aspose.omr.generation.config.elements.customanswersheet/bubblearrayconfig/horizontalpadding) { get; set; } | عدد البكسلات الإضافية على الجانبين الأيسر والأيمن داخل صف الفقاعات. القيمة الافتراضية هي 0 |
| override [Name](../../aspose.omr.generation.config.elements.customanswersheet/bubblearrayconfig/name) { get; set; } | اسم مصفوفة الفقاعات. لا يشارك في العرض أو إنشاء العنصر |
| [RecognitionValues](../../aspose.omr.generation.config.elements.customanswersheet/bubblearrayconfig/recognitionvalues) { get; set; } | كل إدخال يتجاوز القيمة في نتيجة التعرف لتطابق [`AnswersValues`](./answersvalues) دون التأثير على القيمة المعروضة. إذا لم يتم تعيين قيمة - سيتم ملء نتيجة التعرف بالقيم المعروضة من [`AnswersValues`](./answersvalues). مثال: new List(4) {"A", "B", "C", "D"}. مثال: new List(4) {"Dog", "Cat", "Turtle", "Dragon"}. |
| [Threshold](../../aspose.omr.generation.config.elements.customanswersheet/bubblearrayconfig/threshold) { get; set; } | تجاوز العتبة العامة المقدمة أثناء التعرف. نسبة البكسلات من 0 إلى 100 التي بعده تُعتبر الفقاعات مُحددة. القيمة الافتراضية هي -1. بشكل افتراضي سيتم استخدام القيمة العامة للعتبة. |
| override [Type](../../aspose.omr.generation.config.elements.customanswersheet/bubblearrayconfig/type) { get; set; } | نوع عنصر OMR. حقل مطلوب لتسلسل JSON. |
| [VerticalPadding](../../aspose.omr.generation.config.elements.customanswersheet/bubblearrayconfig/verticalpadding) { get; set; } | عدد البكسلات الإضافية على الجانبين العلوي والسفلي داخل صف الفقاعات. القيمة الافتراضية هي 0. |

### انظر أيضًا

* class [BaseConfig](../../aspose.omr.generation.config/baseconfig)
* namespace [Aspose.OMR.Generation.Config.Elements.CustomAnswerSheet](../../aspose.omr.generation.config.elements.customanswersheet)
* assembly [Aspose.OMR](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ Aspose.OMR.dll -->
