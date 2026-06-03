---
title: "GridElement"
second_title: "Αναφορά API του Aspose.OMR for Java"
description: 
type: docs
weight: 16
url: /el/java/com.aspose.omr/gridelement/
---

**Inheritance:**
java.lang.Object, [com.aspose.omr.OmrElement](../../com.aspose.omr/omrelement/)
```
public class GridElement extends OmrElement
```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [GridElement()](#GridElement) |  |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [ElementType](#ElementType) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addChoiceBox(ChoiceBoxElement choiceBox)](#addChoiceBox-com.aspose.omr.ChoiceBoxElement) |  |
| [addChoiceBox(String name, int width, int height, int top, int left)](#addChoiceBox-java.lang.String-int-int-int-int) |  |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getChoiceBoxes()](#getChoiceBoxes) |  |
| [getClass()](#getClass) |  |
| [getHeight()](#getHeight) | Λαμβάνει ή ορίζει το ύψος της ερώτησης |
| [getLeft()](#getLeft) | Λαμβάνει ή ορίζει τη θέση αριστερά της ερώτησης |
| [getName()](#getName) | Λαμβάνει το όνομα της ερώτησης |
| [getOrientation()](#getOrientation) |  |
| [getOrientationString()](#getOrientationString) |  |
| [getRect()](#getRect) |  |
| [getTop()](#getTop) | Λαμβάνει ή ορίζει τη θέση πάνω της ερώτησης |
| [getWidth()](#getWidth) | Λαμβάνει ή ορίζει το πλάτος της ερώτησης |
| [hashCode()](#hashCode) |  |
| [isAlignedHorizontal()](#isAlignedHorizontal) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν οι φούσκες είναι ευθυγραμμισμένες οριζόντια |
| [isAlignedVertical()](#isAlignedVertical) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν οι φούσκες είναι ευθυγραμμισμένες κάθετα |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [setAlignedHorizontal(boolean value)](#setAlignedHorizontal-boolean) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν οι φούσκες είναι ευθυγραμμισμένες οριζόντια |
| [setAlignedVertical(boolean value)](#setAlignedVertical-boolean) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν οι φούσκες είναι ευθυγραμμισμένες κάθετα |
| [setChoiceBoxes(System.Collections.Generic.List<OmrElement> value)](#setChoiceBoxes-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement) |  |
| [setHeight(double value)](#setHeight-double) | Λαμβάνει ή ορίζει το ύψος της ερώτησης |
| [setLeft(double value)](#setLeft-double) | Λαμβάνει ή ορίζει τη θέση αριστερά της ερώτησης |
| [setName(String value)](#setName-java.lang.String) | Ορίζει το όνομα της ερώτησης |
| [setOrientation(int value)](#setOrientation-int) |  |
| [setTop(double value)](#setTop-double) | Λαμβάνει ή ορίζει τη θέση πάνω της ερώτησης |
| [setWidth(double value)](#setWidth-double) | Λαμβάνει ή ορίζει το πλάτος της ερώτησης |
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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| choiceBox | [ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) |  |

### addChoiceBox(String name, int width, int height, int top, int left) {#addChoiceBox-java.lang.String-int-int-int-int}
```
public final ChoiceBoxElement addChoiceBox(String name, int width, int height, int top, int left)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String |  |
| πλάτος | int |  |
| ύψος | int |  |
| επάνω | int |  |
| αριστερά | int |  |

**Returns:**
[ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/)
### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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


Λαμβάνει ή ορίζει το ύψος της ερώτησης

**Returns:**
double - Το ύψος
### getLeft() {#getLeft}
```
public final double getLeft()
```


Λαμβάνει ή ορίζει τη θέση αριστερά της ερώτησης

**Returns:**
double - Το αριστερό
### getName() {#getName}
```
public final String getName()
```


Λαμβάνει το όνομα της ερώτησης

**Returns:**
java.lang.String - Το όνομα της ερώτησης
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


Λαμβάνει ή ορίζει τη θέση πάνω της ερώτησης

**Returns:**
double - Το πάνω
### getWidth() {#getWidth}
```
public final double getWidth()
```


Λαμβάνει ή ορίζει το πλάτος της ερώτησης

**Returns:**
double - Το πλάτος
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


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν οι φούσκες είναι ευθυγραμμισμένες οριζόντια

**Returns:**
boolean - τιμή που υποδεικνύει αν οι φούσκες είναι ευθυγραμμισμένες οριζόντια
### isAlignedVertical() {#isAlignedVertical}
```
public final boolean isAlignedVertical()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν οι φούσκες είναι ευθυγραμμισμένες κάθετα

**Returns:**
boolean - τιμή που υποδεικνύει αν οι φούσκες είναι ευθυγραμμισμένες κάθετα
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


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν οι φούσκες είναι ευθυγραμμισμένες οριζόντια

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | τιμή που υποδεικνύει αν οι φούσκες είναι ευθυγραμμισμένες οριζόντια |

### setAlignedVertical(boolean value) {#setAlignedVertical-boolean}
```
public final void setAlignedVertical(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν οι φούσκες είναι ευθυγραμμισμένες κάθετα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | τιμή που υποδεικνύει αν οι φούσκες είναι ευθυγραμμισμένες κάθετα |

### setChoiceBoxes(System.Collections.Generic.List<OmrElement> value) {#setChoiceBoxes-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement}
```
public final void setChoiceBoxes(System.Collections.Generic.List<OmrElement> value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrElement> |  |

### setHeight(double value) {#setHeight-double}
```
public final void setHeight(double value)
```


Λαμβάνει ή ορίζει το ύψος της ερώτησης

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Το ύψος |

### setLeft(double value) {#setLeft-double}
```
public final void setLeft(double value)
```


Λαμβάνει ή ορίζει τη θέση αριστερά της ερώτησης

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Το αριστερό |

### setName(String value) {#setName-java.lang.String}
```
public final void setName(String value)
```


Ορίζει το όνομα της ερώτησης

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Το όνομα της ερώτησης |

### setOrientation(int value) {#setOrientation-int}
```
public final void setOrientation(int value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setTop(double value) {#setTop-double}
```
public final void setTop(double value)
```


Λαμβάνει ή ορίζει τη θέση πάνω της ερώτησης

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Το πάνω |

### setWidth(double value) {#setWidth-double}
```
public final void setWidth(double value)
```


Λαμβάνει ή ορίζει το πλάτος της ερώτησης

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Το πλάτος |

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

