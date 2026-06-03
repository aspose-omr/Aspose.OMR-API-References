---
title: "OmrPage"
second_title: "Référence API d'Aspose.OMR pour Java"
description: "Représente une seule page OMR"
type: docs
weight: 24
url: /fr/java/com.aspose.omr/omrpage/
---

**Inheritance:**
java.lang.Object
```
public class OmrPage
```

Représente une seule page OMR
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [OmrPage()](#OmrPage) | Initialise une nouvelle instance de la classe [OmrPage](../../com.aspose.omr/omrpage/) |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addBarcodeElement(BarcodeElement element)](#addBarcodeElement-com.aspose.omr.BarcodeElement) |  |
| [addChoiceBoxElement(String name, int width, int height, int top, int left)](#addChoiceBoxElement-java.lang.String-int-int-int-int) | Ajouter un élément de case à cocher sur la page |
| [addClipAreaElement(String name, int width, int height, int top, int left)](#addClipAreaElement-java.lang.String-int-int-int-int) |  |
| [addGridElement(GridElement grid)](#addGridElement-com.aspose.omr.GridElement) |  |
| [addGridElement(String name, int width, int height, int top, int left)](#addGridElement-java.lang.String-int-int-int-int) |  |
| [addRefPointElement(ReferencePointElement item)](#addRefPointElement-com.aspose.omr.ReferencePointElement) |  |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [getElements()](#getElements) | Obtient ou définit la liste des éléments sur la page |
| [getHeight()](#getHeight) | Obtient ou définit la hauteur de la page |
| [getImageFormat()](#getImageFormat) | Obtient ou définit le format de fichier de l'image |
| [getImageName()](#getImageName) | Obtient ou définit les données de l'image |
| [getRotationPointPosition()](#getRotationPointPosition) | Obtient ou définit la RotationPointPosition |
| [getWidth()](#getWidth) | Obtient ou définit la largeur de la page |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [setElements(System.Collections.Generic.List<OmrElement> value)](#setElements-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement) | Obtient ou définit la liste des éléments sur la page |
| [setHeight(double value)](#setHeight-double) | Obtient ou définit la hauteur de la page |
| [setImageFormat(String value)](#setImageFormat-java.lang.String) | Obtient ou définit le format de fichier de l'image |
| [setImageName(String value)](#setImageName-java.lang.String) | Obtient ou définit le nom de l'image |
| [setRotationPointPosition(RotationPointPosition value)](#setRotationPointPosition-com.aspose.omr.RotationPointPosition) | Obtient ou définit la RotationPointPosition |
| [setWidth(double value)](#setWidth-double) | Obtient ou définit la largeur de la page |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### OmrPage() {#OmrPage}
```
public OmrPage()
```


Initialise une nouvelle instance de la classe [OmrPage](../../com.aspose.omr/omrpage/)

### addBarcodeElement(BarcodeElement element) {#addBarcodeElement-com.aspose.omr.BarcodeElement}
```
public final void addBarcodeElement(BarcodeElement element)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| element | [BarcodeElement](../../com.aspose.omr/barcodeelement/) |  |

### addChoiceBoxElement(String name, int width, int height, int top, int left) {#addChoiceBoxElement-java.lang.String-int-int-int-int}
```
public final ChoiceBoxElement addChoiceBoxElement(String name, int width, int height, int top, int left)
```


Ajouter un élément de case à cocher sur la page

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Nom de l'élément |
| largeur | int | Largeur de l'élément |
| hauteur | int | Hauteur de l'élément |
| haut | int | Position supérieure de l'élément |
| gauche | int | Position gauche de l'élément |

**Returns:**
[ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) - Created choice box
### addClipAreaElement(String name, int width, int height, int top, int left) {#addClipAreaElement-java.lang.String-int-int-int-int}
```
public final ClipAreaElement addClipAreaElement(String name, int width, int height, int top, int left)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |
| largeur | int |  |
| hauteur | int |  |
| haut | int |  |
| gauche | int |  |

**Returns:**
[ClipAreaElement](../../com.aspose.omr/clipareaelement/)
### addGridElement(GridElement grid) {#addGridElement-com.aspose.omr.GridElement}
```
public final void addGridElement(GridElement grid)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| grid | [GridElement](../../com.aspose.omr/gridelement/) |  |

### addGridElement(String name, int width, int height, int top, int left) {#addGridElement-java.lang.String-int-int-int-int}
```
public final GridElement addGridElement(String name, int width, int height, int top, int left)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |
| largeur | int |  |
| hauteur | int |  |
| haut | int |  |
| gauche | int |  |

**Returns:**
[GridElement](../../com.aspose.omr/gridelement/)
### addRefPointElement(ReferencePointElement item) {#addRefPointElement-com.aspose.omr.ReferencePointElement}
```
public final void addRefPointElement(ReferencePointElement item)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [ReferencePointElement](../../com.aspose.omr/referencepointelement/) |  |

### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
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


Obtient ou définit la liste des éléments sur la page

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrElement> - liste des éléments sur la page
### getHeight() {#getHeight}
```
public final double getHeight()
```


Obtient ou définit la hauteur de la page

**Returns:**
double - hauteur de la page
### getImageFormat() {#getImageFormat}
```
public final String getImageFormat()
```


Obtient ou définit le format de fichier de l'image

**Returns:**
java.lang.String - le format de fichier de l'image
### getImageName() {#getImageName}
```
public final String getImageName()
```


Obtient ou définit les données de l'image

**Returns:**
java.lang.String - le nom de l'image
### getRotationPointPosition() {#getRotationPointPosition}
```
public final RotationPointPosition getRotationPointPosition()
```


Obtient ou définit la RotationPointPosition

**Returns:**
[RotationPointPosition](../../com.aspose.omr/rotationpointposition/) - RotationPointPosition
### getWidth() {#getWidth}
```
public final double getWidth()
```


Obtient ou définit la largeur de la page

**Returns:**
double - largeur de la page
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


Obtient ou définit la liste des éléments sur la page

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrElement> | liste des éléments sur la page |

### setHeight(double value) {#setHeight-double}
```
public final void setHeight(double value)
```


Obtient ou définit la hauteur de la page

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | hauteur de la page |

### setImageFormat(String value) {#setImageFormat-java.lang.String}
```
public final void setImageFormat(String value)
```


Obtient ou définit le format de fichier de l'image

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | le format de fichier de l'image |

### setImageName(String value) {#setImageName-java.lang.String}
```
public final void setImageName(String value)
```


Obtient ou définit le nom de l'image

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | nom de l'image |

### setRotationPointPosition(RotationPointPosition value) {#setRotationPointPosition-com.aspose.omr.RotationPointPosition}
```
public final void setRotationPointPosition(RotationPointPosition value)
```


Obtient ou définit la RotationPointPosition

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RotationPointPosition](../../com.aspose.omr/rotationpointposition/) | RotationPointPosition |

### setWidth(double value) {#setWidth-double}
```
public final void setWidth(double value)
```


Obtient ou définit la largeur de la page

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | largeur de la page |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

