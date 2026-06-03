---
title: "GridElement"
second_title: "Aspose.OMR für Java API-Referenz"
description: 
type: docs
weight: 16
url: /de/java/com.aspose.omr/gridelement/
---

**Inheritance:**
java.lang.Object, [com.aspose.omr.OmrElement](../../com.aspose.omr/omrelement/)
```
public class GridElement extends OmrElement
```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [GridElement()](#GridElement) |  |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [ElementType](#ElementType) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addChoiceBox(ChoiceBoxElement choiceBox)](#addChoiceBox-com.aspose.omr.ChoiceBoxElement) |  |
| [addChoiceBox(String name, int width, int height, int top, int left)](#addChoiceBox-java.lang.String-int-int-int-int) |  |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getChoiceBoxes()](#getChoiceBoxes) |  |
| [getClass()](#getClass) |  |
| [getHeight()](#getHeight) | Liest oder setzt die Höhe der Frage |
| [getLeft()](#getLeft) | Liest oder setzt die linke Position der Frage |
| [getName()](#getName) | Liest den Namen der Frage |
| [getOrientation()](#getOrientation) |  |
| [getOrientationString()](#getOrientationString) |  |
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
| [setChoiceBoxes(System.Collections.Generic.List<OmrElement> value)](#setChoiceBoxes-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement) |  |
| [setHeight(double value)](#setHeight-double) | Liest oder setzt die Höhe der Frage |
| [setLeft(double value)](#setLeft-double) | Liest oder setzt die linke Position der Frage |
| [setName(String value)](#setName-java.lang.String) | Setzt den Namen der Frage |
| [setOrientation(int value)](#setOrientation-int) |  |
| [setTop(double value)](#setTop-double) | Liest oder setzt die obere Position der Frage |
| [setWidth(double value)](#setWidth-double) | Liest oder setzt die Breite der Frage |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| choiceBox | [ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) |  |

### addChoiceBox(String name, int width, int height, int top, int left) {#addChoiceBox-java.lang.String-int-int-int-int}
```
public final ChoiceBoxElement addChoiceBox(String name, int width, int height, int top, int left)
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
[ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/)
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

### setChoiceBoxes(System.Collections.Generic.List<OmrElement> value) {#setChoiceBoxes-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement}
```
public final void setChoiceBoxes(System.Collections.Generic.List<OmrElement> value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrElement> |  |

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

