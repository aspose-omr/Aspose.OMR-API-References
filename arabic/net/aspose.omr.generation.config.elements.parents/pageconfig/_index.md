---
title: "PageConfig"
second_title: "Aspose.OMR لـ .NET مرجع API"
description: "يمثل عنصر الصفحة. واحد لكل صفحة. يجب وضعه داخل TemplateConfig../aspose.omr.generation.config/templateconfig"
type: docs
weight: 430
url: /ar/net/aspose.omr.generation.config.elements.parents/pageconfig/
---
## PageConfig class

يمثل عنصر الصفحة. واحد لكل صفحة. يجب وضعه داخل [`TemplateConfig`](../../aspose.omr.generation.config/templateconfig)

```csharp
public class PageConfig : ParentConfig
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [PageConfig](pageconfig)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [Children](../../aspose.omr.generation.config.elements.parents/pageconfig/children) { get; set; } | عناصر OMR الفرعية. في معظم الحالات تكون موضوعة داخل العنصر الأب أو تحته. |
| [LeftMargin](../../aspose.omr.generation.config.elements.parents/pageconfig/leftmargin) { get; set; } | المسافة بالبكسل على الجانب الأيسر من اللوحة. تتجاوز القيمة المقدمة من [`PageMarginLeft`](../../aspose.omr.generation/globalpagesettings/pagemarginleft) |
| override [Name](../../aspose.omr.generation.config.elements.parents/pageconfig/name) { get; set; } | اسم الصفحة |
| [Orientation](../../aspose.omr.generation.config.elements.parents/pageconfig/orientation) { get; set; } | اتجاه هذه الصفحة. يتجاوز القيمة المقدمة من [`Orientation`](../../aspose.omr.generation/globalpagesettings/orientation) |
| [PaperSize](../../aspose.omr.generation.config.elements.parents/pageconfig/papersize) { get; set; } | حجم الورق لهذه الصفحة. يتجاوز القيمة المقدمة من [`PaperSize`](../../aspose.omr.generation/globalpagesettings/papersize) |
| [RightMargin](../../aspose.omr.generation.config.elements.parents/pageconfig/rightmargin) { get; set; } | المسافة بالبكسل على الجانب الأيمن من اللوحة. تتجاوز القيمة المقدمة من [`PageMarginRight`](../../aspose.omr.generation/globalpagesettings/pagemarginright) |
| [RotationPointPosition](../../aspose.omr.generation.config.elements.parents/pageconfig/rotationpointposition) { get; set; } | موضع نقطة الدوران المطلوبة على هذه الصفحة إذا لم يتم تعيينه - سيتم استخدام TopRight1. يتجاوز القيمة المقدمة من !:GlobalPageSettings.RotationPointPosition |
| override [Type](../../aspose.omr.generation.config.elements.parents/pageconfig/type) { get; set; } | نوع عنصر OMR. حقل مطلوب لتسلسل JSON. |

### انظر أيضًا

* class [ParentConfig](../../aspose.omr.generation.config/parentconfig)
* namespace [Aspose.OMR.Generation.Config.Elements.Parents](../../aspose.omr.generation.config.elements.parents)
* assembly [Aspose.OMR](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ Aspose.OMR.dll -->
