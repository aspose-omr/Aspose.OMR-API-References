---
title: "CompositeGridConfig"
second_title: "Aspose.OMR لـ .NET مرجع API"
description: "عنصر الشبكة. ينتج مصفوفة من الفقاعات. كل فقاعة مملوءة تمثل رمزًا واحدًا في القيمة المركبة. جميع الرموز المعلَّمة سيتم دمجها في قيمة واحدة."
type: docs
weight: 290
url: /ar/net/aspose.omr.generation.config.elements/compositegridconfig/
---
## CompositeGridConfig class

عنصر الشبكة. ينتج مصفوفة من الفقاعات. كل فقاعة مملوءة تمثل رمزًا واحدًا في القيمة المركبة. جميع الرموز المعلَّمة سيتم دمجها في قيمة واحدة.

```csharp
public class CompositeGridConfig : BaseConfig
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [CompositeGridConfig](compositegridconfig)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BubbleType](../../aspose.omr.generation.config.elements/compositegridconfig/bubbletype) { get; set; } | نوع الفقاعة |
| [Column](../../aspose.omr.generation.config.elements/compositegridconfig/column) { get; set; } | عند رسم العنصر في عنصر أب متعدد الأعمدة - يمثل الموقع. |
| [ColumnsCount](../../aspose.omr.generation.config.elements/compositegridconfig/columnscount) { get; set; } | عدد الأعمدة داخل الشبكة. كل عمود يمثل رمزًا واحدًا في قيمة النتيجة. يجب أن يكون العدد مساويًا لعدد الأعمدة في [`ExtraRow`](./extrarow). |
| [DisplayHint](../../aspose.omr.generation.config.elements/compositegridconfig/displayhint) { get; set; } | هل يجب عرض اسم هذه الشبكة |
| [ExtraRow](../../aspose.omr.generation.config.elements/compositegridconfig/extrarow) { get; set; } | القيم الخاصة بكل عمود التي ستوضع فوق القيم الافتراضية - [`Values`](./values). تُعرض كمصفوفة ثنائية الأبعاد. الأول - الصف. الثاني - العمود. كل سلسلة تمثل نصًا داخل الفقاعة. إذا كانت السلسلة فارغة (null) لن يتم وضع فقاعة. يجب أن يكون عدد الأعمدة مساويًا لـ [`ColumnsCount`](./columnscount). |
| [GridAlignment](../../aspose.omr.generation.config.elements/compositegridconfig/gridalignment) { get; set; } | محاذاة الشبكة، تشير إلى مكان رسم الشبكة على الصفحة |
| [GridOrientation](../../aspose.omr.generation.config.elements/compositegridconfig/gridorientation) { get; set; } | اتجاه الشبكة: أفقي أو عمودي. يشير إلى كيفية تموضع العناصر الفرعية |
| [HeaderBorderColor](../../aspose.omr.generation.config.elements/compositegridconfig/headerbordercolor) { get; set; } | لون حد المربع |
| [HeaderBorderSize](../../aspose.omr.generation.config.elements/compositegridconfig/headerbordersize) { get; set; } | حجم حد المربع |
| [HeaderType](../../aspose.omr.generation.config.elements/compositegridconfig/headertype) { get; set; } | يشير إلى نوع العنصر الذي يجب رسمه في بداية الشبكة |
| override [Name](../../aspose.omr.generation.config.elements/compositegridconfig/name) { get; set; } | اسم الشبكة. يُستخدم كمعرف في التعرف |
| [RotationAngle](../../aspose.omr.generation.config.elements/compositegridconfig/rotationangle) { get; set; } | وصف دوران عنصر الشبكة حول محوره الخاص. "90" - تدوير CompositeGrid 90 درجة "-90" - تدوير ComopositeGrid إلى -90 درجة |
| override [Type](../../aspose.omr.generation.config.elements/compositegridconfig/type) { get; set; } | نوع عنصر OMR. حقل مطلوب لتسلسل JSON. |
| [Values](../../aspose.omr.generation.config.elements/compositegridconfig/values) { get; set; } | مجموعة من السلاسل التي ستصف الرموز الممكنة في كل عمود. القيم الخاصة بكل عمود توضع في [`ExtraRow`](./extrarow). |
| [XPosition](../../aspose.omr.generation.config.elements/compositegridconfig/xposition) { get; set; } | موضع X للشبكة على الصفحة، يتجاوز المحاذاة |
| [YPosition](../../aspose.omr.generation.config.elements/compositegridconfig/yposition) { get; set; } | موضع Y للشبكة على الصفحة، يتجاوز المحاذاة |

## الحقول

| الاسم | الوصف |
| --- | --- |
| [BubbleSize](../../aspose.omr.generation.config.elements/compositegridconfig/bubblesize) | حجم الفقاعة |
| [VerticalMargin](../../aspose.omr.generation.config.elements/compositegridconfig/verticalmargin) | الهامش بين الأسطر |

### انظر أيضًا

* class [BaseConfig](../../aspose.omr.generation.config/baseconfig)
* namespace [Aspose.OMR.Generation.Config.Elements](../../aspose.omr.generation.config.elements)
* assembly [Aspose.OMR](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ Aspose.OMR.dll -->
