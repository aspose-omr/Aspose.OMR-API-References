---
title: "GridElement"
second_title: "Referensi API Aspose.OMR for Java"
description: 
type: docs
weight: 16
url: /id/java/com.aspose.omr/gridelement/
---

**Inheritance:**
java.lang.Object, [com.aspose.omr.OmrElement](../../com.aspose.omr/omrelement/)
```
public class GridElement extends OmrElement
```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [GridElement()](#GridElement) |  |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [ElementType](#ElementType) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [addChoiceBox(ChoiceBoxElement choiceBox)](#addChoiceBox-com.aspose.omr.ChoiceBoxElement) |  |
| [addChoiceBox(String name, int width, int height, int top, int left)](#addChoiceBox-java.lang.String-int-int-int-int) |  |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getChoiceBoxes()](#getChoiceBoxes) |  |
| [getClass()](#getClass) |  |
| [getHeight()](#getHeight) | Mendapatkan atau mengatur tinggi pertanyaan |
| [getLeft()](#getLeft) | Mendapatkan atau mengatur posisi kiri pertanyaan |
| [getName()](#getName) | Mendapatkan nama pertanyaan |
| [getOrientation()](#getOrientation) |  |
| [getOrientationString()](#getOrientationString) |  |
| [getRect()](#getRect) |  |
| [getTop()](#getTop) | Mendapatkan atau mengatur posisi atas pertanyaan |
| [getWidth()](#getWidth) | Mendapatkan atau mengatur lebar pertanyaan |
| [hashCode()](#hashCode) |  |
| [isAlignedHorizontal()](#isAlignedHorizontal) | Mendapatkan atau mengatur nilai yang menunjukkan apakah gelembung disusun secara horizontal |
| [isAlignedVertical()](#isAlignedVertical) | Mendapatkan atau mengatur nilai yang menunjukkan apakah gelembung disusun secara vertikal |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [setAlignedHorizontal(boolean value)](#setAlignedHorizontal-boolean) | Mendapatkan atau mengatur nilai yang menunjukkan apakah gelembung disusun secara horizontal |
| [setAlignedVertical(boolean value)](#setAlignedVertical-boolean) | Mendapatkan atau mengatur nilai yang menunjukkan apakah gelembung disusun secara vertikal |
| [setChoiceBoxes(System.Collections.Generic.List<OmrElement> value)](#setChoiceBoxes-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement) |  |
| [setHeight(double value)](#setHeight-double) | Mendapatkan atau mengatur tinggi pertanyaan |
| [setLeft(double value)](#setLeft-double) | Mendapatkan atau mengatur posisi kiri pertanyaan |
| [setName(String value)](#setName-java.lang.String) | Mengatur nama pertanyaan |
| [setOrientation(int value)](#setOrientation-int) |  |
| [setTop(double value)](#setTop-double) | Mendapatkan atau mengatur posisi atas pertanyaan |
| [setWidth(double value)](#setWidth-double) | Mendapatkan atau mengatur lebar pertanyaan |
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| choiceBox | [ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) |  |

### addChoiceBox(String name, int width, int height, int top, int left) {#addChoiceBox-java.lang.String-int-int-int-int}
```
public final ChoiceBoxElement addChoiceBox(String name, int width, int height, int top, int left)
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
[ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/)
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


Mendapatkan atau mengatur tinggi pertanyaan

**Returns:**
double - Tinggi
### getLeft() {#getLeft}
```
public final double getLeft()
```


Mendapatkan atau mengatur posisi kiri pertanyaan

**Returns:**
double - Kiri
### getName() {#getName}
```
public final String getName()
```


Mendapatkan nama pertanyaan

**Returns:**
java.lang.String - Nama pertanyaan
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


Mendapatkan atau mengatur posisi atas pertanyaan

**Returns:**
double - Atas
### getWidth() {#getWidth}
```
public final double getWidth()
```


Mendapatkan atau mengatur lebar pertanyaan

**Returns:**
double - Lebar
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


Mendapatkan atau mengatur nilai yang menunjukkan apakah gelembung disusun secara horizontal

**Returns:**
boolean - nilai yang menunjukkan apakah gelembung disusun secara horizontal
### isAlignedVertical() {#isAlignedVertical}
```
public final boolean isAlignedVertical()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah gelembung disusun secara vertikal

**Returns:**
boolean - nilai yang menunjukkan apakah gelembung disusun secara vertikal
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


Mendapatkan atau mengatur nilai yang menunjukkan apakah gelembung disusun secara horizontal

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | nilai yang menunjukkan apakah gelembung disusun secara horizontal |

### setAlignedVertical(boolean value) {#setAlignedVertical-boolean}
```
public final void setAlignedVertical(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah gelembung disusun secara vertikal

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | nilai yang menunjukkan apakah gelembung disusun secara vertikal |

### setChoiceBoxes(System.Collections.Generic.List<OmrElement> value) {#setChoiceBoxes-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement}
```
public final void setChoiceBoxes(System.Collections.Generic.List<OmrElement> value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrElement> |  |

### setHeight(double value) {#setHeight-double}
```
public final void setHeight(double value)
```


Mendapatkan atau mengatur tinggi pertanyaan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Tinggi |

### setLeft(double value) {#setLeft-double}
```
public final void setLeft(double value)
```


Mendapatkan atau mengatur posisi kiri pertanyaan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Kiri |

### setName(String value) {#setName-java.lang.String}
```
public final void setName(String value)
```


Mengatur nama pertanyaan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nama pertanyaan |

### setOrientation(int value) {#setOrientation-int}
```
public final void setOrientation(int value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setTop(double value) {#setTop-double}
```
public final void setTop(double value)
```


Mendapatkan atau mengatur posisi atas pertanyaan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Atas |

### setWidth(double value) {#setWidth-double}
```
public final void setWidth(double value)
```


Mendapatkan atau mengatur lebar pertanyaan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Lebar |

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

