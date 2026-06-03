---
title: "GridElement"
second_title: "مرجع Aspose.OMR لـ Java API"
description: 
type: docs
weight: 16
url: /ar/java/com.aspose.omr/gridelement/
---

**Inheritance:**
java.lang.Object, [com.aspose.omr.OmrElement](../../com.aspose.omr/omrelement/)
```
public class GridElement extends OmrElement
```
## المُنشئات

| مُنشئ | الوصف |
| --- | --- |
| [GridElement()](#GridElement) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
| [ElementType](#ElementType) |  |
## طرق

| طريقة | الوصف |
| --- | --- |
| [addChoiceBox(ChoiceBoxElement choiceBox)](#addChoiceBox-com.aspose.omr.ChoiceBoxElement) |  |
| [addChoiceBox(String name, int width, int height, int top, int left)](#addChoiceBox-java.lang.String-int-int-int-int) |  |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getChoiceBoxes()](#getChoiceBoxes) |  |
| [getClass()](#getClass) |  |
| [getHeight()](#getHeight) | يحصل أو يضبط ارتفاع السؤال |
| [getLeft()](#getLeft) | يحصل أو يضبط موضع السؤال الأيسر |
| [getName()](#getName) | يحصل على اسم السؤال |
| [getOrientation()](#getOrientation) |  |
| [getOrientationString()](#getOrientationString) |  |
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
| [setChoiceBoxes(System.Collections.Generic.List<OmrElement> value)](#setChoiceBoxes-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement) |  |
| [setHeight(double value)](#setHeight-double) | يحصل أو يضبط ارتفاع السؤال |
| [setLeft(double value)](#setLeft-double) | يحصل أو يضبط موضع السؤال الأيسر |
| [setName(String value)](#setName-java.lang.String) | يضبط اسم السؤال |
| [setOrientation(int value)](#setOrientation-int) |  |
| [setTop(double value)](#setTop-double) | يحصل أو يضبط موضع السؤال العلوي |
| [setWidth(double value)](#setWidth-double) | يحصل أو يضبط عرض السؤال |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### GridElement() {#GridElement}
```
public GridElement()
```


### ElementType {#ElementType}
```
public String ElementType
```


### addChoiceBox(ChoiceBoxElement choiceBox) {#addChoiceBox-com.aspose.omr.ChoiceBoxElement}
```
public final void addChoiceBox(ChoiceBoxElement choiceBox)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| choiceBox | [ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) |  |

### addChoiceBox(String name, int width, int height, int top, int left) {#addChoiceBox-java.lang.String-int-int-int-int}
```
public final ChoiceBoxElement addChoiceBox(String name, int width, int height, int top, int left)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String |  |
| العرض | int |  |
| الارتفاع | int |  |
| أعلى | int |  |
| يسار | int |  |

**Returns:**
[ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/)
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
### getChoiceBoxes() {#getChoiceBoxes}
```
public final System.Collections.Generic.List<OmrElement> getChoiceBoxes()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrElement>
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




**Returns:**
java.lang.String
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

### setChoiceBoxes(System.Collections.Generic.List<OmrElement> value) {#setChoiceBoxes-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement}
```
public final void setChoiceBoxes(System.Collections.Generic.List<OmrElement> value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrElement> |  |

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

