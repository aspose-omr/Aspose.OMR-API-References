---
title: "ChoiceBoxElement"
second_title: "Aspose.OMR for Java API-referentie"
description: "Vertegenwoordigt ChoiceBox‑vraag"
type: docs
weight: 11
url: /nl/java/com.aspose.omr/choiceboxelement/
---

**Inheritance:**
java.lang.Object, [com.aspose.omr.OmrElement](../../com.aspose.omr/omrelement/)
```
public class ChoiceBoxElement extends OmrElement
```

Vertegenwoordigt ChoiceBox‑vraag
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ChoiceBoxElement()](#ChoiceBoxElement) | Initialiseert een nieuw exemplaar van de [ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) klasse |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [ElementType](#ElementType) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addBubble(String name, int width, int height, int top, int left, boolean isValid)](#addBubble-java.lang.String-int-int-int-int-boolean) | Voegt een bubbel toe binnen de vraag |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getBubbleHeight()](#getBubbleHeight) |  |
| [getBubbleWidth()](#getBubbleWidth) |  |
| [getBubbles()](#getBubbles) | Haalt op of stelt de bubbelscollectie in |
| [getClass()](#getClass) |  |
| [getHeight()](#getHeight) | Haalt op of stelt de vraaghoogte in |
| [getLeft()](#getLeft) | Haalt op of stelt de linkse positie van de vraag in |
| [getMultipleSelectionAllowed()](#getMultipleSelectionAllowed) | Haalt op of stelt een waarde in die aangeeft of meerdere selecties zijn toegestaan |
| [getName()](#getName) | Haalt de vraagnaam op |
| [getOrientation()](#getOrientation) |  |
| [getOrientationString()](#getOrientationString) | Haalt de stringrepresentatie van de oriëntatie‑eigenschap op |
| [getRect()](#getRect) |  |
| [getTop()](#getTop) | Haalt op of stelt de bovenste positie van de vraag in |
| [getWidth()](#getWidth) | Haalt op of stelt de vraagbreedte in |
| [hashCode()](#hashCode) |  |
| [isAlignedHorizontal()](#isAlignedHorizontal) | Haalt of stelt een waarde in die aangeeft of bubbels horizontaal zijn uitgelijnd |
| [isAlignedVertical()](#isAlignedVertical) | Haalt of stelt een waarde in die aangeeft of bubbels verticaal zijn uitgelijnd |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [setAlignedHorizontal(boolean value)](#setAlignedHorizontal-boolean) | Haalt of stelt een waarde in die aangeeft of bubbels horizontaal zijn uitgelijnd |
| [setAlignedVertical(boolean value)](#setAlignedVertical-boolean) | Haalt of stelt een waarde in die aangeeft of bubbels verticaal zijn uitgelijnd |
| [setBubbleHeight(double value)](#setBubbleHeight-double) |  |
| [setBubbleWidth(double value)](#setBubbleWidth-double) |  |
| [setBubbles(System.Collections.Generic.List<OmrBubble> value)](#setBubbles-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrBubble) | Haalt op of stelt de bubbelscollectie in |
| [setHeight(double value)](#setHeight-double) | Haalt op of stelt de vraaghoogte in |
| [setLeft(double value)](#setLeft-double) | Haalt op of stelt de linkse positie van de vraag in |
| [setMultipleSelectionAllowed(boolean value)](#setMultipleSelectionAllowed-boolean) | Haalt op of stelt een waarde in die aangeeft of meerdere selecties zijn toegestaan |
| [setName(String value)](#setName-java.lang.String) | Stelt de vraagnaam in |
| [setOrientation(int value)](#setOrientation-int) |  |
| [setTop(double value)](#setTop-double) | Haalt op of stelt de bovenste positie van de vraag in |
| [setWidth(double value)](#setWidth-double) | Haalt op of stelt de vraagbreedte in |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### ChoiceBoxElement() {#ChoiceBoxElement}
```
public ChoiceBoxElement()
```


Initialiseert een nieuw exemplaar van de [ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) klasse

### ElementType {#ElementType}
```
public String ElementType
```


### addBubble(String name, int width, int height, int top, int left, boolean isValid) {#addBubble-java.lang.String-int-int-int-int-boolean}
```
public final void addBubble(String name, int width, int height, int top, int left, boolean isValid)
```


Voegt een bubbel toe binnen de vraag

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | Bubbelnaam |
| breedte | int | Bubbelbreedte |
| hoogte | int | Bubbelhoogte |
| boven | int | Bubbel bovenste positie |
| links | int | Bubbel linkerpositie |
| isValid | boolean | Bubbel geldigheidsvlag |

### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Haalt op of stelt de bubbelscollectie in

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrBubble> - bubbelscollectie
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


Haalt op of stelt de vraaghoogte in

**Returns:**
double - De hoogte
### getLeft() {#getLeft}
```
public final double getLeft()
```


Haalt op of stelt de linkse positie van de vraag in

**Returns:**
double - De linkerkant
### getMultipleSelectionAllowed() {#getMultipleSelectionAllowed}
```
public final boolean getMultipleSelectionAllowed()
```


Haalt op of stelt een waarde in die aangeeft of meerdere selecties zijn toegestaan

**Returns:**
boolean - waarde die aangeeft of meerdere selecties zijn toegestaan
### getName() {#getName}
```
public final String getName()
```


Haalt de vraagnaam op

**Returns:**
java.lang.String - De vraagnaam
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


Haalt de stringrepresentatie van de oriëntatie‑eigenschap op

**Returns:**
java.lang.String - stringrepresentatie van de oriëntatie‑eigenschap
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


Haalt op of stelt de bovenste positie van de vraag in

**Returns:**
double - De bovenkant
### getWidth() {#getWidth}
```
public final double getWidth()
```


Haalt op of stelt de vraagbreedte in

**Returns:**
double - De breedte
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


Haalt of stelt een waarde in die aangeeft of bubbels horizontaal zijn uitgelijnd

**Returns:**
boolean - waarde die aangeeft of bubbels horizontaal zijn uitgelijnd
### isAlignedVertical() {#isAlignedVertical}
```
public final boolean isAlignedVertical()
```


Haalt of stelt een waarde in die aangeeft of bubbels verticaal zijn uitgelijnd

**Returns:**
boolean - een waarde die aangeeft of bubbels verticaal zijn uitgelijnd
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


Haalt of stelt een waarde in die aangeeft of bubbels horizontaal zijn uitgelijnd

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | een waarde die aangeeft of bubbels horizontaal zijn uitgelijnd |

### setAlignedVertical(boolean value) {#setAlignedVertical-boolean}
```
public final void setAlignedVertical(boolean value)
```


Haalt of stelt een waarde in die aangeeft of bubbels verticaal zijn uitgelijnd

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | een waarde die aangeeft of bubbels verticaal zijn uitgelijnd |

### setBubbleHeight(double value) {#setBubbleHeight-double}
```
public final void setBubbleHeight(double value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setBubbleWidth(double value) {#setBubbleWidth-double}
```
public final void setBubbleWidth(double value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setBubbles(System.Collections.Generic.List<OmrBubble> value) {#setBubbles-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrBubble}
```
public final void setBubbles(System.Collections.Generic.List<OmrBubble> value)
```


Haalt op of stelt de bubbelscollectie in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrBubble> | bubbelscollectie |

### setHeight(double value) {#setHeight-double}
```
public final void setHeight(double value)
```


Haalt op of stelt de vraaghoogte in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | De hoogte |

### setLeft(double value) {#setLeft-double}
```
public final void setLeft(double value)
```


Haalt op of stelt de linkse positie van de vraag in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | De linkerkant |

### setMultipleSelectionAllowed(boolean value) {#setMultipleSelectionAllowed-boolean}
```
public final void setMultipleSelectionAllowed(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of meerdere selecties zijn toegestaan

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | een waarde die aangeeft of meerdere selecties zijn toegestaan |

### setName(String value) {#setName-java.lang.String}
```
public final void setName(String value)
```


Stelt de vraagnaam in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | De vraagnaam |

### setOrientation(int value) {#setOrientation-int}
```
public final void setOrientation(int value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setTop(double value) {#setTop-double}
```
public final void setTop(double value)
```


Haalt op of stelt de bovenste positie van de vraag in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | De bovenkant |

### setWidth(double value) {#setWidth-double}
```
public final void setWidth(double value)
```


Haalt op of stelt de vraagbreedte in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | De breedte |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

