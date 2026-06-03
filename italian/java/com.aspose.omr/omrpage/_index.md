---
title: "OmrPage"
second_title: "Riferimento API Aspose.OMR per Java"
description: "Rappresenta una singola pagina omr"
type: docs
weight: 24
url: /it/java/com.aspose.omr/omrpage/
---

**Inheritance:**
java.lang.Object
```
public class OmrPage
```

Rappresenta una singola pagina omr
## Costruttori

| Costruttore | Description |
| --- | --- |
| [OmrPage()](#OmrPage) | Inizializza una nuova istanza della classe [OmrPage](../../com.aspose.omr/omrpage/) |
## Metodi

| Metodo | Description |
| --- | --- |
| [addBarcodeElement(BarcodeElement element)](#addBarcodeElement-com.aspose.omr.BarcodeElement) |  |
| [addChoiceBoxElement(String name, int width, int height, int top, int left)](#addChoiceBoxElement-java.lang.String-int-int-int-int) | Aggiungi elemento casella di scelta nella pagina |
| [addClipAreaElement(String name, int width, int height, int top, int left)](#addClipAreaElement-java.lang.String-int-int-int-int) |  |
| [addGridElement(GridElement grid)](#addGridElement-com.aspose.omr.GridElement) |  |
| [addGridElement(String name, int width, int height, int top, int left)](#addGridElement-java.lang.String-int-int-int-int) |  |
| [addRefPointElement(ReferencePointElement item)](#addRefPointElement-com.aspose.omr.ReferencePointElement) |  |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [getElements()](#getElements) | Ottiene o imposta l'elenco degli elementi nella pagina |
| [getHeight()](#getHeight) | Ottiene o imposta l'altezza della pagina |
| [getImageFormat()](#getImageFormat) | Ottiene o imposta il formato del file immagine |
| [getImageName()](#getImageName) | Ottiene o imposta i dati dell'immagine |
| [getRotationPointPosition()](#getRotationPointPosition) | Ottiene o imposta la RotationPointPosition |
| [getWidth()](#getWidth) | Ottiene o imposta la larghezza della pagina |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [setElements(System.Collections.Generic.List<OmrElement> value)](#setElements-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement) | Ottiene o imposta l'elenco degli elementi nella pagina |
| [setHeight(double value)](#setHeight-double) | Ottiene o imposta l'altezza della pagina |
| [setImageFormat(String value)](#setImageFormat-java.lang.String) | Ottiene o imposta il formato del file immagine |
| [setImageName(String value)](#setImageName-java.lang.String) | Ottiene o imposta il nome dell'immagine |
| [setRotationPointPosition(RotationPointPosition value)](#setRotationPointPosition-com.aspose.omr.RotationPointPosition) | Ottiene o imposta la RotationPointPosition |
| [setWidth(double value)](#setWidth-double) | Ottiene o imposta la larghezza della pagina |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### OmrPage() {#OmrPage}
```
public OmrPage()
```


Inizializza una nuova istanza della classe [OmrPage](../../com.aspose.omr/omrpage/)

### addBarcodeElement(BarcodeElement element) {#addBarcodeElement-com.aspose.omr.BarcodeElement}
```
public final void addBarcodeElement(BarcodeElement element)
```




**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| element | [BarcodeElement](../../com.aspose.omr/barcodeelement/) |  |

### addChoiceBoxElement(String name, int width, int height, int top, int left) {#addChoiceBoxElement-java.lang.String-int-int-int-int}
```
public final ChoiceBoxElement addChoiceBoxElement(String name, int width, int height, int top, int left)
```


Aggiungi elemento casella di scelta nella pagina

**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| nome | java.lang.String | Nome elemento |
| larghezza | int | Larghezza elemento |
| altezza | int | Altezza elemento |
| alto | int | Posizione superiore dell'elemento |
| sinistra | int | Posizione sinistra dell'elemento |

**Returns:**
[ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) - Created choice box
### addClipAreaElement(String name, int width, int height, int top, int left) {#addClipAreaElement-java.lang.String-int-int-int-int}
```
public final ClipAreaElement addClipAreaElement(String name, int width, int height, int top, int left)
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
[ClipAreaElement](../../com.aspose.omr/clipareaelement/)
### addGridElement(GridElement grid) {#addGridElement-com.aspose.omr.GridElement}
```
public final void addGridElement(GridElement grid)
```




**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| grid | [GridElement](../../com.aspose.omr/gridelement/) |  |

### addGridElement(String name, int width, int height, int top, int left) {#addGridElement-java.lang.String-int-int-int-int}
```
public final GridElement addGridElement(String name, int width, int height, int top, int left)
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
[GridElement](../../com.aspose.omr/gridelement/)
### addRefPointElement(ReferencePointElement item) {#addRefPointElement-com.aspose.omr.ReferencePointElement}
```
public final void addRefPointElement(ReferencePointElement item)
```




**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| item | [ReferencePointElement](../../com.aspose.omr/referencepointelement/) |  |

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


Ottiene o imposta l'elenco degli elementi nella pagina

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrElement> - elenco degli elementi nella pagina
### getHeight() {#getHeight}
```
public final double getHeight()
```


Ottiene o imposta l'altezza della pagina

**Returns:**
double - altezza della pagina
### getImageFormat() {#getImageFormat}
```
public final String getImageFormat()
```


Ottiene o imposta il formato del file immagine

**Returns:**
java.lang.String - il formato del file immagine
### getImageName() {#getImageName}
```
public final String getImageName()
```


Ottiene o imposta i dati dell'immagine

**Returns:**
java.lang.String - il nome dell'immagine
### getRotationPointPosition() {#getRotationPointPosition}
```
public final RotationPointPosition getRotationPointPosition()
```


Ottiene o imposta la RotationPointPosition

**Returns:**
[RotationPointPosition](../../com.aspose.omr/rotationpointposition/) - RotationPointPosition
### getWidth() {#getWidth}
```
public final double getWidth()
```


Ottiene o imposta la larghezza della pagina

**Returns:**
double - larghezza della pagina
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


Ottiene o imposta l'elenco degli elementi nella pagina

**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| valore | com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrElement> | elenco degli elementi nella pagina |

### setHeight(double value) {#setHeight-double}
```
public final void setHeight(double value)
```


Ottiene o imposta l'altezza della pagina

**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| valore | double | altezza della pagina |

### setImageFormat(String value) {#setImageFormat-java.lang.String}
```
public final void setImageFormat(String value)
```


Ottiene o imposta il formato del file immagine

**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| valore | java.lang.String | il formato del file immagine |

### setImageName(String value) {#setImageName-java.lang.String}
```
public final void setImageName(String value)
```


Ottiene o imposta il nome dell'immagine

**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| valore | java.lang.String | nome immagine |

### setRotationPointPosition(RotationPointPosition value) {#setRotationPointPosition-com.aspose.omr.RotationPointPosition}
```
public final void setRotationPointPosition(RotationPointPosition value)
```


Ottiene o imposta la RotationPointPosition

**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| value | [RotationPointPosition](../../com.aspose.omr/rotationpointposition/) | RotationPointPosition |

### setWidth(double value) {#setWidth-double}
```
public final void setWidth(double value)
```


Ottiene o imposta la larghezza della pagina

**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| valore | double | larghezza pagina |

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

