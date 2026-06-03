---
title: "ChoiceBoxElement"
second_title: "Aspose.OMR för Java API-referens"
description: "Representerar ChoiceBox-fråga"
type: docs
weight: 11
url: /sv/java/com.aspose.omr/choiceboxelement/
---

**Inheritance:**
java.lang.Object, [com.aspose.omr.OmrElement](../../com.aspose.omr/omrelement/)
```
public class ChoiceBoxElement extends OmrElement
```

Representerar ChoiceBox-fråga
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ChoiceBoxElement()](#ChoiceBoxElement) | Initierar en ny instans av klassen [ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [ElementType](#ElementType) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addBubble(String name, int width, int height, int top, int left, boolean isValid)](#addBubble-java.lang.String-int-int-int-int-boolean) | Lägger till en bubbla i frågan |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getBubbleHeight()](#getBubbleHeight) |  |
| [getBubbleWidth()](#getBubbleWidth) |  |
| [getBubbles()](#getBubbles) | Hämtar eller anger samling av bubblor |
| [getClass()](#getClass) |  |
| [getHeight()](#getHeight) | Hämtar eller anger frågehöjd |
| [getLeft()](#getLeft) | Hämtar eller anger fråge vänsterposition |
| [getMultipleSelectionAllowed()](#getMultipleSelectionAllowed) | Hämtar eller anger ett värde som indikerar om flervalsval är tillåtet |
| [getName()](#getName) | Hämtar frågenamn |
| [getOrientation()](#getOrientation) |  |
| [getOrientationString()](#getOrientationString) | Hämtar strängrepresentation av orienteringsegenskapen |
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
| [setBubbleHeight(double value)](#setBubbleHeight-double) |  |
| [setBubbleWidth(double value)](#setBubbleWidth-double) |  |
| [setBubbles(System.Collections.Generic.List<OmrBubble> value)](#setBubbles-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrBubble) | Hämtar eller anger samling av bubblor |
| [setHeight(double value)](#setHeight-double) | Hämtar eller anger frågehöjd |
| [setLeft(double value)](#setLeft-double) | Hämtar eller anger fråge vänsterposition |
| [setMultipleSelectionAllowed(boolean value)](#setMultipleSelectionAllowed-boolean) | Hämtar eller anger ett värde som indikerar om flervalsval är tillåtet |
| [setName(String value)](#setName-java.lang.String) | Anger frågenamn |
| [setOrientation(int value)](#setOrientation-int) |  |
| [setTop(double value)](#setTop-double) | Hämtar eller anger fråge topposition |
| [setWidth(double value)](#setWidth-double) | Hämtar eller anger frågebredd |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### ChoiceBoxElement() {#ChoiceBoxElement}
```
public ChoiceBoxElement()
```


Initierar en ny instans av klassen [ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/)

### ElementType {#ElementType}
```
public String ElementType
```


### addBubble(String name, int width, int height, int top, int left, boolean isValid) {#addBubble-java.lang.String-int-int-int-int-boolean}
```
public final void addBubble(String name, int width, int height, int top, int left, boolean isValid)
```


Lägger till en bubbla i frågan

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String | Bubblans namn |
| bredd | int | Bubblans bredd |
| höjd | int | Bubblans höjd |
| övre | int | Bubblans topposition |
| vänster | int | Bubblans vänsterposition |
| isValid | boolean | Giltighetsflagga för bubbla |

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


Hämtar eller anger samling av bubblor

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrBubble> - bubbelsamling
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
### getMultipleSelectionAllowed() {#getMultipleSelectionAllowed}
```
public final boolean getMultipleSelectionAllowed()
```


Hämtar eller anger ett värde som indikerar om flervalsval är tillåtet

**Returns:**
boolean - värde som indikerar om flervalsval är tillåtet
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


Hämtar strängrepresentation av orienteringsegenskapen

**Returns:**
java.lang.String - strängrepresentation av orienteringsegenskapen
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

### setBubbleHeight(double value) {#setBubbleHeight-double}
```
public final void setBubbleHeight(double value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setBubbleWidth(double value) {#setBubbleWidth-double}
```
public final void setBubbleWidth(double value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setBubbles(System.Collections.Generic.List<OmrBubble> value) {#setBubbles-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrBubble}
```
public final void setBubbles(System.Collections.Generic.List<OmrBubble> value)
```


Hämtar eller anger samling av bubblor

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrBubble> | bubbelsamling |

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

### setMultipleSelectionAllowed(boolean value) {#setMultipleSelectionAllowed-boolean}
```
public final void setMultipleSelectionAllowed(boolean value)
```


Hämtar eller anger ett värde som indikerar om flervalsval är tillåtet

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | ett värde som indikerar om flervalsval är tillåtet |

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

