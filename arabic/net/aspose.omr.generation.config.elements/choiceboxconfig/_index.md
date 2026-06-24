---
title: "ChoiceBoxConfig"
second_title: "Aspose.OMR لـ .NET مرجع API"
description: "صندوق الاختيار هو عنصر أساسي يمثل سؤالًا واحدًا بعدد محدد من الإجابات."
type: docs
weight: 280
url: /ar/net/aspose.omr.generation.config.elements/choiceboxconfig/
---
## ChoiceBoxConfig class

صندوق الاختيار هو عنصر أساسي يمثل سؤالًا واحدًا بعدد محدد من الإجابات.

```csharp
public class ChoiceBoxConfig : ParentConfig
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [ChoiceBoxConfig](choiceboxconfig)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [Children](../../aspose.omr.generation.config.elements/choiceboxconfig/children) { get; set; } | عناصر OMR الفرعية. [`ChoiceBoxAnswerConfig`](../choiceboxanswerconfig) |
| [Color](../../aspose.omr.generation.config.elements/choiceboxconfig/color) { get; set; } | لون النص |
| [DisplayQuestionNumber](../../aspose.omr.generation.config.elements/choiceboxconfig/displayquestionnumber) { get; set; } | هل نعرض رقم هذا السؤال. بشكل افتراضي - true |
| [FontFamily](../../aspose.omr.generation.config.elements/choiceboxconfig/fontfamily) { get; set; } | عائلة الخط للنص |
| [FontSize](../../aspose.omr.generation.config.elements/choiceboxconfig/fontsize) { get; set; } | حجم خط النص |
| [FontStyle](../../aspose.omr.generation.config.elements/choiceboxconfig/fontstyle) { get; set; } | نمط النص |
| [Multiselect](../../aspose.omr.generation.config.elements/choiceboxconfig/multiselect) { get; set; } | السماح باختيار إجابات متعددة لكل سؤال يتجاوز الإعدادات الافتراضية في [`Multiselect`](../../aspose.omr.generation/globalpagesettings/multiselect) |
| override [Name](../../aspose.omr.generation.config.elements/choiceboxconfig/name) { get; set; } | اسم صندوق الاختيار. لقيمة العرض [`QuestionText`](./questiontext) |
| [QuestionText](../../aspose.omr.generation.config.elements/choiceboxconfig/questiontext) { get; set; } | يحصل أو يعيّن نص السؤال لعنصر ChoiceBox |
| [TextAlignment](../../aspose.omr.generation.config.elements/choiceboxconfig/textalignment) { get; set; } | محاذاة النص، تشير إلى مكان رسم النص على الصفحة |
| override [Type](../../aspose.omr.generation.config.elements/choiceboxconfig/type) { get; set; } | نوع عنصر OMR. حقل مطلوب لتسلسل JSON. |

### انظر أيضًا

* class [ParentConfig](../../aspose.omr.generation.config/parentconfig)
* namespace [Aspose.OMR.Generation.Config.Elements](../../aspose.omr.generation.config.elements)
* assembly [Aspose.OMR](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ Aspose.OMR.dll -->
