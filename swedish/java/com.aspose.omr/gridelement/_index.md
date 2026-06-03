---
title: "GridElement"
second_title: "Aspose.OMR för Java API-referens"
description: 
type: docs
weight: 16
url: /sv/java/com.aspose.omr/gridelement/
---

**Inheritance:**
java.lang.Object, [com.aspose.omr.OmrElement](../../com.aspose.omr/omrelement/)
```
public class GridElement extends OmrElement
```
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [GridElement()](#GridElement) |  |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [ElementType](#ElementType) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addChoiceBox(ChoiceBoxElement choiceBox)](#addChoiceBox-com.aspose.omr.ChoiceBoxElement) |  |
| [addChoiceBox(String name, int width, int height, int top, int left)](#addChoiceBox-java.lang.String-int-int-int-int) |  |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getChoiceBoxes()](#getChoiceBoxes) |  |
| [getClass()](#getClass) |  |
| [getHeight()](#getHeight) | Hämtar eller anger frågehöjd |
| [getLeft()](#getLeft) | Hämtar eller anger fråge vänsterposition |
| [getName()](#getName) | Hämtar frågenamn |
| [getOrientation()](#getOrientation) |  |
| [getOrientationString()](#getOrientationString) |  |
| [getRect()](#getRect) |  |
| [getTop()](#getTop) | Hämtar eller anger fråge topposition |
| [getWidth()](#getWidth) | Hämtar eller anger frågebredd |
| [hashCode()](#hashCode) |  |
| [isAlignedHorizontal()](#isAlignedHorizontal) | Hämtar eller anger ett värde som indikerar om bubblor är horisontellt placerade |
| [isAlignedVertical()](#isAlignedVertical) | Hämtar eller anger ett värde som indikerar om bubblor är vertikalt placerade |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [setAlignedHorizontal(boolean value)](#setAlignedHorizontal-boolean) | Hämtar eller anger ett värde som indikerar om bubblor är horisontellt placerade |
| [setAlignedVertical(boolean value)](#setAlignedVertical-boolean) | Hämtar eller anger ett värde som indikerar om bubblor är vertikalt placerade |
| [setChoiceBoxes(System.Collections.Generic.List<OmrElement> value)](#setChoiceBoxes-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement) |  |
| [setHeight(double value)](#setHeight-double) | Hämtar eller anger frågehöjd |
| [setLeft(double value)](#setLeft-double) | Hämtar eller anger fråge vänsterposition |
| [setName(String value)](#setName-java.lang.String) | Anger frågenamn |
| [setOrientation(int value)](#setOrientation-int) |  |
| [setTop(double value)](#setTop-double) | Hämtar eller anger fråge topposition |
| [setWidth(double value)](#setWidth-double) | Hämtar eller anger frågebredd |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| choiceBox | [ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) |  |

### addChoiceBox(String name, int width, int height, int top, int left) {#addChoiceBox-java.lang.String-int-int-int-int}
```
public final ChoiceBoxElement addChoiceBox(String name, int width, int height, int top, int left)
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
[ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/)
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


Hämtar eller anger frågehöjd

**Returns:**
double - Höjden
### getLeft() {#getLeft}
```
public final double getLeft()
```


Hämtar eller anger fråge vänsterposition

**Returns:**
double - Vänster
### getName() {#getName}
```
public final String getName()
```


Hämtar frågenamn

**Returns:**
java.lang.String - Frågenamnet
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


Hämtar eller anger fråge topposition

**Returns:**
double - Toppen
### getWidth() {#getWidth}
```
public final double getWidth()
```


Hämtar eller anger frågebredd

**Returns:**
double - Bredden
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


Hämtar eller anger ett värde som indikerar om bubblor är horisontellt placerade

**Returns:**
boolean - värde som indikerar om bubblor är horisontellt placerade
### isAlignedVertical() {#isAlignedVertical}
```
public final boolean isAlignedVertical()
```


Hämtar eller anger ett värde som indikerar om bubblor är vertikalt placerade

**Returns:**
boolean - ett värde som indikerar om bubblor är vertikalt placerade
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


Hämtar eller anger ett värde som indikerar om bubblor är horisontellt placerade

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | ett värde som indikerar om bubblor är horisontellt placerade |

### setAlignedVertical(boolean value) {#setAlignedVertical-boolean}
```
public final void setAlignedVertical(boolean value)
```


Hämtar eller anger ett värde som indikerar om bubblor är vertikalt placerade

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | ett värde som indikerar om bubblor är vertikalt placerade |

### setChoiceBoxes(System.Collections.Generic.List<OmrElement> value) {#setChoiceBoxes-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement}
```
public final void setChoiceBoxes(System.Collections.Generic.List<OmrElement> value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrElement> |  |

### setHeight(double value) {#setHeight-double}
```
public final void setHeight(double value)
```


Hämtar eller anger frågehöjd

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Höjden |

### setLeft(double value) {#setLeft-double}
```
public final void setLeft(double value)
```


Hämtar eller anger fråge vänsterposition

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Vänster |

### setName(String value) {#setName-java.lang.String}
```
public final void setName(String value)
```


Anger frågenamn

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Frågenamnet |

### setOrientation(int value) {#setOrientation-int}
```
public final void setOrientation(int value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setTop(double value) {#setTop-double}
```
public final void setTop(double value)
```


Hämtar eller anger fråge topposition

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Toppen |

### setWidth(double value) {#setWidth-double}
```
public final void setWidth(double value)
```


Hämtar eller anger frågebredd

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Bredden |

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

