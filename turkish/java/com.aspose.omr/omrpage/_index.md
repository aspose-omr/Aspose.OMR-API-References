---
title: "OmrPage"
second_title: "Aspose.OMR for Java API Referansı"
description: "Tek bir omr sayfasını temsil eder"
type: docs
weight: 24
url: /tr/java/com.aspose.omr/omrpage/
---

**Inheritance:**
java.lang.Object
```
public class OmrPage
```

Tek bir omr sayfasını temsil eder
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [OmrPage()](#OmrPage) | Yeni bir [OmrPage](../../com.aspose.omr/omrpage/) sınıfı örneği başlatır |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [addBarcodeElement(BarcodeElement element)](#addBarcodeElement-com.aspose.omr.BarcodeElement) |  |
| [addChoiceBoxElement(String name, int width, int height, int top, int left)](#addChoiceBoxElement-java.lang.String-int-int-int-int) | Sayfaya seçim kutusu öğesi ekle |
| [addClipAreaElement(String name, int width, int height, int top, int left)](#addClipAreaElement-java.lang.String-int-int-int-int) |  |
| [addGridElement(GridElement grid)](#addGridElement-com.aspose.omr.GridElement) |  |
| [addGridElement(String name, int width, int height, int top, int left)](#addGridElement-java.lang.String-int-int-int-int) |  |
| [addRefPointElement(ReferencePointElement item)](#addRefPointElement-com.aspose.omr.ReferencePointElement) |  |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [getElements()](#getElements) | Sayfadaki öğeler listesini alır veya ayarlar |
| [getHeight()](#getHeight) | Sayfa yüksekliğini alır veya ayarlar |
| [getImageFormat()](#getImageFormat) | Görüntü dosya biçimini alır veya ayarlar |
| [getImageName()](#getImageName) | Görüntü verisini alır veya ayarlar |
| [getRotationPointPosition()](#getRotationPointPosition) | RotationPointPosition değerini alır veya ayarlar |
| [getWidth()](#getWidth) | Sayfa genişliğini alır veya ayarlar |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [setElements(System.Collections.Generic.List<OmrElement> value)](#setElements-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement) | Sayfadaki öğeler listesini alır veya ayarlar |
| [setHeight(double value)](#setHeight-double) | Sayfa yüksekliğini alır veya ayarlar |
| [setImageFormat(String value)](#setImageFormat-java.lang.String) | Görüntü dosya biçimini alır veya ayarlar |
| [setImageName(String value)](#setImageName-java.lang.String) | Görüntü adını alır veya ayarlar |
| [setRotationPointPosition(RotationPointPosition value)](#setRotationPointPosition-com.aspose.omr.RotationPointPosition) | RotationPointPosition değerini alır veya ayarlar |
| [setWidth(double value)](#setWidth-double) | Sayfa genişliğini alır veya ayarlar |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### OmrPage() {#OmrPage}
```
public OmrPage()
```


Yeni bir [OmrPage](../../com.aspose.omr/omrpage/) sınıfı örneği başlatır

### addBarcodeElement(BarcodeElement element) {#addBarcodeElement-com.aspose.omr.BarcodeElement}
```
public final void addBarcodeElement(BarcodeElement element)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [BarcodeElement](../../com.aspose.omr/barcodeelement/) |  |

### addChoiceBoxElement(String name, int width, int height, int top, int left) {#addChoiceBoxElement-java.lang.String-int-int-int-int}
```
public final ChoiceBoxElement addChoiceBoxElement(String name, int width, int height, int top, int left)
```


Sayfaya seçim kutusu öğesi ekle

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Eleman adı |
| genişlik | int | Eleman genişliği |
| yükseklik | int | Eleman yüksekliği |
| üst | int | Eleman üst konumu |
| sol | int | Eleman sol konumu |

**Returns:**
[ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) - Created choice box
### addClipAreaElement(String name, int width, int height, int top, int left) {#addClipAreaElement-java.lang.String-int-int-int-int}
```
public final ClipAreaElement addClipAreaElement(String name, int width, int height, int top, int left)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String |  |
| genişlik | int |  |
| yükseklik | int |  |
| üst | int |  |
| sol | int |  |

**Returns:**
[ClipAreaElement](../../com.aspose.omr/clipareaelement/)
### addGridElement(GridElement grid) {#addGridElement-com.aspose.omr.GridElement}
```
public final void addGridElement(GridElement grid)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| grid | [GridElement](../../com.aspose.omr/gridelement/) |  |

### addGridElement(String name, int width, int height, int top, int left) {#addGridElement-java.lang.String-int-int-int-int}
```
public final GridElement addGridElement(String name, int width, int height, int top, int left)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String |  |
| genişlik | int |  |
| yükseklik | int |  |
| üst | int |  |
| sol | int |  |

**Returns:**
[GridElement](../../com.aspose.omr/gridelement/)
### addRefPointElement(ReferencePointElement item) {#addRefPointElement-com.aspose.omr.ReferencePointElement}
```
public final void addRefPointElement(ReferencePointElement item)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [ReferencePointElement](../../com.aspose.omr/referencepointelement/) |  |

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


Sayfadaki öğeler listesini alır veya ayarlar

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrElement> - sayfadaki elemanların listesi
### getHeight() {#getHeight}
```
public final double getHeight()
```


Sayfa yüksekliğini alır veya ayarlar

**Returns:**
double - sayfa yüksekliği
### getImageFormat() {#getImageFormat}
```
public final String getImageFormat()
```


Görüntü dosya biçimini alır veya ayarlar

**Returns:**
java.lang.String - görüntü dosya biçimi
### getImageName() {#getImageName}
```
public final String getImageName()
```


Görüntü verisini alır veya ayarlar

**Returns:**
java.lang.String - görüntü adı
### getRotationPointPosition() {#getRotationPointPosition}
```
public final RotationPointPosition getRotationPointPosition()
```


RotationPointPosition değerini alır veya ayarlar

**Returns:**
[RotationPointPosition](../../com.aspose.omr/rotationpointposition/) - RotationPointPosition
### getWidth() {#getWidth}
```
public final double getWidth()
```


Sayfa genişliğini alır veya ayarlar

**Returns:**
double - sayfa genişliği
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


Sayfadaki öğeler listesini alır veya ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrElement> | sayfadaki elemanların listesi |

### setHeight(double value) {#setHeight-double}
```
public final void setHeight(double value)
```


Sayfa yüksekliğini alır veya ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | sayfa yüksekliği |

### setImageFormat(String value) {#setImageFormat-java.lang.String}
```
public final void setImageFormat(String value)
```


Görüntü dosya biçimini alır veya ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | görüntü dosya biçimi |

### setImageName(String value) {#setImageName-java.lang.String}
```
public final void setImageName(String value)
```


Görüntü adını alır veya ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | görsel adı |

### setRotationPointPosition(RotationPointPosition value) {#setRotationPointPosition-com.aspose.omr.RotationPointPosition}
```
public final void setRotationPointPosition(RotationPointPosition value)
```


RotationPointPosition değerini alır veya ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RotationPointPosition](../../com.aspose.omr/rotationpointposition/) | RotationPointPosition |

### setWidth(double value) {#setWidth-double}
```
public final void setWidth(double value)
```


Sayfa genişliğini alır veya ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | sayfa genişliği |

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

