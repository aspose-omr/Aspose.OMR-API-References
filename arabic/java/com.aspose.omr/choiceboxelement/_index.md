---
title: "ChoiceBoxElement"
second_title: "مرجع Aspose.OMR لـ Java API"
description: "يمثل سؤال ChoiceBox"
type: docs
weight: 11
url: /ar/java/com.aspose.omr/choiceboxelement/
---

**Inheritance:**
java.lang.Object, [com.aspose.omr.OmrElement](../../com.aspose.omr/omrelement/)
```
public class ChoiceBoxElement extends OmrElement
```

يمثل سؤال ChoiceBox
## المُنشئات

| مُنشئ | الوصف |
| --- | --- |
| [ChoiceBoxElement()](#ChoiceBoxElement) | يُنشئ مثيلاً جديدًا من الفئة [ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) |
## الحقول

| حقل | الوصف |
| --- | --- |
| [ElementType](#ElementType) |  |
## طرق

| طريقة | الوصف |
| --- | --- |
| [addBubble(String name, int width, int height, int top, int left, boolean isValid)](#addBubble-java.lang.String-int-int-int-int-boolean) | يضيف فقاعة داخل السؤال |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getBubbleHeight()](#getBubbleHeight) |  |
| [getBubbleWidth()](#getBubbleWidth) |  |
| [getBubbles()](#getBubbles) | يحصل أو يعيّن مجموعة الفقاعات |
| [getClass()](#getClass) |  |
| [getHeight()](#getHeight) | يحصل أو يضبط ارتفاع السؤال |
| [getLeft()](#getLeft) | يحصل أو يضبط موضع السؤال الأيسر |
| [getMultipleSelectionAllowed()](#getMultipleSelectionAllowed) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان السماح بالاختيار المتعدد |
| [getName()](#getName) | يحصل على اسم السؤال |
| [getOrientation()](#getOrientation) |  |
| [getOrientationString()](#getOrientationString) | يحصل على تمثيل نصي لخاصية الاتجاه |
| [getRect()](#getRect) |  |
| [getTop()](#getTop) | يحصل أو يضبط موضع السؤال العلوي |
| [getWidth()](#getWidth) | يحصل أو يضبط عرض السؤال |
| [hashCode()](#hashCode) |  |
| [isAlignedHorizontal()](#isAlignedHorizontal) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت الفقاعات مصطفة أفقياً |
| [isAlignedVertical()](#isAlignedVertical) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت الفقاعات مصطفة عمودياً |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [setAlignedHorizontal(boolean value)](#setAlignedHorizontal-boolean) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت الفقاعات مصطفة أفقياً |
| [setAlignedVertical(boolean value)](#setAlignedVertical-boolean) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت الفقاعات مصطفة عمودياً |
| [setBubbleHeight(double value)](#setBubbleHeight-double) |  |
| [setBubbleWidth(double value)](#setBubbleWidth-double) |  |
| [setBubbles(System.Collections.Generic.List<OmrBubble> value)](#setBubbles-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrBubble) | يحصل أو يعيّن مجموعة الفقاعات |
| [setHeight(double value)](#setHeight-double) | يحصل أو يضبط ارتفاع السؤال |
| [setLeft(double value)](#setLeft-double) | يحصل أو يضبط موضع السؤال الأيسر |
| [setMultipleSelectionAllowed(boolean value)](#setMultipleSelectionAllowed-boolean) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان السماح بالاختيار المتعدد |
| [setName(String value)](#setName-java.lang.String) | يضبط اسم السؤال |
| [setOrientation(int value)](#setOrientation-int) |  |
| [setTop(double value)](#setTop-double) | يحصل أو يضبط موضع السؤال العلوي |
| [setWidth(double value)](#setWidth-double) | يحصل أو يضبط عرض السؤال |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### ChoiceBoxElement() {#ChoiceBoxElement}
```
public ChoiceBoxElement()
```


يُنشئ مثيلاً جديدًا من الفئة [ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/)

### ElementType {#ElementType}
```
public String ElementType
```


### addBubble(String name, int width, int height, int top, int left, boolean isValid) {#addBubble-java.lang.String-int-int-int-int-boolean}
```
public final void addBubble(String name, int width, int height, int top, int left, boolean isValid)
```


يضيف فقاعة داخل السؤال

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | اسم الفقاعة |
| العرض | int | عرض الفقاعة |
| الارتفاع | int | ارتفاع الفقاعة |
| أعلى | int | موضع الفقاعة العلوي |
| يسار | int | موضع الفقاعة الأيسر |
| isValid | boolean | علامة صلاحية الفقاعة |

### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBubbleHeight() {#getBubbleHeight}
```
public final double getBubbleHeight()
```




**Returns:**
double
### getBubbleWidth() {#getBubbleWidth}
```
public final double getBubbleWidth()
```




**Returns:**
double
### getBubbles() {#getBubbles}
```
public final System.Collections.Generic.List<OmrBubble> getBubbles()
```


يحصل أو يعيّن مجموعة الفقاعات

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrBubble> - مجموعة الفقاعات
### getClass() {#getClass}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getHeight() {#getHeight}
```
public final double getHeight()
```


يحصل أو يضبط ارتفاع السؤال

**Returns:**
double - الارتفاع
### getLeft() {#getLeft}
```
public final double getLeft()
```


يحصل أو يضبط موضع السؤال الأيسر

**Returns:**
double - اليسار
### getMultipleSelectionAllowed() {#getMultipleSelectionAllowed}
```
public final boolean getMultipleSelectionAllowed()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان السماح بالاختيار المتعدد

**Returns:**
boolean - قيمة تشير إلى ما إذا كان السماح بالاختيار المتعدد
### getName() {#getName}
```
public final String getName()
```


يحصل على اسم السؤال

**Returns:**
java.lang.String - اسم السؤال
### getOrientation() {#getOrientation}
```
public final int getOrientation()
```




**Returns:**
int
### getOrientationString() {#getOrientationString}
```
public final String getOrientationString()
```


يحصل على تمثيل نصي لخاصية الاتجاه

**Returns:**
java.lang.String - تمثيل نصي لخاصية الاتجاه
### getRect() {#getRect}
```
public System.Drawing.RectangleF getRect()
```




**Returns:**
com.aspose.ms.System.Drawing.RectangleF
### getTop() {#getTop}
```
public final double getTop()
```


يحصل أو يضبط موضع السؤال العلوي

**Returns:**
double - الأعلى
### getWidth() {#getWidth}
```
public final double getWidth()
```


يحصل أو يضبط عرض السؤال

**Returns:**
double - العرض
### hashCode() {#hashCode}
```
public native int hashCode()
```




**Returns:**
int
### isAlignedHorizontal() {#isAlignedHorizontal}
```
public final boolean isAlignedHorizontal()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت الفقاعات مصطفة أفقياً

**Returns:**
boolean - قيمة تشير إلى ما إذا كانت الفقاعات مصطفة أفقياً
### isAlignedVertical() {#isAlignedVertical}
```
public final boolean isAlignedVertical()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت الفقاعات مصطفة عمودياً

**Returns:**
boolean - قيمة تشير إلى ما إذا كانت الفقاعات مصطفة عمودياً
### notify() {#notify}
```
public final native void notify()
```




### notifyAll() {#notifyAll}
```
public final native void notifyAll()
```




### setAlignedHorizontal(boolean value) {#setAlignedHorizontal-boolean}
```
public final void setAlignedHorizontal(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت الفقاعات مصطفة أفقياً

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean | قيمة تشير إلى ما إذا كانت الفقاعات مصطفة أفقياً |

### setAlignedVertical(boolean value) {#setAlignedVertical-boolean}
```
public final void setAlignedVertical(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت الفقاعات مصطفة عمودياً

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean | قيمة تشير إلى ما إذا كانت الفقاعات مصطفة عمودياً |

### setBubbleHeight(double value) {#setBubbleHeight-double}
```
public final void setBubbleHeight(double value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

### setBubbleWidth(double value) {#setBubbleWidth-double}
```
public final void setBubbleWidth(double value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

### setBubbles(System.Collections.Generic.List<OmrBubble> value) {#setBubbles-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrBubble}
```
public final void setBubbles(System.Collections.Generic.List<OmrBubble> value)
```


يحصل أو يعيّن مجموعة الفقاعات

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrBubble> | مجموعة الفقاعات |

### setHeight(double value) {#setHeight-double}
```
public final void setHeight(double value)
```


يحصل أو يضبط ارتفاع السؤال

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double | الارتفاع |

### setLeft(double value) {#setLeft-double}
```
public final void setLeft(double value)
```


يحصل أو يضبط موضع السؤال الأيسر

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double | اليسار |

### setMultipleSelectionAllowed(boolean value) {#setMultipleSelectionAllowed-boolean}
```
public final void setMultipleSelectionAllowed(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان السماح بالاختيار المتعدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean | قيمة تشير إلى ما إذا كان السماح بالاختيار المتعدد |

### setName(String value) {#setName-java.lang.String}
```
public final void setName(String value)
```


يضبط اسم السؤال

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String | اسم السؤال |

### setOrientation(int value) {#setOrientation-int}
```
public final void setOrientation(int value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setTop(double value) {#setTop-double}
```
public final void setTop(double value)
```


يحصل أو يضبط موضع السؤال العلوي

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double | الأعلى |

### setWidth(double value) {#setWidth-double}
```
public final void setWidth(double value)
```


يحصل أو يضبط عرض السؤال

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double | العرض |

### toString() {#toString}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait}
```
public final void wait()
```




### wait(long arg0) {#wait-long}
```
public final native void wait(long arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

