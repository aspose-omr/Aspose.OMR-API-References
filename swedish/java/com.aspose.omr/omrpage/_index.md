---
title: "OmrPage"
second_title: "Aspose.OMR för Java API-referens"
description: "Representerar enskild omr-sida"
type: docs
weight: 24
url: /sv/java/com.aspose.omr/omrpage/
---

**Inheritance:**
java.lang.Object
```
public class OmrPage
```

Representerar enskild omr-sida
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [OmrPage()](#OmrPage) | Initierar en ny instans av klassen [OmrPage](../../com.aspose.omr/omrpage/) |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addBarcodeElement(BarcodeElement element)](#addBarcodeElement-com.aspose.omr.BarcodeElement) |  |
| [addChoiceBoxElement(String name, int width, int height, int top, int left)](#addChoiceBoxElement-java.lang.String-int-int-int-int) | Lägg till valrutaelement på sidan |
| [addClipAreaElement(String name, int width, int height, int top, int left)](#addClipAreaElement-java.lang.String-int-int-int-int) |  |
| [addGridElement(GridElement grid)](#addGridElement-com.aspose.omr.GridElement) |  |
| [addGridElement(String name, int width, int height, int top, int left)](#addGridElement-java.lang.String-int-int-int-int) |  |
| [addRefPointElement(ReferencePointElement item)](#addRefPointElement-com.aspose.omr.ReferencePointElement) |  |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [getElements()](#getElements) | Hämtar eller sätter lista över element på sidan |
| [getHeight()](#getHeight) | Hämtar eller anger sidans höjd |
| [getImageFormat()](#getImageFormat) | Hämtar eller anger bildfilens format |
| [getImageName()](#getImageName) | Hämtar eller anger bilddata |
| [getRotationPointPosition()](#getRotationPointPosition) | Hämtar eller anger RotationPointPosition |
| [getWidth()](#getWidth) | Hämtar eller anger sidans bredd |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [setElements(System.Collections.Generic.List<OmrElement> value)](#setElements-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement) | Hämtar eller sätter lista över element på sidan |
| [setHeight(double value)](#setHeight-double) | Hämtar eller anger sidans höjd |
| [setImageFormat(String value)](#setImageFormat-java.lang.String) | Hämtar eller anger bildfilens format |
| [setImageName(String value)](#setImageName-java.lang.String) | Hämtar eller anger bildens namn |
| [setRotationPointPosition(RotationPointPosition value)](#setRotationPointPosition-com.aspose.omr.RotationPointPosition) | Hämtar eller anger RotationPointPosition |
| [setWidth(double value)](#setWidth-double) | Hämtar eller anger sidans bredd |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### OmrPage() {#OmrPage}
```
public OmrPage()
```


Initierar en ny instans av klassen [OmrPage](../../com.aspose.omr/omrpage/)

### addBarcodeElement(BarcodeElement element) {#addBarcodeElement-com.aspose.omr.BarcodeElement}
```
public final void addBarcodeElement(BarcodeElement element)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [BarcodeElement](../../com.aspose.omr/barcodeelement/) |  |

### addChoiceBoxElement(String name, int width, int height, int top, int left) {#addChoiceBoxElement-java.lang.String-int-int-int-int}
```
public final ChoiceBoxElement addChoiceBoxElement(String name, int width, int height, int top, int left)
```


Lägg till valrutaelement på sidan

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String | Elementnamn |
| bredd | int | Elementbredd |
| höjd | int | Elementhöjd |
| övre | int | Elementets övre position |
| vänster | int | Elementets vänstra position |

**Returns:**
[ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) - Created choice box
### addClipAreaElement(String name, int width, int height, int top, int left) {#addClipAreaElement-java.lang.String-int-int-int-int}
```
public final ClipAreaElement addClipAreaElement(String name, int width, int height, int top, int left)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |
| bredd | int |  |
| höjd | int |  |
| övre | int |  |
| vänster | int |  |

**Returns:**
[ClipAreaElement](../../com.aspose.omr/clipareaelement/)
### addGridElement(GridElement grid) {#addGridElement-com.aspose.omr.GridElement}
```
public final void addGridElement(GridElement grid)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| grid | [GridElement](../../com.aspose.omr/gridelement/) |  |

### addGridElement(String name, int width, int height, int top, int left) {#addGridElement-java.lang.String-int-int-int-int}
```
public final GridElement addGridElement(String name, int width, int height, int top, int left)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |
| bredd | int |  |
| höjd | int |  |
| övre | int |  |
| vänster | int |  |

**Returns:**
[GridElement](../../com.aspose.omr/gridelement/)
### addRefPointElement(ReferencePointElement item) {#addRefPointElement-com.aspose.omr.ReferencePointElement}
```
public final void addRefPointElement(ReferencePointElement item)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [ReferencePointElement](../../com.aspose.omr/referencepointelement/) |  |

### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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


Hämtar eller sätter lista över element på sidan

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrElement> - lista över element på sidan
### getHeight() {#getHeight}
```
public final double getHeight()
```


Hämtar eller anger sidans höjd

**Returns:**
double - sidans höjd
### getImageFormat() {#getImageFormat}
```
public final String getImageFormat()
```


Hämtar eller anger bildfilens format

**Returns:**
java.lang.String - bildfilens format
### getImageName() {#getImageName}
```
public final String getImageName()
```


Hämtar eller anger bilddata

**Returns:**
java.lang.String - bildens namn
### getRotationPointPosition() {#getRotationPointPosition}
```
public final RotationPointPosition getRotationPointPosition()
```


Hämtar eller anger RotationPointPosition

**Returns:**
[RotationPointPosition](../../com.aspose.omr/rotationpointposition/) - RotationPointPosition
### getWidth() {#getWidth}
```
public final double getWidth()
```


Hämtar eller anger sidans bredd

**Returns:**
double - sidans bredd
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


Hämtar eller sätter lista över element på sidan

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrElement> | lista över element på sidan |

### setHeight(double value) {#setHeight-double}
```
public final void setHeight(double value)
```


Hämtar eller anger sidans höjd

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | sidans höjd |

### setImageFormat(String value) {#setImageFormat-java.lang.String}
```
public final void setImageFormat(String value)
```


Hämtar eller anger bildfilens format

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | bildfilens format |

### setImageName(String value) {#setImageName-java.lang.String}
```
public final void setImageName(String value)
```


Hämtar eller anger bildens namn

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | bildnamn |

### setRotationPointPosition(RotationPointPosition value) {#setRotationPointPosition-com.aspose.omr.RotationPointPosition}
```
public final void setRotationPointPosition(RotationPointPosition value)
```


Hämtar eller anger RotationPointPosition

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RotationPointPosition](../../com.aspose.omr/rotationpointposition/) | RotationPointPosition |

### setWidth(double value) {#setWidth-double}
```
public final void setWidth(double value)
```


Hämtar eller anger sidans bredd

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | sidbredd |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

