---
title: "ChoiceBoxElement"
second_title: "Aspose.OMR für Java API-Referenz"
description: "Stellt ChoiceBox‑Frage dar"
type: docs
weight: 11
url: /de/java/com.aspose.omr/choiceboxelement/
---

**Inheritance:**
java.lang.Object, [com.aspose.omr.OmrElement](../../com.aspose.omr/omrelement/)
```
public class ChoiceBoxElement extends OmrElement
```

Stellt ChoiceBox‑Frage dar
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ChoiceBoxElement()](#ChoiceBoxElement) | Initialisiert eine neue Instanz der [ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) Klasse |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [ElementType](#ElementType) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addBubble(String name, int width, int height, int top, int left, boolean isValid)](#addBubble-java.lang.String-int-int-int-int-boolean) | Fügt eine Blase innerhalb der Frage hinzu |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getBubbleHeight()](#getBubbleHeight) |  |
| [getBubbleWidth()](#getBubbleWidth) |  |
| [getBubbles()](#getBubbles) | Liest oder setzt die Blasen‑Sammlung |
| [getClass()](#getClass) |  |
| [getHeight()](#getHeight) | Liest oder setzt die Höhe der Frage |
| [getLeft()](#getLeft) | Liest oder setzt die linke Position der Frage |
| [getMultipleSelectionAllowed()](#getMultipleSelectionAllowed) | Liest oder setzt einen Wert, der angibt, ob Mehrfachauswahl erlaubt ist |
| [getName()](#getName) | Liest den Namen der Frage |
| [getOrientation()](#getOrientation) |  |
| [getOrientationString()](#getOrientationString) | Liest die String‑Darstellung der Orientierungseigenschaft |
| [getRect()](#getRect) |  |
| [getTop()](#getTop) | Liest oder setzt die obere Position der Frage |
| [getWidth()](#getWidth) | Liest oder setzt die Breite der Frage |
| [hashCode()](#hashCode) |  |
| [isAlignedHorizontal()](#isAlignedHorizontal) | Liest oder setzt einen Wert, der angibt, ob die Bubbles horizontal ausgerichtet sind |
| [isAlignedVertical()](#isAlignedVertical) | Liest oder setzt einen Wert, der angibt, ob die Bubbles vertikal ausgerichtet sind |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [setAlignedHorizontal(boolean value)](#setAlignedHorizontal-boolean) | Liest oder setzt einen Wert, der angibt, ob die Bubbles horizontal ausgerichtet sind |
| [setAlignedVertical(boolean value)](#setAlignedVertical-boolean) | Liest oder setzt einen Wert, der angibt, ob die Bubbles vertikal ausgerichtet sind |
| [setBubbleHeight(double value)](#setBubbleHeight-double) |  |
| [setBubbleWidth(double value)](#setBubbleWidth-double) |  |
| [setBubbles(System.Collections.Generic.List<OmrBubble> value)](#setBubbles-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrBubble) | Liest oder setzt die Blasen‑Sammlung |
| [setHeight(double value)](#setHeight-double) | Liest oder setzt die Höhe der Frage |
| [setLeft(double value)](#setLeft-double) | Liest oder setzt die linke Position der Frage |
| [setMultipleSelectionAllowed(boolean value)](#setMultipleSelectionAllowed-boolean) | Liest oder setzt einen Wert, der angibt, ob Mehrfachauswahl erlaubt ist |
| [setName(String value)](#setName-java.lang.String) | Setzt den Namen der Frage |
| [setOrientation(int value)](#setOrientation-int) |  |
| [setTop(double value)](#setTop-double) | Liest oder setzt die obere Position der Frage |
| [setWidth(double value)](#setWidth-double) | Liest oder setzt die Breite der Frage |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### ChoiceBoxElement() {#ChoiceBoxElement}
```
public ChoiceBoxElement()
```


Initialisiert eine neue Instanz der [ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) Klasse

### ElementType {#ElementType}
```
public String ElementType
```


### addBubble(String name, int width, int height, int top, int left, boolean isValid) {#addBubble-java.lang.String-int-int-int-int-boolean}
```
public final void addBubble(String name, int width, int height, int top, int left, boolean isValid)
```


Fügt eine Blase innerhalb der Frage hinzu

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String | Blasenname |
| Breite | int | Blasenbreite |
| Höhe | int | Blasenhöhe |
| Oben | int | Obere Position der Blase |
| Links | int | Linke Position der Blase |
| isValid | boolean | Blasen‑Gültigkeitsflag |

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


Liest oder setzt die Blasen‑Sammlung

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrBubble> - Blasen‑Sammlung
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


Liest oder setzt die Höhe der Frage

**Returns:**
double - Die Höhe
### getLeft() {#getLeft}
```
public final double getLeft()
```


Liest oder setzt die linke Position der Frage

**Returns:**
double - Der linke
### getMultipleSelectionAllowed() {#getMultipleSelectionAllowed}
```
public final boolean getMultipleSelectionAllowed()
```


Liest oder setzt einen Wert, der angibt, ob Mehrfachauswahl erlaubt ist

**Returns:**
boolean - Wert, der angibt, ob Mehrfachauswahl erlaubt ist
### getName() {#getName}
```
public final String getName()
```


Liest den Namen der Frage

**Returns:**
java.lang.String - Der Name der Frage
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


Liest die String‑Darstellung der Orientierungseigenschaft

**Returns:**
java.lang.String - String‑Darstellung der Orientierungseigenschaft
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


Liest oder setzt die obere Position der Frage

**Returns:**
double - Der obere
### getWidth() {#getWidth}
```
public final double getWidth()
```


Liest oder setzt die Breite der Frage

**Returns:**
double - Die Breite
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


Liest oder setzt einen Wert, der angibt, ob die Bubbles horizontal ausgerichtet sind

**Returns:**
boolean – Wert, der angibt, ob die Bubbles horizontal ausgerichtet sind
### isAlignedVertical() {#isAlignedVertical}
```
public final boolean isAlignedVertical()
```


Liest oder setzt einen Wert, der angibt, ob die Bubbles vertikal ausgerichtet sind

**Returns:**
boolean – ein Wert, der angibt, ob die Bubbles vertikal ausgerichtet sind
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


Liest oder setzt einen Wert, der angibt, ob die Bubbles horizontal ausgerichtet sind

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob die Bubbles horizontal ausgerichtet sind |

### setAlignedVertical(boolean value) {#setAlignedVertical-boolean}
```
public final void setAlignedVertical(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob die Bubbles vertikal ausgerichtet sind

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob die Bubbles vertikal ausgerichtet sind |

### setBubbleHeight(double value) {#setBubbleHeight-double}
```
public final void setBubbleHeight(double value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setBubbleWidth(double value) {#setBubbleWidth-double}
```
public final void setBubbleWidth(double value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setBubbles(System.Collections.Generic.List<OmrBubble> value) {#setBubbles-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrBubble}
```
public final void setBubbles(System.Collections.Generic.List<OmrBubble> value)
```


Liest oder setzt die Blasen‑Sammlung

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrBubble> | Blasen‑Sammlung |

### setHeight(double value) {#setHeight-double}
```
public final void setHeight(double value)
```


Liest oder setzt die Höhe der Frage

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double | Die Höhe |

### setLeft(double value) {#setLeft-double}
```
public final void setLeft(double value)
```


Liest oder setzt die linke Position der Frage

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double | Der linke |

### setMultipleSelectionAllowed(boolean value) {#setMultipleSelectionAllowed-boolean}
```
public final void setMultipleSelectionAllowed(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob Mehrfachauswahl erlaubt ist

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob Mehrfachauswahl erlaubt ist |

### setName(String value) {#setName-java.lang.String}
```
public final void setName(String value)
```


Setzt den Namen der Frage

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Der Name der Frage |

### setOrientation(int value) {#setOrientation-int}
```
public final void setOrientation(int value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setTop(double value) {#setTop-double}
```
public final void setTop(double value)
```


Liest oder setzt die obere Position der Frage

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double | Der obere |

### setWidth(double value) {#setWidth-double}
```
public final void setWidth(double value)
```


Liest oder setzt die Breite der Frage

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double | Die Breite |

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

