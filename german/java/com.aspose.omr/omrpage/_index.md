---
title: "OmrPage"
second_title: "Aspose.OMR für Java API-Referenz"
description: "Stellt einzelne OMR‑Seite dar"
type: docs
weight: 24
url: /de/java/com.aspose.omr/omrpage/
---

**Inheritance:**
java.lang.Object
```
public class OmrPage
```

Stellt einzelne OMR‑Seite dar
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [OmrPage()](#OmrPage) | Initialisiert eine neue Instanz der Klasse [OmrPage](../../com.aspose.omr/omrpage/) |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addBarcodeElement(BarcodeElement element)](#addBarcodeElement-com.aspose.omr.BarcodeElement) |  |
| [addChoiceBoxElement(String name, int width, int height, int top, int left)](#addChoiceBoxElement-java.lang.String-int-int-int-int) | Fügt ein Auswahlfeld-Element zur Seite hinzu |
| [addClipAreaElement(String name, int width, int height, int top, int left)](#addClipAreaElement-java.lang.String-int-int-int-int) |  |
| [addGridElement(GridElement grid)](#addGridElement-com.aspose.omr.GridElement) |  |
| [addGridElement(String name, int width, int height, int top, int left)](#addGridElement-java.lang.String-int-int-int-int) |  |
| [addRefPointElement(ReferencePointElement item)](#addRefPointElement-com.aspose.omr.ReferencePointElement) |  |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [getElements()](#getElements) | Liest oder setzt die Liste der Elemente auf der Seite |
| [getHeight()](#getHeight) | Liest oder legt die Seitenhöhe fest |
| [getImageFormat()](#getImageFormat) | Liest oder legt das Bilddateiformat fest |
| [getImageName()](#getImageName) | Liest oder legt die Bilddaten fest |
| [getRotationPointPosition()](#getRotationPointPosition) | Liest oder legt die RotationPointPosition fest |
| [getWidth()](#getWidth) | Liest oder legt die Seitenbreite fest |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [setElements(System.Collections.Generic.List<OmrElement> value)](#setElements-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement) | Liest oder setzt die Liste der Elemente auf der Seite |
| [setHeight(double value)](#setHeight-double) | Liest oder legt die Seitenhöhe fest |
| [setImageFormat(String value)](#setImageFormat-java.lang.String) | Liest oder legt das Bilddateiformat fest |
| [setImageName(String value)](#setImageName-java.lang.String) | Liest oder legt den Bildnamen fest |
| [setRotationPointPosition(RotationPointPosition value)](#setRotationPointPosition-com.aspose.omr.RotationPointPosition) | Liest oder legt die RotationPointPosition fest |
| [setWidth(double value)](#setWidth-double) | Liest oder legt die Seitenbreite fest |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### OmrPage() {#OmrPage}
```
public OmrPage()
```


Initialisiert eine neue Instanz der Klasse [OmrPage](../../com.aspose.omr/omrpage/)

### addBarcodeElement(BarcodeElement element) {#addBarcodeElement-com.aspose.omr.BarcodeElement}
```
public final void addBarcodeElement(BarcodeElement element)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [BarcodeElement](../../com.aspose.omr/barcodeelement/) |  |

### addChoiceBoxElement(String name, int width, int height, int top, int left) {#addChoiceBoxElement-java.lang.String-int-int-int-int}
```
public final ChoiceBoxElement addChoiceBoxElement(String name, int width, int height, int top, int left)
```


Fügt ein Auswahlfeld-Element zur Seite hinzu

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String | Elementname |
| Breite | int | Elementbreite |
| Höhe | int | Elementhöhe |
| Oben | int | Obere Position des Elements |
| Links | int | Linke Position des Elements |

**Returns:**
[ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) - Created choice box
### addClipAreaElement(String name, int width, int height, int top, int left) {#addClipAreaElement-java.lang.String-int-int-int-int}
```
public final ClipAreaElement addClipAreaElement(String name, int width, int height, int top, int left)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String |  |
| Breite | int |  |
| Höhe | int |  |
| Oben | int |  |
| Links | int |  |

**Returns:**
[ClipAreaElement](../../com.aspose.omr/clipareaelement/)
### addGridElement(GridElement grid) {#addGridElement-com.aspose.omr.GridElement}
```
public final void addGridElement(GridElement grid)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| grid | [GridElement](../../com.aspose.omr/gridelement/) |  |

### addGridElement(String name, int width, int height, int top, int left) {#addGridElement-java.lang.String-int-int-int-int}
```
public final GridElement addGridElement(String name, int width, int height, int top, int left)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String |  |
| Breite | int |  |
| Höhe | int |  |
| Oben | int |  |
| Links | int |  |

**Returns:**
[GridElement](../../com.aspose.omr/gridelement/)
### addRefPointElement(ReferencePointElement item) {#addRefPointElement-com.aspose.omr.ReferencePointElement}
```
public final void addRefPointElement(ReferencePointElement item)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [ReferencePointElement](../../com.aspose.omr/referencepointelement/) |  |

### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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


Liest oder setzt die Liste der Elemente auf der Seite

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrElement> - Liste von Elementen auf der Seite
### getHeight() {#getHeight}
```
public final double getHeight()
```


Liest oder legt die Seitenhöhe fest

**Returns:**
double - Seitenhöhe
### getImageFormat() {#getImageFormat}
```
public final String getImageFormat()
```


Liest oder legt das Bilddateiformat fest

**Returns:**
java.lang.String - das Bilddateiformat
### getImageName() {#getImageName}
```
public final String getImageName()
```


Liest oder legt die Bilddaten fest

**Returns:**
java.lang.String - der Bildname
### getRotationPointPosition() {#getRotationPointPosition}
```
public final RotationPointPosition getRotationPointPosition()
```


Liest oder legt die RotationPointPosition fest

**Returns:**
[RotationPointPosition](../../com.aspose.omr/rotationpointposition/) - RotationPointPosition
### getWidth() {#getWidth}
```
public final double getWidth()
```


Liest oder legt die Seitenbreite fest

**Returns:**
double - Seitenbreite
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


Liest oder setzt die Liste der Elemente auf der Seite

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrElement> | Liste von Elementen auf der Seite |

### setHeight(double value) {#setHeight-double}
```
public final void setHeight(double value)
```


Liest oder legt die Seitenhöhe fest

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double | Seitenhöhe |

### setImageFormat(String value) {#setImageFormat-java.lang.String}
```
public final void setImageFormat(String value)
```


Liest oder legt das Bilddateiformat fest

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | das Bilddateiformat |

### setImageName(String value) {#setImageName-java.lang.String}
```
public final void setImageName(String value)
```


Liest oder legt den Bildnamen fest

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Bildname |

### setRotationPointPosition(RotationPointPosition value) {#setRotationPointPosition-com.aspose.omr.RotationPointPosition}
```
public final void setRotationPointPosition(RotationPointPosition value)
```


Liest oder legt die RotationPointPosition fest

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RotationPointPosition](../../com.aspose.omr/rotationpointposition/) | RotationPointPosition |

### setWidth(double value) {#setWidth-double}
```
public final void setWidth(double value)
```


Liest oder legt die Seitenbreite fest

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double | Seitenbreite |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

