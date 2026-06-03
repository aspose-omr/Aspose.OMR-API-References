---
title: "OmrPage"
second_title: "Referencia de API de Aspose.OMR for Java"
description: "Representa una única página OMR"
type: docs
weight: 24
url: /es/java/com.aspose.omr/omrpage/
---

**Inheritance:**
java.lang.Object
```
public class OmrPage
```

Representa una única página OMR
## Constructores

| Constructor | Descripción |
| --- | --- |
| [OmrPage()](#OmrPage) | Inicializa una nueva instancia de la clase [OmrPage](../../com.aspose.omr/omrpage/) |
## Métodos

| Método | Descripción |
| --- | --- |
| [addBarcodeElement(BarcodeElement element)](#addBarcodeElement-com.aspose.omr.BarcodeElement) |  |
| [addChoiceBoxElement(String name, int width, int height, int top, int left)](#addChoiceBoxElement-java.lang.String-int-int-int-int) | Agregar elemento de cuadro de opción en la página |
| [addClipAreaElement(String name, int width, int height, int top, int left)](#addClipAreaElement-java.lang.String-int-int-int-int) |  |
| [addGridElement(GridElement grid)](#addGridElement-com.aspose.omr.GridElement) |  |
| [addGridElement(String name, int width, int height, int top, int left)](#addGridElement-java.lang.String-int-int-int-int) |  |
| [addRefPointElement(ReferencePointElement item)](#addRefPointElement-com.aspose.omr.ReferencePointElement) |  |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [getElements()](#getElements) | Obtiene o establece la lista de elementos en la página |
| [getHeight()](#getHeight) | Obtiene o establece la altura de la página |
| [getImageFormat()](#getImageFormat) | Obtiene o establece el formato de archivo de la imagen |
| [getImageName()](#getImageName) | Obtiene o establece los datos de la imagen |
| [getRotationPointPosition()](#getRotationPointPosition) | Obtiene o establece la RotationPointPosition |
| [getWidth()](#getWidth) | Obtiene o establece el ancho de la página |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [setElements(System.Collections.Generic.List<OmrElement> value)](#setElements-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement) | Obtiene o establece la lista de elementos en la página |
| [setHeight(double value)](#setHeight-double) | Obtiene o establece la altura de la página |
| [setImageFormat(String value)](#setImageFormat-java.lang.String) | Obtiene o establece el formato de archivo de la imagen |
| [setImageName(String value)](#setImageName-java.lang.String) | Obtiene o establece el nombre de la imagen |
| [setRotationPointPosition(RotationPointPosition value)](#setRotationPointPosition-com.aspose.omr.RotationPointPosition) | Obtiene o establece la RotationPointPosition |
| [setWidth(double value)](#setWidth-double) | Obtiene o establece el ancho de la página |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### OmrPage() {#OmrPage}
```
public OmrPage()
```


Inicializa una nueva instancia de la clase [OmrPage](../../com.aspose.omr/omrpage/)

### addBarcodeElement(BarcodeElement element) {#addBarcodeElement-com.aspose.omr.BarcodeElement}
```
public final void addBarcodeElement(BarcodeElement element)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [BarcodeElement](../../com.aspose.omr/barcodeelement/) |  |

### addChoiceBoxElement(String name, int width, int height, int top, int left) {#addChoiceBoxElement-java.lang.String-int-int-int-int}
```
public final ChoiceBoxElement addChoiceBoxElement(String name, int width, int height, int top, int left)
```


Agregar elemento de cuadro de opción en la página

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String | Nombre del elemento |
| ancho | int | Ancho del elemento |
| altura | int | Altura del elemento |
| superior | int | Posición superior del elemento |
| izquierda | int | Posición izquierda del elemento |

**Returns:**
[ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) - Created choice box
### addClipAreaElement(String name, int width, int height, int top, int left) {#addClipAreaElement-java.lang.String-int-int-int-int}
```
public final ClipAreaElement addClipAreaElement(String name, int width, int height, int top, int left)
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
[ClipAreaElement](../../com.aspose.omr/clipareaelement/)
### addGridElement(GridElement grid) {#addGridElement-com.aspose.omr.GridElement}
```
public final void addGridElement(GridElement grid)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| grid | [GridElement](../../com.aspose.omr/gridelement/) |  |

### addGridElement(String name, int width, int height, int top, int left) {#addGridElement-java.lang.String-int-int-int-int}
```
public final GridElement addGridElement(String name, int width, int height, int top, int left)
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
[GridElement](../../com.aspose.omr/gridelement/)
### addRefPointElement(ReferencePointElement item) {#addRefPointElement-com.aspose.omr.ReferencePointElement}
```
public final void addRefPointElement(ReferencePointElement item)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [ReferencePointElement](../../com.aspose.omr/referencepointelement/) |  |

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


Obtiene o establece la lista de elementos en la página

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrElement> - lista de elementos en la página
### getHeight() {#getHeight}
```
public final double getHeight()
```


Obtiene o establece la altura de la página

**Returns:**
double - altura de la página
### getImageFormat() {#getImageFormat}
```
public final String getImageFormat()
```


Obtiene o establece el formato de archivo de la imagen

**Returns:**
java.lang.String - el formato de archivo de la imagen
### getImageName() {#getImageName}
```
public final String getImageName()
```


Obtiene o establece los datos de la imagen

**Returns:**
java.lang.String - el nombre de la imagen
### getRotationPointPosition() {#getRotationPointPosition}
```
public final RotationPointPosition getRotationPointPosition()
```


Obtiene o establece la RotationPointPosition

**Returns:**
[RotationPointPosition](../../com.aspose.omr/rotationpointposition/) - RotationPointPosition
### getWidth() {#getWidth}
```
public final double getWidth()
```


Obtiene o establece el ancho de la página

**Returns:**
double - ancho de la página
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


Obtiene o establece la lista de elementos en la página

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrElement> | lista de elementos en la página |

### setHeight(double value) {#setHeight-double}
```
public final void setHeight(double value)
```


Obtiene o establece la altura de la página

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | altura de la página |

### setImageFormat(String value) {#setImageFormat-java.lang.String}
```
public final void setImageFormat(String value)
```


Obtiene o establece el formato de archivo de la imagen

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | el formato de archivo de la imagen |

### setImageName(String value) {#setImageName-java.lang.String}
```
public final void setImageName(String value)
```


Obtiene o establece el nombre de la imagen

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | nombre de imagen |

### setRotationPointPosition(RotationPointPosition value) {#setRotationPointPosition-com.aspose.omr.RotationPointPosition}
```
public final void setRotationPointPosition(RotationPointPosition value)
```


Obtiene o establece la RotationPointPosition

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RotationPointPosition](../../com.aspose.omr/rotationpointposition/) | RotationPointPosition |

### setWidth(double value) {#setWidth-double}
```
public final void setWidth(double value)
```


Obtiene o establece el ancho de la página

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | ancho de página |

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

