---
title: "ChoiceBoxElement"
second_title: "Riferimento API Aspose.OMR per Java"
description: "Rappresenta la domanda ChoiceBox"
type: docs
weight: 11
url: /it/java/com.aspose.omr/choiceboxelement/
---

**Inheritance:**
java.lang.Object, [com.aspose.omr.OmrElement](../../com.aspose.omr/omrelement/)
```
public class ChoiceBoxElement extends OmrElement
```

Rappresenta la domanda ChoiceBox
## Costruttori

| Costruttore | Description |
| --- | --- |
| [ChoiceBoxElement()](#ChoiceBoxElement) | Inizializza una nuova istanza della classe [ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) |
## Campi

| Campo | Description |
| --- | --- |
| [ElementType](#ElementType) |  |
## Metodi

| Metodo | Description |
| --- | --- |
| [addBubble(String name, int width, int height, int top, int left, boolean isValid)](#addBubble-java.lang.String-int-int-int-int-boolean) | Aggiunge una bolla all'interno della domanda |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getBubbleHeight()](#getBubbleHeight) |  |
| [getBubbleWidth()](#getBubbleWidth) |  |
| [getBubbles()](#getBubbles) | Ottiene o imposta la collezione di bolle |
| [getClass()](#getClass) |  |
| [getHeight()](#getHeight) | Ottiene o imposta l'altezza della domanda |
| [getLeft()](#getLeft) | Ottiene o imposta la posizione sinistra della domanda |
| [getMultipleSelectionAllowed()](#getMultipleSelectionAllowed) | Ottiene o imposta un valore che indica se è consentita la selezione multipla |
| [getName()](#getName) | Ottiene il nome della domanda |
| [getOrientation()](#getOrientation) |  |
| [getOrientationString()](#getOrientationString) | Ottiene la rappresentazione stringa della proprietà orientamento |
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
| [setBubbleHeight(double value)](#setBubbleHeight-double) |  |
| [setBubbleWidth(double value)](#setBubbleWidth-double) |  |
| [setBubbles(System.Collections.Generic.List<OmrBubble> value)](#setBubbles-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrBubble) | Ottiene o imposta la collezione di bolle |
| [setHeight(double value)](#setHeight-double) | Ottiene o imposta l'altezza della domanda |
| [setLeft(double value)](#setLeft-double) | Ottiene o imposta la posizione sinistra della domanda |
| [setMultipleSelectionAllowed(boolean value)](#setMultipleSelectionAllowed-boolean) | Ottiene o imposta un valore che indica se è consentita la selezione multipla |
| [setName(String value)](#setName-java.lang.String) | Imposta il nome della domanda |
| [setOrientation(int value)](#setOrientation-int) |  |
| [setTop(double value)](#setTop-double) | Ottiene o imposta la posizione superiore della domanda |
| [setWidth(double value)](#setWidth-double) | Ottiene o imposta la larghezza della domanda |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### ChoiceBoxElement() {#ChoiceBoxElement}
```
public ChoiceBoxElement()
```


Inizializza una nuova istanza della classe [ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/)

### ElementType {#ElementType}
```
public String ElementType
```


### addBubble(String name, int width, int height, int top, int left, boolean isValid) {#addBubble-java.lang.String-int-int-int-int-boolean}
```
public final void addBubble(String name, int width, int height, int top, int left, boolean isValid)
```


Aggiunge una bolla all'interno della domanda

**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| nome | java.lang.String | Nome della bolla |
| larghezza | int | Larghezza della bolla |
| altezza | int | Altezza della bolla |
| alto | int | Posizione superiore della bolla |
| sinistra | int | Posizione sinistra della bolla |
| isValid | boolean | Flag di validità della bolla |

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


Ottiene o imposta la collezione di bolle

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrBubble> - collezione di bolle
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
### getMultipleSelectionAllowed() {#getMultipleSelectionAllowed}
```
public final boolean getMultipleSelectionAllowed()
```


Ottiene o imposta un valore che indica se è consentita la selezione multipla

**Returns:**
boolean - valore che indica se è consentita la selezione multipla
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


Ottiene la rappresentazione stringa della proprietà orientamento

**Returns:**
java.lang.String - rappresentazione stringa della proprietà orientamento
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

### setBubbleHeight(double value) {#setBubbleHeight-double}
```
public final void setBubbleHeight(double value)
```




**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| valore | double |  |

### setBubbleWidth(double value) {#setBubbleWidth-double}
```
public final void setBubbleWidth(double value)
```




**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| valore | double |  |

### setBubbles(System.Collections.Generic.List<OmrBubble> value) {#setBubbles-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrBubble}
```
public final void setBubbles(System.Collections.Generic.List<OmrBubble> value)
```


Ottiene o imposta la collezione di bolle

**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| valore | com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrBubble> | collezione di bolle |

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

### setMultipleSelectionAllowed(boolean value) {#setMultipleSelectionAllowed-boolean}
```
public final void setMultipleSelectionAllowed(boolean value)
```


Ottiene o imposta un valore che indica se è consentita la selezione multipla

**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| valore | boolean | un valore che indica se è consentita la selezione multipla |

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

