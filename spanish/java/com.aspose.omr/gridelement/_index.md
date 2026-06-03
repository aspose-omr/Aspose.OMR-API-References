---
title: "GridElement"
second_title: "Referencia de API de Aspose.OMR for Java"
description: 
type: docs
weight: 16
url: /es/java/com.aspose.omr/gridelement/
---

**Inheritance:**
java.lang.Object, [com.aspose.omr.OmrElement](../../com.aspose.omr/omrelement/)
```
public class GridElement extends OmrElement
```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [GridElement()](#GridElement) |  |
## Campos

| Campo | Descripción |
| --- | --- |
| [ElementType](#ElementType) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [addChoiceBox(ChoiceBoxElement choiceBox)](#addChoiceBox-com.aspose.omr.ChoiceBoxElement) |  |
| [addChoiceBox(String name, int width, int height, int top, int left)](#addChoiceBox-java.lang.String-int-int-int-int) |  |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getChoiceBoxes()](#getChoiceBoxes) |  |
| [getClass()](#getClass) |  |
| [getHeight()](#getHeight) | Obtiene o establece la altura de la pregunta |
| [getLeft()](#getLeft) | Obtiene o establece la posición izquierda de la pregunta |
| [getName()](#getName) | Obtiene el nombre de la pregunta |
| [getOrientation()](#getOrientation) |  |
| [getOrientationString()](#getOrientationString) |  |
| [getRect()](#getRect) |  |
| [getTop()](#getTop) | Obtiene o establece la posición superior de la pregunta |
| [getWidth()](#getWidth) | Obtiene o establece el ancho de la pregunta |
| [hashCode()](#hashCode) |  |
| [isAlignedHorizontal()](#isAlignedHorizontal) | Obtiene o establece un valor que indica si las burbujas están alineadas horizontalmente |
| [isAlignedVertical()](#isAlignedVertical) | Obtiene o establece un valor que indica si las burbujas están alineadas verticalmente |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [setAlignedHorizontal(boolean value)](#setAlignedHorizontal-boolean) | Obtiene o establece un valor que indica si las burbujas están alineadas horizontalmente |
| [setAlignedVertical(boolean value)](#setAlignedVertical-boolean) | Obtiene o establece un valor que indica si las burbujas están alineadas verticalmente |
| [setChoiceBoxes(System.Collections.Generic.List<OmrElement> value)](#setChoiceBoxes-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement) |  |
| [setHeight(double value)](#setHeight-double) | Obtiene o establece la altura de la pregunta |
| [setLeft(double value)](#setLeft-double) | Obtiene o establece la posición izquierda de la pregunta |
| [setName(String value)](#setName-java.lang.String) | Establece el nombre de la pregunta |
| [setOrientation(int value)](#setOrientation-int) |  |
| [setTop(double value)](#setTop-double) | Obtiene o establece la posición superior de la pregunta |
| [setWidth(double value)](#setWidth-double) | Obtiene o establece el ancho de la pregunta |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| choiceBox | [ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) |  |

### addChoiceBox(String name, int width, int height, int top, int left) {#addChoiceBox-java.lang.String-int-int-int-int}
```
public final ChoiceBoxElement addChoiceBox(String name, int width, int height, int top, int left)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |
| ancho | int |  |
| altura | int |  |
| superior | int |  |
| izquierda | int |  |

**Returns:**
[ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/)
### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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


Obtiene o establece la altura de la pregunta

**Returns:**
double - La altura
### getLeft() {#getLeft}
```
public final double getLeft()
```


Obtiene o establece la posición izquierda de la pregunta

**Returns:**
double - La izquierda
### getName() {#getName}
```
public final String getName()
```


Obtiene el nombre de la pregunta

**Returns:**
java.lang.String - El nombre de la pregunta
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


Obtiene o establece la posición superior de la pregunta

**Returns:**
double - La parte superior
### getWidth() {#getWidth}
```
public final double getWidth()
```


Obtiene o establece el ancho de la pregunta

**Returns:**
double - El ancho
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


Obtiene o establece un valor que indica si las burbujas están alineadas horizontalmente

**Returns:**
boolean - valor que indica si las burbujas están alineadas horizontalmente
### isAlignedVertical() {#isAlignedVertical}
```
public final boolean isAlignedVertical()
```


Obtiene o establece un valor que indica si las burbujas están alineadas verticalmente

**Returns:**
boolean - un valor que indica si las burbujas están alineadas verticalmente
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


Obtiene o establece un valor que indica si las burbujas están alineadas horizontalmente

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | un valor que indica si las burbujas están alineadas horizontalmente |

### setAlignedVertical(boolean value) {#setAlignedVertical-boolean}
```
public final void setAlignedVertical(boolean value)
```


Obtiene o establece un valor que indica si las burbujas están alineadas verticalmente

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | un valor que indica si las burbujas están alineadas verticalmente |

### setChoiceBoxes(System.Collections.Generic.List<OmrElement> value) {#setChoiceBoxes-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement}
```
public final void setChoiceBoxes(System.Collections.Generic.List<OmrElement> value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrElement> |  |

### setHeight(double value) {#setHeight-double}
```
public final void setHeight(double value)
```


Obtiene o establece la altura de la pregunta

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | La altura |

### setLeft(double value) {#setLeft-double}
```
public final void setLeft(double value)
```


Obtiene o establece la posición izquierda de la pregunta

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | La izquierda |

### setName(String value) {#setName-java.lang.String}
```
public final void setName(String value)
```


Establece el nombre de la pregunta

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | El nombre de la pregunta |

### setOrientation(int value) {#setOrientation-int}
```
public final void setOrientation(int value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setTop(double value) {#setTop-double}
```
public final void setTop(double value)
```


Obtiene o establece la posición superior de la pregunta

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | La parte superior |

### setWidth(double value) {#setWidth-double}
```
public final void setWidth(double value)
```


Obtiene o establece el ancho de la pregunta

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | El ancho |

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

