---
title: "GridElement"
second_title: "Référence API d'Aspose.OMR pour Java"
description: 
type: docs
weight: 16
url: /fr/java/com.aspose.omr/gridelement/
---

**Inheritance:**
java.lang.Object, [com.aspose.omr.OmrElement](../../com.aspose.omr/omrelement/)
```
public class GridElement extends OmrElement
```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [GridElement()](#GridElement) |  |
## Champs

| Champ | Description |
| --- | --- |
| [ElementType](#ElementType) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addChoiceBox(ChoiceBoxElement choiceBox)](#addChoiceBox-com.aspose.omr.ChoiceBoxElement) |  |
| [addChoiceBox(String name, int width, int height, int top, int left)](#addChoiceBox-java.lang.String-int-int-int-int) |  |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getChoiceBoxes()](#getChoiceBoxes) |  |
| [getClass()](#getClass) |  |
| [getHeight()](#getHeight) | Obtient ou définit la hauteur de la question |
| [getLeft()](#getLeft) | Obtient ou définit la position gauche de la question |
| [getName()](#getName) | Obtient le nom de la question |
| [getOrientation()](#getOrientation) |  |
| [getOrientationString()](#getOrientationString) |  |
| [getRect()](#getRect) |  |
| [getTop()](#getTop) | Obtient ou définit la position supérieure de la question |
| [getWidth()](#getWidth) | Obtient ou définit la largeur de la question |
| [hashCode()](#hashCode) |  |
| [isAlignedHorizontal()](#isAlignedHorizontal) | Obtient ou définit une valeur indiquant si les bulles sont alignées horizontalement |
| [isAlignedVertical()](#isAlignedVertical) | Obtient ou définit une valeur indiquant si les bulles sont alignées verticalement |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [setAlignedHorizontal(boolean value)](#setAlignedHorizontal-boolean) | Obtient ou définit une valeur indiquant si les bulles sont alignées horizontalement |
| [setAlignedVertical(boolean value)](#setAlignedVertical-boolean) | Obtient ou définit une valeur indiquant si les bulles sont alignées verticalement |
| [setChoiceBoxes(System.Collections.Generic.List<OmrElement> value)](#setChoiceBoxes-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement) |  |
| [setHeight(double value)](#setHeight-double) | Obtient ou définit la hauteur de la question |
| [setLeft(double value)](#setLeft-double) | Obtient ou définit la position gauche de la question |
| [setName(String value)](#setName-java.lang.String) | Définit le nom de la question |
| [setOrientation(int value)](#setOrientation-int) |  |
| [setTop(double value)](#setTop-double) | Obtient ou définit la position supérieure de la question |
| [setWidth(double value)](#setWidth-double) | Obtient ou définit la largeur de la question |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| choiceBox | [ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) |  |

### addChoiceBox(String name, int width, int height, int top, int left) {#addChoiceBox-java.lang.String-int-int-int-int}
```
public final ChoiceBoxElement addChoiceBox(String name, int width, int height, int top, int left)
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
[ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/)
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


Obtient ou définit la hauteur de la question

**Returns:**
double - La hauteur
### getLeft() {#getLeft}
```
public final double getLeft()
```


Obtient ou définit la position gauche de la question

**Returns:**
double - La gauche
### getName() {#getName}
```
public final String getName()
```


Obtient le nom de la question

**Returns:**
java.lang.String - Le nom de la question
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


Obtient ou définit la position supérieure de la question

**Returns:**
double - Le haut
### getWidth() {#getWidth}
```
public final double getWidth()
```


Obtient ou définit la largeur de la question

**Returns:**
double - La largeur
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


Obtient ou définit une valeur indiquant si les bulles sont alignées horizontalement

**Returns:**
boolean - valeur indiquant si les bulles sont alignées horizontalement
### isAlignedVertical() {#isAlignedVertical}
```
public final boolean isAlignedVertical()
```


Obtient ou définit une valeur indiquant si les bulles sont alignées verticalement

**Returns:**
boolean - valeur indiquant si les bulles sont alignées verticalement
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


Obtient ou définit une valeur indiquant si les bulles sont alignées horizontalement

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | une valeur indiquant si les bulles sont alignées horizontalement |

### setAlignedVertical(boolean value) {#setAlignedVertical-boolean}
```
public final void setAlignedVertical(boolean value)
```


Obtient ou définit une valeur indiquant si les bulles sont alignées verticalement

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | une valeur indiquant si les bulles sont alignées verticalement |

### setChoiceBoxes(System.Collections.Generic.List<OmrElement> value) {#setChoiceBoxes-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement}
```
public final void setChoiceBoxes(System.Collections.Generic.List<OmrElement> value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrElement> |  |

### setHeight(double value) {#setHeight-double}
```
public final void setHeight(double value)
```


Obtient ou définit la hauteur de la question

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | La hauteur |

### setLeft(double value) {#setLeft-double}
```
public final void setLeft(double value)
```


Obtient ou définit la position gauche de la question

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | La gauche |

### setName(String value) {#setName-java.lang.String}
```
public final void setName(String value)
```


Définit le nom de la question

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Le nom de la question |

### setOrientation(int value) {#setOrientation-int}
```
public final void setOrientation(int value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setTop(double value) {#setTop-double}
```
public final void setTop(double value)
```


Obtient ou définit la position supérieure de la question

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Le haut |

### setWidth(double value) {#setWidth-double}
```
public final void setWidth(double value)
```


Obtient ou définit la largeur de la question

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | La largeur |

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

