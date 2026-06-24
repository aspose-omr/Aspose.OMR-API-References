---
title: "AnswerSheetConfig"
second_title: "Aspose.OMR لـ .NET مرجع API"
description: "يمثل عنصر ورقة الإجابة. يسمح بإضافة صناديق الاختيار مجمّعة في أعمدة وصفوف. استخدم ورقة الإجابة إذا أردت وضع الكثير من الأسئلة على صفحة لأنهم قريبون من بعضهم."
type: docs
weight: 250
url: /ar/net/aspose.omr.generation.config.elements/answersheetconfig/
---
## AnswerSheetConfig class

يمثل عنصر ورقة الإجابة. يسمح بإضافة صناديق الاختيار مجمّعة في أعمدة وصفوف. استخدم ورقة الإجابة إذا أردت وضع الكثير من الأسئلة على صفحة لأنهم قريبون من بعضهم.

```csharp
public class AnswerSheetConfig : BaseConfig
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [AnswerSheetConfig](answersheetconfig)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AnswersCount](../../aspose.omr.generation.config.elements/answersheetconfig/answerscount) { get; set; } | عدد خيارات الإجابة لكل سؤال في ورقة الإجابات. |
| [AnswersValues](../../aspose.omr.generation.config.elements/answersheetconfig/answersvalues) { get; set; } | كل قيمة تمثل رمزًا داخل الفقاعة. يجب أن يكون العدد مساويًا للعدد في [`AnswersCount`](./answerscount) مثال: new string[] {\"A\", \"B\", \"C\", \"D\"} مثال: new string[] {\"1\", \"2\", \"3\", \"4\"} |
| [BubbleType](../../aspose.omr.generation.config.elements/answersheetconfig/bubbletype) { get; set; } | نوع الفقاعة |
| [Column](../../aspose.omr.generation.config.elements/answersheetconfig/column) { get; set; } | يشير إلى العمود الذي سيتم رسم الورقة فيه |
| [ColumnsCount](../../aspose.omr.generation.config.elements/answersheetconfig/columnscount) { get; set; } | يضبط عدد الأعمدة التي سيتم رسمها. |
| [ElementsCount](../../aspose.omr.generation.config.elements/answersheetconfig/elementscount) { get; set; } | يحدد العدد الإجمالي للأسئلة في ورقة الإجابات. |
| [Multiselect](../../aspose.omr.generation.config.elements/answersheetconfig/multiselect) { get; set; } | السماح باختيار إجابات متعددة لكل سؤال يتجاوز الإعدادات الافتراضية في [`Multiselect`](../../aspose.omr.generation/globalpagesettings/multiselect) |
| override [Name](../../aspose.omr.generation.config.elements/answersheetconfig/name) { get; set; } | اسم ورقة الإجابات |
| [StartId](../../aspose.omr.generation.config.elements/answersheetconfig/startid) { get; set; } | الفهرس الابتدائي لترقيم الأسئلة |
| override [Type](../../aspose.omr.generation.config.elements/answersheetconfig/type) { get; set; } | نوع عنصر OMR. حقل مطلوب لتسلسل JSON. |
| [VerticalMargin](../../aspose.omr.generation.config.elements/answersheetconfig/verticalmargin) { get; set; } | الهامش العمودي لورقة الإجابات. يُحدد بالبيكسل. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| [BubbleSize](../../aspose.omr.generation.config.elements/answersheetconfig/bubblesize) | حجم الفقاعة |

### انظر أيضًا

* class [BaseConfig](../../aspose.omr.generation.config/baseconfig)
* namespace [Aspose.OMR.Generation.Config.Elements](../../aspose.omr.generation.config.elements)
* assembly [Aspose.OMR](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ Aspose.OMR.dll -->
