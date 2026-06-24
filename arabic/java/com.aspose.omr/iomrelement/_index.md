---
title: "IOmrElement"
second_title: "مرجع API لـ Aspose.OMR for Java"
description: "الواجهة لعناصر OMR"
type: docs
weight: 31
url: /ar/java/com.aspose.omr/iomrelement/
---
```
public interface IOmrElement
```

الواجهة لعناصر OMR
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getAnswer()](#getAnswer) | يشكّل سلسلة تحتوي على نتيجة التعرف |
| [getCsv()](#getCsv) | يشكّل الإجابات كسلسلة قيم مفصولة بفواصل |
| [getQuestionName()](#getQuestionName) | يحصل على اسم السؤال |
| [setQuestionName(String value)](#setQuestionName-java.lang.String) | يضبط اسم السؤال |
### getAnswer() {#getAnswer}
```
public abstract String getAnswer()
```


يشكّل سلسلة تحتوي على نتيجة التعرف

**Returns:**
java.lang.String - سلسلة تحتوي على نتيجة التعرف
### getCsv() {#getCsv}
```
public abstract String getCsv()
```


يشكّل الإجابات كسلسلة قيم مفصولة بفواصل

**Returns:**
java.lang.String - نتائج التعرف كسلسلة CSV
### getQuestionName() {#getQuestionName}
```
public abstract String getQuestionName()
```


يحصل على اسم السؤال

**Returns:**
java.lang.String - اسم السؤال
### setQuestionName(String value) {#setQuestionName-java.lang.String}
```
public abstract void setQuestionName(String value)
```


يضبط اسم السؤال

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String | اسم السؤال |

