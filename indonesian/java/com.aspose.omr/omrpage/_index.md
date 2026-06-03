---
title: "OmrPage"
second_title: "Referensi API Aspose.OMR for Java"
description: "Mewakili satu halaman omr"
type: docs
weight: 24
url: /id/java/com.aspose.omr/omrpage/
---

**Inheritance:**
java.lang.Object
```
public class OmrPage
```

Mewakili satu halaman omr
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [OmrPage()](#OmrPage) | Menginisialisasi sebuah instance baru dari kelas [OmrPage](../../com.aspose.omr/omrpage/) |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [addBarcodeElement(BarcodeElement element)](#addBarcodeElement-com.aspose.omr.BarcodeElement) |  |
| [addChoiceBoxElement(String name, int width, int height, int top, int left)](#addChoiceBoxElement-java.lang.String-int-int-int-int) | Tambahkan elemen kotak pilihan pada halaman |
| [addClipAreaElement(String name, int width, int height, int top, int left)](#addClipAreaElement-java.lang.String-int-int-int-int) |  |
| [addGridElement(GridElement grid)](#addGridElement-com.aspose.omr.GridElement) |  |
| [addGridElement(String name, int width, int height, int top, int left)](#addGridElement-java.lang.String-int-int-int-int) |  |
| [addRefPointElement(ReferencePointElement item)](#addRefPointElement-com.aspose.omr.ReferencePointElement) |  |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [getElements()](#getElements) | Mendapatkan atau mengatur daftar elemen pada halaman |
| [getHeight()](#getHeight) | Mendapatkan atau mengatur tinggi halaman |
| [getImageFormat()](#getImageFormat) | Mendapatkan atau mengatur format file gambar |
| [getImageName()](#getImageName) | Mendapatkan atau mengatur data gambar |
| [getRotationPointPosition()](#getRotationPointPosition) | Mendapatkan atau mengatur RotationPointPosition |
| [getWidth()](#getWidth) | Mendapatkan atau mengatur lebar halaman |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [setElements(System.Collections.Generic.List<OmrElement> value)](#setElements-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement) | Mendapatkan atau mengatur daftar elemen pada halaman |
| [setHeight(double value)](#setHeight-double) | Mendapatkan atau mengatur tinggi halaman |
| [setImageFormat(String value)](#setImageFormat-java.lang.String) | Mendapatkan atau mengatur format file gambar |
| [setImageName(String value)](#setImageName-java.lang.String) | Mendapatkan atau mengatur nama gambar |
| [setRotationPointPosition(RotationPointPosition value)](#setRotationPointPosition-com.aspose.omr.RotationPointPosition) | Mendapatkan atau mengatur RotationPointPosition |
| [setWidth(double value)](#setWidth-double) | Mendapatkan atau mengatur lebar halaman |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### OmrPage() {#OmrPage}
```
public OmrPage()
```


Menginisialisasi sebuah instance baru dari kelas [OmrPage](../../com.aspose.omr/omrpage/)

### addBarcodeElement(BarcodeElement element) {#addBarcodeElement-com.aspose.omr.BarcodeElement}
```
public final void addBarcodeElement(BarcodeElement element)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [BarcodeElement](../../com.aspose.omr/barcodeelement/) |  |

### addChoiceBoxElement(String name, int width, int height, int top, int left) {#addChoiceBoxElement-java.lang.String-int-int-int-int}
```
public final ChoiceBoxElement addChoiceBoxElement(String name, int width, int height, int top, int left)
```


Tambahkan elemen kotak pilihan pada halaman

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama elemen |
| lebar | int | Lebar elemen |
| tinggi | int | Tinggi elemen |
| atas | int | Posisi atas elemen |
| kiri | int | Posisi kiri elemen |

**Returns:**
[ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) - Created choice box
### addClipAreaElement(String name, int width, int height, int top, int left) {#addClipAreaElement-java.lang.String-int-int-int-int}
```
public final ClipAreaElement addClipAreaElement(String name, int width, int height, int top, int left)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String |  |
| lebar | int |  |
| tinggi | int |  |
| atas | int |  |
| kiri | int |  |

**Returns:**
[ClipAreaElement](../../com.aspose.omr/clipareaelement/)
### addGridElement(GridElement grid) {#addGridElement-com.aspose.omr.GridElement}
```
public final void addGridElement(GridElement grid)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| grid | [GridElement](../../com.aspose.omr/gridelement/) |  |

### addGridElement(String name, int width, int height, int top, int left) {#addGridElement-java.lang.String-int-int-int-int}
```
public final GridElement addGridElement(String name, int width, int height, int top, int left)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String |  |
| lebar | int |  |
| tinggi | int |  |
| atas | int |  |
| kiri | int |  |

**Returns:**
[GridElement](../../com.aspose.omr/gridelement/)
### addRefPointElement(ReferencePointElement item) {#addRefPointElement-com.aspose.omr.ReferencePointElement}
```
public final void addRefPointElement(ReferencePointElement item)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [ReferencePointElement](../../com.aspose.omr/referencepointelement/) |  |

### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
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


Mendapatkan atau mengatur daftar elemen pada halaman

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrElement> - daftar elemen pada halaman
### getHeight() {#getHeight}
```
public final double getHeight()
```


Mendapatkan atau mengatur tinggi halaman

**Returns:**
double - tinggi halaman
### getImageFormat() {#getImageFormat}
```
public final String getImageFormat()
```


Mendapatkan atau mengatur format file gambar

**Returns:**
java.lang.String - format file gambar
### getImageName() {#getImageName}
```
public final String getImageName()
```


Mendapatkan atau mengatur data gambar

**Returns:**
java.lang.String - nama gambar
### getRotationPointPosition() {#getRotationPointPosition}
```
public final RotationPointPosition getRotationPointPosition()
```


Mendapatkan atau mengatur RotationPointPosition

**Returns:**
[RotationPointPosition](../../com.aspose.omr/rotationpointposition/) - RotationPointPosition
### getWidth() {#getWidth}
```
public final double getWidth()
```


Mendapatkan atau mengatur lebar halaman

**Returns:**
double - lebar halaman
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


Mendapatkan atau mengatur daftar elemen pada halaman

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrElement> | daftar elemen pada halaman |

### setHeight(double value) {#setHeight-double}
```
public final void setHeight(double value)
```


Mendapatkan atau mengatur tinggi halaman

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | tinggi halaman |

### setImageFormat(String value) {#setImageFormat-java.lang.String}
```
public final void setImageFormat(String value)
```


Mendapatkan atau mengatur format file gambar

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | format file gambar |

### setImageName(String value) {#setImageName-java.lang.String}
```
public final void setImageName(String value)
```


Mendapatkan atau mengatur nama gambar

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | nama gambar |

### setRotationPointPosition(RotationPointPosition value) {#setRotationPointPosition-com.aspose.omr.RotationPointPosition}
```
public final void setRotationPointPosition(RotationPointPosition value)
```


Mendapatkan atau mengatur RotationPointPosition

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [RotationPointPosition](../../com.aspose.omr/rotationpointposition/) | RotationPointPosition |

### setWidth(double value) {#setWidth-double}
```
public final void setWidth(double value)
```


Mendapatkan atau mengatur lebar halaman

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | lebar halaman |

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

