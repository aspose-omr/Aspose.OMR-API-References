---
title: "ChoiceBoxElement"
second_title: "Aspose.OMR for Java API Referansı"
description: "ChoiceBox sorusunu temsil eder"
type: docs
weight: 11
url: /tr/java/com.aspose.omr/choiceboxelement/
---

**Inheritance:**
java.lang.Object, [com.aspose.omr.OmrElement](../../com.aspose.omr/omrelement/)
```
public class ChoiceBoxElement extends OmrElement
```

ChoiceBox sorusunu temsil eder
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ChoiceBoxElement()](#ChoiceBoxElement) | Yeni bir [ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) sınıfının örneğini başlatır |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [ElementType](#ElementType) |  |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [addBubble(String name, int width, int height, int top, int left, boolean isValid)](#addBubble-java.lang.String-int-int-int-int-boolean) | Sorunun içine bubble ekler |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getBubbleHeight()](#getBubbleHeight) |  |
| [getBubbleWidth()](#getBubbleWidth) |  |
| [getBubbles()](#getBubbles) | bubbles koleksiyonunu alır veya ayarlar |
| [getClass()](#getClass) |  |
| [getHeight()](#getHeight) | Soru yüksekliğini alır veya ayarlar |
| [getLeft()](#getLeft) | Soru sol konumunu alır veya ayarlar |
| [getMultipleSelectionAllowed()](#getMultipleSelectionAllowed) | Çoklu seçim izin verilip verilmediğini gösteren değeri alır veya ayarlar |
| [getName()](#getName) | Soru adını alır |
| [getOrientation()](#getOrientation) |  |
| [getOrientationString()](#getOrientationString) | orientation özelliğinin string temsilini alır |
| [getRect()](#getRect) |  |
| [getTop()](#getTop) | Soru üst konumunu alır veya ayarlar |
| [getWidth()](#getWidth) | Soru genişliğini alır veya ayarlar |
| [hashCode()](#hashCode) |  |
| [isAlignedHorizontal()](#isAlignedHorizontal) | Balonların yatay olarak hizalanıp hizalanmadığını belirten değeri alır veya ayarlar |
| [isAlignedVertical()](#isAlignedVertical) | Balonların dikey olarak hizalanıp hizalanmadığını belirten değeri alır veya ayarlar |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [setAlignedHorizontal(boolean value)](#setAlignedHorizontal-boolean) | Balonların yatay olarak hizalanıp hizalanmadığını belirten değeri alır veya ayarlar |
| [setAlignedVertical(boolean value)](#setAlignedVertical-boolean) | Balonların dikey olarak hizalanıp hizalanmadığını belirten değeri alır veya ayarlar |
| [setBubbleHeight(double value)](#setBubbleHeight-double) |  |
| [setBubbleWidth(double value)](#setBubbleWidth-double) |  |
| [setBubbles(System.Collections.Generic.List<OmrBubble> value)](#setBubbles-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrBubble) | bubbles koleksiyonunu alır veya ayarlar |
| [setHeight(double value)](#setHeight-double) | Soru yüksekliğini alır veya ayarlar |
| [setLeft(double value)](#setLeft-double) | Soru sol konumunu alır veya ayarlar |
| [setMultipleSelectionAllowed(boolean value)](#setMultipleSelectionAllowed-boolean) | Çoklu seçim izin verilip verilmediğini gösteren değeri alır veya ayarlar |
| [setName(String value)](#setName-java.lang.String) | Soru adını ayarlar |
| [setOrientation(int value)](#setOrientation-int) |  |
| [setTop(double value)](#setTop-double) | Soru üst konumunu alır veya ayarlar |
| [setWidth(double value)](#setWidth-double) | Soru genişliğini alır veya ayarlar |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### ChoiceBoxElement() {#ChoiceBoxElement}
```
public ChoiceBoxElement()
```


Yeni bir [ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) sınıfının örneğini başlatır

### ElementType {#ElementType}
```
public String ElementType
```


### addBubble(String name, int width, int height, int top, int left, boolean isValid) {#addBubble-java.lang.String-int-int-int-int-boolean}
```
public final void addBubble(String name, int width, int height, int top, int left, boolean isValid)
```


Sorunun içine bubble ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Bubble adı |
| genişlik | int | Bubble genişliği |
| yükseklik | int | Bubble yüksekliği |
| üst | int | Bubble üst konumu |
| sol | int | Bubble sol konumu |
| isValid | boolean | Bubble geçerli bayrağı |

### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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


bubbles koleksiyonunu alır veya ayarlar

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrBubble> - bubbles koleksiyonu
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


Soru yüksekliğini alır veya ayarlar

**Returns:**
double - Yükseklik
### getLeft() {#getLeft}
```
public final double getLeft()
```


Soru sol konumunu alır veya ayarlar

**Returns:**
double - Sol
### getMultipleSelectionAllowed() {#getMultipleSelectionAllowed}
```
public final boolean getMultipleSelectionAllowed()
```


Çoklu seçim izin verilip verilmediğini gösteren değeri alır veya ayarlar

**Returns:**
boolean - çoklu seçimin izin verilip verilmediğini gösteren değer
### getName() {#getName}
```
public final String getName()
```


Soru adını alır

**Returns:**
java.lang.String - Soru adı
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


orientation özelliğinin string temsilini alır

**Returns:**
java.lang.String - orientation özelliğinin string temsili
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


Soru üst konumunu alır veya ayarlar

**Returns:**
double - Üst
### getWidth() {#getWidth}
```
public final double getWidth()
```


Soru genişliğini alır veya ayarlar

**Returns:**
double - Genişlik
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


Balonların yatay olarak hizalanıp hizalanmadığını belirten değeri alır veya ayarlar

**Returns:**
boolean - balonların yatay hizalanıp hizalanmadığını belirten değer
### isAlignedVertical() {#isAlignedVertical}
```
public final boolean isAlignedVertical()
```


Balonların dikey olarak hizalanıp hizalanmadığını belirten değeri alır veya ayarlar

**Returns:**
boolean - balonların dikey hizalanıp hizalanmadığını belirten değer
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


Balonların yatay olarak hizalanıp hizalanmadığını belirten değeri alır veya ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | balonların yatay hizalanıp hizalanmadığını belirten değer |

### setAlignedVertical(boolean value) {#setAlignedVertical-boolean}
```
public final void setAlignedVertical(boolean value)
```


Balonların dikey olarak hizalanıp hizalanmadığını belirten değeri alır veya ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | balonların dikey hizalanıp hizalanmadığını belirten değer |

### setBubbleHeight(double value) {#setBubbleHeight-double}
```
public final void setBubbleHeight(double value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setBubbleWidth(double value) {#setBubbleWidth-double}
```
public final void setBubbleWidth(double value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setBubbles(System.Collections.Generic.List<OmrBubble> value) {#setBubbles-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrBubble}
```
public final void setBubbles(System.Collections.Generic.List<OmrBubble> value)
```


bubbles koleksiyonunu alır veya ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrBubble> | bubbles koleksiyonu |

### setHeight(double value) {#setHeight-double}
```
public final void setHeight(double value)
```


Soru yüksekliğini alır veya ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yükseklik |

### setLeft(double value) {#setLeft-double}
```
public final void setLeft(double value)
```


Soru sol konumunu alır veya ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Sol |

### setMultipleSelectionAllowed(boolean value) {#setMultipleSelectionAllowed-boolean}
```
public final void setMultipleSelectionAllowed(boolean value)
```


Çoklu seçim izin verilip verilmediğini gösteren değeri alır veya ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | çoklu seçimin izin verilip verilmediğini gösteren bir değer |

### setName(String value) {#setName-java.lang.String}
```
public final void setName(String value)
```


Soru adını ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Soru adı |

### setOrientation(int value) {#setOrientation-int}
```
public final void setOrientation(int value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setTop(double value) {#setTop-double}
```
public final void setTop(double value)
```


Soru üst konumunu alır veya ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Üst |

### setWidth(double value) {#setWidth-double}
```
public final void setWidth(double value)
```


Soru genişliğini alır veya ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Genişlik |

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

