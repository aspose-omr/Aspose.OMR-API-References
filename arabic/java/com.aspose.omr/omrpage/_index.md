---
title: "OmrPage"
second_title: "مرجع Aspose.OMR لـ Java API"
description: "يمثل صفحة OMR واحدة"
type: docs
weight: 24
url: /ar/java/com.aspose.omr/omrpage/
---

**Inheritance:**
java.lang.Object
```
public class OmrPage
```

يمثل صفحة OMR واحدة
## المُنشئات

| مُنشئ | الوصف |
| --- | --- |
| [OmrPage()](#OmrPage) | يُنشئ مثلاً جديداً من الفئة [OmrPage](../../com.aspose.omr/omrpage/) |
## طرق

| طريقة | الوصف |
| --- | --- |
| [addBarcodeElement(BarcodeElement element)](#addBarcodeElement-com.aspose.omr.BarcodeElement) |  |
| [addChoiceBoxElement(String name, int width, int height, int top, int left)](#addChoiceBoxElement-java.lang.String-int-int-int-int) | أضف عنصر صندوق اختيار على الصفحة |
| [addClipAreaElement(String name, int width, int height, int top, int left)](#addClipAreaElement-java.lang.String-int-int-int-int) |  |
| [addGridElement(GridElement grid)](#addGridElement-com.aspose.omr.GridElement) |  |
| [addGridElement(String name, int width, int height, int top, int left)](#addGridElement-java.lang.String-int-int-int-int) |  |
| [addRefPointElement(ReferencePointElement item)](#addRefPointElement-com.aspose.omr.ReferencePointElement) |  |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [getElements()](#getElements) | يحصل أو يضبط قائمة العناصر على الصفحة |
| [getHeight()](#getHeight) | يحصل أو يضبط ارتفاع الصفحة |
| [getImageFormat()](#getImageFormat) | يحصل أو يضبط تنسيق ملف الصورة |
| [getImageName()](#getImageName) | يحصل أو يضبط بيانات الصورة |
| [getRotationPointPosition()](#getRotationPointPosition) | يحصل أو يضبط RotationPointPosition |
| [getWidth()](#getWidth) | يحصل أو يضبط عرض الصفحة |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [setElements(System.Collections.Generic.List<OmrElement> value)](#setElements-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement) | يحصل أو يضبط قائمة العناصر على الصفحة |
| [setHeight(double value)](#setHeight-double) | يحصل أو يضبط ارتفاع الصفحة |
| [setImageFormat(String value)](#setImageFormat-java.lang.String) | يحصل أو يضبط تنسيق ملف الصورة |
| [setImageName(String value)](#setImageName-java.lang.String) | يحصل أو يضبط اسم الصورة |
| [setRotationPointPosition(RotationPointPosition value)](#setRotationPointPosition-com.aspose.omr.RotationPointPosition) | يحصل أو يضبط RotationPointPosition |
| [setWidth(double value)](#setWidth-double) | يحصل أو يضبط عرض الصفحة |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### OmrPage() {#OmrPage}
```
public OmrPage()
```


يُنشئ مثلاً جديداً من الفئة [OmrPage](../../com.aspose.omr/omrpage/)

### addBarcodeElement(BarcodeElement element) {#addBarcodeElement-com.aspose.omr.BarcodeElement}
```
public final void addBarcodeElement(BarcodeElement element)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| element | [BarcodeElement](../../com.aspose.omr/barcodeelement/) |  |

### addChoiceBoxElement(String name, int width, int height, int top, int left) {#addChoiceBoxElement-java.lang.String-int-int-int-int}
```
public final ChoiceBoxElement addChoiceBoxElement(String name, int width, int height, int top, int left)
```


أضف عنصر صندوق اختيار على الصفحة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | اسم العنصر |
| العرض | int | عرض العنصر |
| الارتفاع | int | ارتفاع العنصر |
| أعلى | int | موضع أعلى العنصر |
| يسار | int | موضع يسار العنصر |

**Returns:**
[ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) - Created choice box
### addClipAreaElement(String name, int width, int height, int top, int left) {#addClipAreaElement-java.lang.String-int-int-int-int}
```
public final ClipAreaElement addClipAreaElement(String name, int width, int height, int top, int left)
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
[ClipAreaElement](../../com.aspose.omr/clipareaelement/)
### addGridElement(GridElement grid) {#addGridElement-com.aspose.omr.GridElement}
```
public final void addGridElement(GridElement grid)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| grid | [GridElement](../../com.aspose.omr/gridelement/) |  |

### addGridElement(String name, int width, int height, int top, int left) {#addGridElement-java.lang.String-int-int-int-int}
```
public final GridElement addGridElement(String name, int width, int height, int top, int left)
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
[GridElement](../../com.aspose.omr/gridelement/)
### addRefPointElement(ReferencePointElement item) {#addRefPointElement-com.aspose.omr.ReferencePointElement}
```
public final void addRefPointElement(ReferencePointElement item)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [ReferencePointElement](../../com.aspose.omr/referencepointelement/) |  |

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
### getClass() {#getClass}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getElements() {#getElements}
```
public final System.Collections.Generic.List<OmrElement> getElements()
```


يحصل أو يضبط قائمة العناصر على الصفحة

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrElement> - قائمة العناصر في الصفحة
### getHeight() {#getHeight}
```
public final double getHeight()
```


يحصل أو يضبط ارتفاع الصفحة

**Returns:**
double - ارتفاع الصفحة
### getImageFormat() {#getImageFormat}
```
public final String getImageFormat()
```


يحصل أو يضبط تنسيق ملف الصورة

**Returns:**
java.lang.String - تنسيق ملف الصورة
### getImageName() {#getImageName}
```
public final String getImageName()
```


يحصل أو يضبط بيانات الصورة

**Returns:**
java.lang.String - اسم الصورة
### getRotationPointPosition() {#getRotationPointPosition}
```
public final RotationPointPosition getRotationPointPosition()
```


يحصل أو يضبط RotationPointPosition

**Returns:**
[RotationPointPosition](../../com.aspose.omr/rotationpointposition/) - RotationPointPosition
### getWidth() {#getWidth}
```
public final double getWidth()
```


يحصل أو يضبط عرض الصفحة

**Returns:**
double - عرض الصفحة
### hashCode() {#hashCode}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify}
```
public final native void notify()
```




### notifyAll() {#notifyAll}
```
public final native void notifyAll()
```




### setElements(System.Collections.Generic.List<OmrElement> value) {#setElements-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement}
```
public final void setElements(System.Collections.Generic.List<OmrElement> value)
```


يحصل أو يضبط قائمة العناصر على الصفحة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrElement> | قائمة العناصر في الصفحة |

### setHeight(double value) {#setHeight-double}
```
public final void setHeight(double value)
```


يحصل أو يضبط ارتفاع الصفحة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double | ارتفاع الصفحة |

### setImageFormat(String value) {#setImageFormat-java.lang.String}
```
public final void setImageFormat(String value)
```


يحصل أو يضبط تنسيق ملف الصورة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String | تنسيق ملف الصورة |

### setImageName(String value) {#setImageName-java.lang.String}
```
public final void setImageName(String value)
```


يحصل أو يضبط اسم الصورة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String | اسم الصورة |

### setRotationPointPosition(RotationPointPosition value) {#setRotationPointPosition-com.aspose.omr.RotationPointPosition}
```
public final void setRotationPointPosition(RotationPointPosition value)
```


يحصل أو يضبط RotationPointPosition

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RotationPointPosition](../../com.aspose.omr/rotationpointposition/) | RotationPointPosition |

### setWidth(double value) {#setWidth-double}
```
public final void setWidth(double value)
```


يحصل أو يضبط عرض الصفحة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double | عرض الصفحة |

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

