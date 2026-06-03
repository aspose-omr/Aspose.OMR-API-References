---
title: "ContainerConfig"
second_title: "Aspose.OMR لـ .NET مرجع API"
description: "يمثل عنصر الحاوية."
type: docs
weight: 420
url: /ar/net/aspose.omr.generation.config.elements.parents/containerconfig/
---
## ContainerConfig class

يمثل عنصر الحاوية.

```csharp
public class ContainerConfig : ParentConfig
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ContainerConfig](containerconfig)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BlockBottomMargin](../../aspose.omr.generation.config.elements.parents/containerconfig/blockbottommargin) { get; set; } | عدد البكسلات التي سيتم وضعها أسفل الكتل. |
| [BlockRightMargin](../../aspose.omr.generation.config.elements.parents/containerconfig/blockrightmargin) { get; set; } | عدد البكسلات التي سيتم وضعها بين الكتل على الجانب الأيمن |
| [BlockTopPadding](../../aspose.omr.generation.config.elements.parents/containerconfig/blocktoppadding) { get; set; } | عدد البكسلات التي سيتم وضعها بعد الحد العلوي للكتلة. |
| override [Children](../../aspose.omr.generation.config.elements.parents/containerconfig/children) { get; set; } | عناصر OMR الفرعية. في معظم الحالات تكون موضوعة داخل العنصر الأب أو تحته. |
| [ColumnsCount](../../aspose.omr.generation.config.elements.parents/containerconfig/columnscount) { get; set; } | عدد الأعمدة داخل الحاوية. مقسمة إلى أعمدة متساوية. إصدار قديم من [`Proportions`](./proportions) |
| [ContainerType](../../aspose.omr.generation.config.elements.parents/containerconfig/containertype) { get; set; } | نوع الحاوية |
| override [Name](../../aspose.omr.generation.config.elements.parents/containerconfig/name) { get; set; } | اسم عنصر الحاوية |
| [Proportions](../../aspose.omr.generation.config.elements.parents/containerconfig/proportions) { get; set; } | قسّم كل عمود داخله بنسبة مخصصة النسخة الأحدث من [`ColumnsCount`](./columnscount) |
| [SyncBlockHeight](../../aspose.omr.generation.config.elements.parents/containerconfig/syncblockheight) { get; set; } | عند تعيينه إلى true يزامن كل ارتفاع العنصر الفرعي [`BlockConfig`](../blockconfig). الحد السفلي محاذى إلى الأطول. |
| override [Type](../../aspose.omr.generation.config.elements.parents/containerconfig/type) { get; set; } | نوع عنصر OMR. حقل مطلوب لتسلسل JSON. |

### انظر أيضًا

* class [ParentConfig](../../aspose.omr.generation.config/parentconfig)
* namespace [Aspose.OMR.Generation.Config.Elements.Parents](../../aspose.omr.generation.config.elements.parents)
* assembly [Aspose.OMR](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ Aspose.OMR.dll -->
