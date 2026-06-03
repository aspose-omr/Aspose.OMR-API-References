---
title: "OmrPage"
second_title: "Αναφορά API του Aspose.OMR for Java"
description: "Αντιπροσωπεύει μια μοναδική σελίδα OMR"
type: docs
weight: 24
url: /el/java/com.aspose.omr/omrpage/
---

**Inheritance:**
java.lang.Object
```
public class OmrPage
```

Αντιπροσωπεύει μια μοναδική σελίδα OMR
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [OmrPage()](#OmrPage) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [OmrPage](../../com.aspose.omr/omrpage/) |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addBarcodeElement(BarcodeElement element)](#addBarcodeElement-com.aspose.omr.BarcodeElement) |  |
| [addChoiceBoxElement(String name, int width, int height, int top, int left)](#addChoiceBoxElement-java.lang.String-int-int-int-int) | Προσθέτει στοιχείο πλαισίου επιλογής στη σελίδα |
| [addClipAreaElement(String name, int width, int height, int top, int left)](#addClipAreaElement-java.lang.String-int-int-int-int) |  |
| [addGridElement(GridElement grid)](#addGridElement-com.aspose.omr.GridElement) |  |
| [addGridElement(String name, int width, int height, int top, int left)](#addGridElement-java.lang.String-int-int-int-int) |  |
| [addRefPointElement(ReferencePointElement item)](#addRefPointElement-com.aspose.omr.ReferencePointElement) |  |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [getElements()](#getElements) | Λαμβάνει ή ορίζει τη λίστα των στοιχείων στη σελίδα |
| [getHeight()](#getHeight) | Λαμβάνει ή ορίζει το ύψος της σελίδας |
| [getImageFormat()](#getImageFormat) | Λαμβάνει ή ορίζει τη μορφή αρχείου εικόνας |
| [getImageName()](#getImageName) | Λαμβάνει ή ορίζει τα δεδομένα εικόνας |
| [getRotationPointPosition()](#getRotationPointPosition) | Λαμβάνει ή ορίζει το RotationPointPosition |
| [getWidth()](#getWidth) | Λαμβάνει ή ορίζει το πλάτος της σελίδας |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [setElements(System.Collections.Generic.List<OmrElement> value)](#setElements-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement) | Λαμβάνει ή ορίζει τη λίστα των στοιχείων στη σελίδα |
| [setHeight(double value)](#setHeight-double) | Λαμβάνει ή ορίζει το ύψος της σελίδας |
| [setImageFormat(String value)](#setImageFormat-java.lang.String) | Λαμβάνει ή ορίζει τη μορφή αρχείου εικόνας |
| [setImageName(String value)](#setImageName-java.lang.String) | Λαμβάνει ή ορίζει το όνομα της εικόνας |
| [setRotationPointPosition(RotationPointPosition value)](#setRotationPointPosition-com.aspose.omr.RotationPointPosition) | Λαμβάνει ή ορίζει το RotationPointPosition |
| [setWidth(double value)](#setWidth-double) | Λαμβάνει ή ορίζει το πλάτος της σελίδας |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### OmrPage() {#OmrPage}
```
public OmrPage()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [OmrPage](../../com.aspose.omr/omrpage/)

### addBarcodeElement(BarcodeElement element) {#addBarcodeElement-com.aspose.omr.BarcodeElement}
```
public final void addBarcodeElement(BarcodeElement element)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [BarcodeElement](../../com.aspose.omr/barcodeelement/) |  |

### addChoiceBoxElement(String name, int width, int height, int top, int left) {#addChoiceBoxElement-java.lang.String-int-int-int-int}
```
public final ChoiceBoxElement addChoiceBoxElement(String name, int width, int height, int top, int left)
```


Προσθέτει στοιχείο πλαισίου επιλογής στη σελίδα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String | Όνομα στοιχείου |
| πλάτος | int | Πλάτος στοιχείου |
| ύψος | int | Ύψος στοιχείου |
| επάνω | int | Θέση επάνω στοιχείου |
| αριστερά | int | Θέση αριστερά στοιχείου |

**Returns:**
[ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) - Created choice box
### addClipAreaElement(String name, int width, int height, int top, int left) {#addClipAreaElement-java.lang.String-int-int-int-int}
```
public final ClipAreaElement addClipAreaElement(String name, int width, int height, int top, int left)
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
[ClipAreaElement](../../com.aspose.omr/clipareaelement/)
### addGridElement(GridElement grid) {#addGridElement-com.aspose.omr.GridElement}
```
public final void addGridElement(GridElement grid)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| grid | [GridElement](../../com.aspose.omr/gridelement/) |  |

### addGridElement(String name, int width, int height, int top, int left) {#addGridElement-java.lang.String-int-int-int-int}
```
public final GridElement addGridElement(String name, int width, int height, int top, int left)
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
[GridElement](../../com.aspose.omr/gridelement/)
### addRefPointElement(ReferencePointElement item) {#addRefPointElement-com.aspose.omr.ReferencePointElement}
```
public final void addRefPointElement(ReferencePointElement item)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [ReferencePointElement](../../com.aspose.omr/referencepointelement/) |  |

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


Λαμβάνει ή ορίζει τη λίστα των στοιχείων στη σελίδα

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrElement> - λίστα στοιχείων στη σελίδα
### getHeight() {#getHeight}
```
public final double getHeight()
```


Λαμβάνει ή ορίζει το ύψος της σελίδας

**Returns:**
double - ύψος σελίδας
### getImageFormat() {#getImageFormat}
```
public final String getImageFormat()
```


Λαμβάνει ή ορίζει τη μορφή αρχείου εικόνας

**Returns:**
java.lang.String - η μορφή αρχείου εικόνας
### getImageName() {#getImageName}
```
public final String getImageName()
```


Λαμβάνει ή ορίζει τα δεδομένα εικόνας

**Returns:**
java.lang.String - το όνομα της εικόνας
### getRotationPointPosition() {#getRotationPointPosition}
```
public final RotationPointPosition getRotationPointPosition()
```


Λαμβάνει ή ορίζει το RotationPointPosition

**Returns:**
[RotationPointPosition](../../com.aspose.omr/rotationpointposition/) - RotationPointPosition
### getWidth() {#getWidth}
```
public final double getWidth()
```


Λαμβάνει ή ορίζει το πλάτος της σελίδας

**Returns:**
double - πλάτος σελίδας
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


Λαμβάνει ή ορίζει τη λίστα των στοιχείων στη σελίδα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrElement> | λίστα στοιχείων στη σελίδα |

### setHeight(double value) {#setHeight-double}
```
public final void setHeight(double value)
```


Λαμβάνει ή ορίζει το ύψος της σελίδας

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | ύψος σελίδας |

### setImageFormat(String value) {#setImageFormat-java.lang.String}
```
public final void setImageFormat(String value)
```


Λαμβάνει ή ορίζει τη μορφή αρχείου εικόνας

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | η μορφή αρχείου εικόνας |

### setImageName(String value) {#setImageName-java.lang.String}
```
public final void setImageName(String value)
```


Λαμβάνει ή ορίζει το όνομα της εικόνας

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | όνομα εικόνας |

### setRotationPointPosition(RotationPointPosition value) {#setRotationPointPosition-com.aspose.omr.RotationPointPosition}
```
public final void setRotationPointPosition(RotationPointPosition value)
```


Λαμβάνει ή ορίζει το RotationPointPosition

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [RotationPointPosition](../../com.aspose.omr/rotationpointposition/) | RotationPointPosition |

### setWidth(double value) {#setWidth-double}
```
public final void setWidth(double value)
```


Λαμβάνει ή ορίζει το πλάτος της σελίδας

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | πλάτος σελίδας |

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

