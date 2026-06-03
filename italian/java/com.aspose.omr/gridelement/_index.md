---
title: "GridElement"
second_title: "Riferimento API Aspose.OMR per Java"
description: 
type: docs
weight: 16
url: /it/java/com.aspose.omr/gridelement/
---

**Inheritance:**
java.lang.Object, [com.aspose.omr.OmrElement](../../com.aspose.omr/omrelement/)
```
public class GridElement extends OmrElement
```
## Costruttori

| Costruttore | Description |
| --- | --- |
| [GridElement()](#GridElement) |  |
## Campi

| Campo | Description |
| --- | --- |
| [ElementType](#ElementType) |  |
## Metodi

| Metodo | Description |
| --- | --- |
| [addChoiceBox(ChoiceBoxElement choiceBox)](#addChoiceBox-com.aspose.omr.ChoiceBoxElement) |  |
| [addChoiceBox(String name, int width, int height, int top, int left)](#addChoiceBox-java.lang.String-int-int-int-int) |  |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getChoiceBoxes()](#getChoiceBoxes) |  |
| [getClass()](#getClass) |  |
| [getHeight()](#getHeight) | Ottiene o imposta l'altezza della domanda |
| [getLeft()](#getLeft) | Ottiene o imposta la posizione sinistra della domanda |
| [getName()](#getName) | Ottiene il nome della domanda |
| [getOrientation()](#getOrientation) |  |
| [getOrientationString()](#getOrientationString) |  |
| [getRect()](#getRect) |  |
| [getTop()](#getTop) | Ottiene o imposta la posizione superiore della domanda |
| [getWidth()](#getWidth) | Ottiene o imposta la larghezza della domanda |
| [hashCode()](#hashCode) |  |
| [isAlignedHorizontal()](#isAlignedHorizontal) | Ottiene o imposta un valore che indica se le bolle sono allineate orizzontalmente |
| [isAlignedVertical()](#isAlignedVertical) | Ottiene o imposta un valore che indica se le bolle sono allineate verticalmente |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [setAlignedHorizontal(boolean value)](#setAlignedHorizontal-boolean) | Ottiene o imposta un valore che indica se le bolle sono allineate orizzontalmente |
| [setAlignedVertical(boolean value)](#setAlignedVertical-boolean) | Ottiene o imposta un valore che indica se le bolle sono allineate verticalmente |
| [setChoiceBoxes(System.Collections.Generic.List<OmrElement> value)](#setChoiceBoxes-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement) |  |
| [setHeight(double value)](#setHeight-double) | Ottiene o imposta l'altezza della domanda |
| [setLeft(double value)](#setLeft-double) | Ottiene o imposta la posizione sinistra della domanda |
| [setName(String value)](#setName-java.lang.String) | Imposta il nome della domanda |
| [setOrientation(int value)](#setOrientation-int) |  |
| [setTop(double value)](#setTop-double) | Ottiene o imposta la posizione superiore della domanda |
| [setWidth(double value)](#setWidth-double) | Ottiene o imposta la larghezza della domanda |
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
| Parametro | Tipo | Description |
| --- | --- | --- |
| choiceBox | [ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) |  |

### addChoiceBox(String name, int width, int height, int top, int left) {#addChoiceBox-java.lang.String-int-int-int-int}
```
public final ChoiceBoxElement addChoiceBox(String name, int width, int height, int top, int left)
```




**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| nome | java.lang.String |  |
| larghezza | int |  |
| altezza | int |  |
| alto | int |  |
| sinistra | int |  |

**Returns:**
[ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/)
### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Description |
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


Ottiene o imposta l'altezza della domanda

**Returns:**
double - L'altezza
### getLeft() {#getLeft}
```
public final double getLeft()
```


Ottiene o imposta la posizione sinistra della domanda

**Returns:**
double - La sinistra
### getName() {#getName}
```
public final String getName()
```


Ottiene il nome della domanda

**Returns:**
java.lang.String - Il nome della domanda
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


Ottiene o imposta la posizione superiore della domanda

**Returns:**
double - La parte superiore
### getWidth() {#getWidth}
```
public final double getWidth()
```


Ottiene o imposta la larghezza della domanda

**Returns:**
double - La larghezza
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


Ottiene o imposta un valore che indica se le bolle sono allineate orizzontalmente

**Returns:**
boolean - valore che indica se le bolle sono allineate orizzontalmente
### isAlignedVertical() {#isAlignedVertical}
```
public final boolean isAlignedVertical()
```


Ottiene o imposta un valore che indica se le bolle sono allineate verticalmente

**Returns:**
boolean - valore che indica se le bolle sono allineate verticalmente
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


Ottiene o imposta un valore che indica se le bolle sono allineate orizzontalmente

**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| valore | boolean | un valore che indica se le bolle sono allineate orizzontalmente |

### setAlignedVertical(boolean value) {#setAlignedVertical-boolean}
```
public final void setAlignedVertical(boolean value)
```


Ottiene o imposta un valore che indica se le bolle sono allineate verticalmente

**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| valore | boolean | un valore che indica se le bolle sono allineate verticalmente |

### setChoiceBoxes(System.Collections.Generic.List<OmrElement> value) {#setChoiceBoxes-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement}
```
public final void setChoiceBoxes(System.Collections.Generic.List<OmrElement> value)
```




**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| valore | com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrElement> |  |

### setHeight(double value) {#setHeight-double}
```
public final void setHeight(double value)
```


Ottiene o imposta l'altezza della domanda

**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| valore | double | L'altezza |

### setLeft(double value) {#setLeft-double}
```
public final void setLeft(double value)
```


Ottiene o imposta la posizione sinistra della domanda

**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| valore | double | La sinistra |

### setName(String value) {#setName-java.lang.String}
```
public final void setName(String value)
```


Imposta il nome della domanda

**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| valore | java.lang.String | Il nome della domanda |

### setOrientation(int value) {#setOrientation-int}
```
public final void setOrientation(int value)
```




**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| valore | int |  |

### setTop(double value) {#setTop-double}
```
public final void setTop(double value)
```


Ottiene o imposta la posizione superiore della domanda

**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| valore | double | La parte superiore |

### setWidth(double value) {#setWidth-double}
```
public final void setWidth(double value)
```


Ottiene o imposta la larghezza della domanda

**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| valore | double | La larghezza |

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
| Parametro | Tipo | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

