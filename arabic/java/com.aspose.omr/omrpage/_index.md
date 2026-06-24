---
title: "OmrPage"
second_title: "مرجع API لـ Aspose.OMR for Java"
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

| المُنشئ | الوصف |
| --- | --- |
| [OmrPage()](#OmrPage) | يُنشئ مثيلًا جديدًا من الفئة [OmrPage](../../com.aspose.omr/omrpage/) |
## الطرق

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
| [getHeight()](#getHeight) | الحصول أو تعيين ارتفاع الصفحة |
| [getImageFormat()](#getImageFormat) | الحصول أو تعيين تنسيق ملف الصورة |
| [getImageName()](#getImageName) | الحصول أو تعيين بيانات الصورة |
| [getRotationPointPosition()](#getRotationPointPosition) | الحصول أو تعيين RotationPointPosition |
| [getWidth()](#getWidth) | الحصول أو تعيين عرض الصفحة |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [setElements(System.Collections.Generic.List<OmrElement> value)](#setElements-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement) | يحصل أو يضبط قائمة العناصر على الصفحة |
| [setHeight(double value)](#setHeight-double) | الحصول أو تعيين ارتفاع الصفحة |
| [setImageFormat(String value)](#setImageFormat-java.lang.String) | الحصول أو تعيين تنسيق ملف الصورة |
| [setImageName(String value)](#setImageName-java.lang.String) | الحصول أو تعيين اسم الصورة |
| [setRotationPointPosition(RotationPointPosition value)](#setRotationPointPosition-com.aspose.omr.RotationPointPosition) | الحصول أو تعيين RotationPointPosition |
| [setWidth(double value)](#setWidth-double) | الحصول أو تعيين عرض الصفحة |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### OmrPage() {#OmrPage}
```
public OmrPage()
```


يُنشئ مثيلًا جديدًا من الفئة [OmrPage](../../com.aspose.omr/omrpage/)

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


الحصول أو تعيين ارتفاع الصفحة

**Returns:**
double - ارتفاع الصفحة
### getImageFormat() {#getImageFormat}
```
public final String getImageFormat()
```


الحصول أو تعيين تنسيق ملف الصورة

**Returns:**
java.lang.String - تنسيق ملف الصورة
### getImageName() {#getImageName}
```
public final String getImageName()
```


الحصول أو تعيين بيانات الصورة

**Returns:**
java.lang.String - اسم الصورة
### getRotationPointPosition() {#getRotationPointPosition}
```
public final RotationPointPosition getRotationPointPosition()
```


الحصول أو تعيين RotationPointPosition

**Returns:**
[RotationPointPosition](../../com.aspose.omr/rotationpointposition/) - RotationPointPosition
### getWidth() {#getWidth}
```
public final double getWidth()
```


الحصول أو تعيين عرض الصفحة

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


الحصول أو تعيين ارتفاع الصفحة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double | ارتفاع الصفحة |

### setImageFormat(String value) {#setImageFormat-java.lang.String}
```
public final void setImageFormat(String value)
```


الحصول أو تعيين تنسيق ملف الصورة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String | تنسيق ملف الصورة |

### setImageName(String value) {#setImageName-java.lang.String}
```
public final void setImageName(String value)
```


الحصول أو تعيين اسم الصورة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String | اسم الصورة |

### setRotationPointPosition(RotationPointPosition value) {#setRotationPointPosition-com.aspose.omr.RotationPointPosition}
```
public final void setRotationPointPosition(RotationPointPosition value)
```


الحصول أو تعيين RotationPointPosition

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RotationPointPosition](../../com.aspose.omr/rotationpointposition/) | RotationPointPosition |

### setWidth(double value) {#setWidth-double}
```
public final void setWidth(double value)
```


الحصول أو تعيين عرض الصفحة

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

