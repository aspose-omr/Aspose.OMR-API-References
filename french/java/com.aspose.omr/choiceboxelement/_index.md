---
title: "ChoiceBoxElement"
second_title: "Référence API d'Aspose.OMR pour Java"
description: "Représente la question ChoiceBox"
type: docs
weight: 11
url: /fr/java/com.aspose.omr/choiceboxelement/
---

**Inheritance:**
java.lang.Object, [com.aspose.omr.OmrElement](../../com.aspose.omr/omrelement/)
```
public class ChoiceBoxElement extends OmrElement
```

Représente la question ChoiceBox
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ChoiceBoxElement()](#ChoiceBoxElement) | Initialise une nouvelle instance de la [ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) classe |
## Champs

| Champ | Description |
| --- | --- |
| [ElementType](#ElementType) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addBubble(String name, int width, int height, int top, int left, boolean isValid)](#addBubble-java.lang.String-int-int-int-int-boolean) | Ajoute une bulle à l'intérieur de la question |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getBubbleHeight()](#getBubbleHeight) |  |
| [getBubbleWidth()](#getBubbleWidth) |  |
| [getBubbles()](#getBubbles) | Obtient ou définit la collection de bulles |
| [getClass()](#getClass) |  |
| [getHeight()](#getHeight) | Obtient ou définit la hauteur de la question |
| [getLeft()](#getLeft) | Obtient ou définit la position gauche de la question |
| [getMultipleSelectionAllowed()](#getMultipleSelectionAllowed) | Obtient ou définit une valeur indiquant si la sélection multiple est autorisée |
| [getName()](#getName) | Obtient le nom de la question |
| [getOrientation()](#getOrientation) |  |
| [getOrientationString()](#getOrientationString) | Obtient la représentation sous forme de chaîne de la propriété d'orientation |
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
| [setBubbleHeight(double value)](#setBubbleHeight-double) |  |
| [setBubbleWidth(double value)](#setBubbleWidth-double) |  |
| [setBubbles(System.Collections.Generic.List<OmrBubble> value)](#setBubbles-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrBubble) | Obtient ou définit la collection de bulles |
| [setHeight(double value)](#setHeight-double) | Obtient ou définit la hauteur de la question |
| [setLeft(double value)](#setLeft-double) | Obtient ou définit la position gauche de la question |
| [setMultipleSelectionAllowed(boolean value)](#setMultipleSelectionAllowed-boolean) | Obtient ou définit une valeur indiquant si la sélection multiple est autorisée |
| [setName(String value)](#setName-java.lang.String) | Définit le nom de la question |
| [setOrientation(int value)](#setOrientation-int) |  |
| [setTop(double value)](#setTop-double) | Obtient ou définit la position supérieure de la question |
| [setWidth(double value)](#setWidth-double) | Obtient ou définit la largeur de la question |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### ChoiceBoxElement() {#ChoiceBoxElement}
```
public ChoiceBoxElement()
```


Initialise une nouvelle instance de la [ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) classe

### ElementType {#ElementType}
```
public String ElementType
```


### addBubble(String name, int width, int height, int top, int left, boolean isValid) {#addBubble-java.lang.String-int-int-int-int-boolean}
```
public final void addBubble(String name, int width, int height, int top, int left, boolean isValid)
```


Ajoute une bulle à l'intérieur de la question

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Nom de la bulle |
| largeur | int | Largeur de la bulle |
| hauteur | int | Hauteur de la bulle |
| haut | int | Position supérieure de la bulle |
| gauche | int | Position gauche de la bulle |
| isValid | boolean | Indicateur de validité de la bulle |

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


Obtient ou définit la collection de bulles

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrBubble> - collection de bulles
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
### getMultipleSelectionAllowed() {#getMultipleSelectionAllowed}
```
public final boolean getMultipleSelectionAllowed()
```


Obtient ou définit une valeur indiquant si la sélection multiple est autorisée

**Returns:**
boolean - valeur indiquant si la sélection multiple est autorisée
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


Obtient la représentation sous forme de chaîne de la propriété d'orientation

**Returns:**
java.lang.String - représentation sous forme de chaîne de la propriété d'orientation
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

### setBubbleHeight(double value) {#setBubbleHeight-double}
```
public final void setBubbleHeight(double value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setBubbleWidth(double value) {#setBubbleWidth-double}
```
public final void setBubbleWidth(double value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setBubbles(System.Collections.Generic.List<OmrBubble> value) {#setBubbles-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrBubble}
```
public final void setBubbles(System.Collections.Generic.List<OmrBubble> value)
```


Obtient ou définit la collection de bulles

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrBubble> | collection de bulles |

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

### setMultipleSelectionAllowed(boolean value) {#setMultipleSelectionAllowed-boolean}
```
public final void setMultipleSelectionAllowed(boolean value)
```


Obtient ou définit une valeur indiquant si la sélection multiple est autorisée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | une valeur indiquant si la sélection multiple est autorisée |

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

