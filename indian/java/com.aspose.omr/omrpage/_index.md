---
title: "OmrPage"
second_title: "Aspose.OMR Java के लिए API रेफ़रेंस"
description: "एकल ओएमआर पेज का प्रतिनिधित्व करता है"
type: docs
weight: 24
url: /hi/java/com.aspose.omr/omrpage/
---

**Inheritance:**
java.lang.Object
```
public class OmrPage
```

एकल ओएमआर पेज का प्रतिनिधित्व करता है
## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [OmrPage()](#OmrPage) | एक नया उदाहरण प्रारंभ करता है [OmrPage](../../com.aspose.omr/omrpage/) क्लास का |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [addBarcodeElement(BarcodeElement element)](#addBarcodeElement-com.aspose.omr.BarcodeElement) |  |
| [addChoiceBoxElement(String name, int width, int height, int top, int left)](#addChoiceBoxElement-java.lang.String-int-int-int-int) | पृष्ठ पर विकल्प बॉक्स तत्व जोड़ें |
| [addClipAreaElement(String name, int width, int height, int top, int left)](#addClipAreaElement-java.lang.String-int-int-int-int) |  |
| [addGridElement(GridElement grid)](#addGridElement-com.aspose.omr.GridElement) |  |
| [addGridElement(String name, int width, int height, int top, int left)](#addGridElement-java.lang.String-int-int-int-int) |  |
| [addRefPointElement(ReferencePointElement item)](#addRefPointElement-com.aspose.omr.ReferencePointElement) |  |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [getElements()](#getElements) | पृष्ठ पर तत्वों की सूची प्राप्त करता है या सेट करता है |
| [getHeight()](#getHeight) | पृष्ठ की ऊँचाई प्राप्त करता है या सेट करता है |
| [getImageFormat()](#getImageFormat) | छवि फ़ाइल प्रारूप प्राप्त करता है या सेट करता है |
| [getImageName()](#getImageName) | छवि डेटा प्राप्त करता है या सेट करता है |
| [getRotationPointPosition()](#getRotationPointPosition) | RotationPointPosition प्राप्त करता है या सेट करता है |
| [getWidth()](#getWidth) | पृष्ठ की चौड़ाई प्राप्त करता है या सेट करता है |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [setElements(System.Collections.Generic.List<OmrElement> value)](#setElements-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement) | पृष्ठ पर तत्वों की सूची प्राप्त करता है या सेट करता है |
| [setHeight(double value)](#setHeight-double) | पृष्ठ की ऊँचाई प्राप्त करता है या सेट करता है |
| [setImageFormat(String value)](#setImageFormat-java.lang.String) | छवि फ़ाइल प्रारूप प्राप्त करता है या सेट करता है |
| [setImageName(String value)](#setImageName-java.lang.String) | छवि नाम प्राप्त करता है या सेट करता है |
| [setRotationPointPosition(RotationPointPosition value)](#setRotationPointPosition-com.aspose.omr.RotationPointPosition) | RotationPointPosition प्राप्त करता है या सेट करता है |
| [setWidth(double value)](#setWidth-double) | पृष्ठ की चौड़ाई प्राप्त करता है या सेट करता है |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### OmrPage() {#OmrPage}
```
public OmrPage()
```


एक नया उदाहरण प्रारंभ करता है [OmrPage](../../com.aspose.omr/omrpage/) क्लास का

### addBarcodeElement(BarcodeElement element) {#addBarcodeElement-com.aspose.omr.BarcodeElement}
```
public final void addBarcodeElement(BarcodeElement element)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | [BarcodeElement](../../com.aspose.omr/barcodeelement/) |  |

### addChoiceBoxElement(String name, int width, int height, int top, int left) {#addChoiceBoxElement-java.lang.String-int-int-int-int}
```
public final ChoiceBoxElement addChoiceBoxElement(String name, int width, int height, int top, int left)
```


पृष्ठ पर विकल्प बॉक्स तत्व जोड़ें

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String | तत्व नाम |
| चौड़ाई | int | तत्व चौड़ाई |
| ऊँचाई | int | तत्व ऊँचाई |
| ऊपर | int | तत्व ऊपर स्थिति |
| बाएँ | int | तत्व बाएँ स्थिति |

**Returns:**
[ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) - Created choice box
### addClipAreaElement(String name, int width, int height, int top, int left) {#addClipAreaElement-java.lang.String-int-int-int-int}
```
public final ClipAreaElement addClipAreaElement(String name, int width, int height, int top, int left)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |
| चौड़ाई | int |  |
| ऊँचाई | int |  |
| ऊपर | int |  |
| बाएँ | int |  |

**Returns:**
[ClipAreaElement](../../com.aspose.omr/clipareaelement/)
### addGridElement(GridElement grid) {#addGridElement-com.aspose.omr.GridElement}
```
public final void addGridElement(GridElement grid)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| grid | [GridElement](../../com.aspose.omr/gridelement/) |  |

### addGridElement(String name, int width, int height, int top, int left) {#addGridElement-java.lang.String-int-int-int-int}
```
public final GridElement addGridElement(String name, int width, int height, int top, int left)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |
| चौड़ाई | int |  |
| ऊँचाई | int |  |
| ऊपर | int |  |
| बाएँ | int |  |

**Returns:**
[GridElement](../../com.aspose.omr/gridelement/)
### addRefPointElement(ReferencePointElement item) {#addRefPointElement-com.aspose.omr.ReferencePointElement}
```
public final void addRefPointElement(ReferencePointElement item)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [ReferencePointElement](../../com.aspose.omr/referencepointelement/) |  |

### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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


पृष्ठ पर तत्वों की सूची प्राप्त करता है या सेट करता है

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrElement> - पृष्ठ पर तत्वों की सूची
### getHeight() {#getHeight}
```
public final double getHeight()
```


पृष्ठ की ऊँचाई प्राप्त करता है या सेट करता है

**Returns:**
double - पृष्ठ ऊँचाई
### getImageFormat() {#getImageFormat}
```
public final String getImageFormat()
```


छवि फ़ाइल प्रारूप प्राप्त करता है या सेट करता है

**Returns:**
java.lang.String - छवि फ़ाइल प्रारूप
### getImageName() {#getImageName}
```
public final String getImageName()
```


छवि डेटा प्राप्त करता है या सेट करता है

**Returns:**
java.lang.String - छवि नाम
### getRotationPointPosition() {#getRotationPointPosition}
```
public final RotationPointPosition getRotationPointPosition()
```


RotationPointPosition प्राप्त करता है या सेट करता है

**Returns:**
[RotationPointPosition](../../com.aspose.omr/rotationpointposition/) - RotationPointPosition
### getWidth() {#getWidth}
```
public final double getWidth()
```


पृष्ठ की चौड़ाई प्राप्त करता है या सेट करता है

**Returns:**
double - पृष्ठ चौड़ाई
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


पृष्ठ पर तत्वों की सूची प्राप्त करता है या सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrElement> | पृष्ठ पर तत्वों की सूची |

### setHeight(double value) {#setHeight-double}
```
public final void setHeight(double value)
```


पृष्ठ की ऊँचाई प्राप्त करता है या सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double | पृष्ठ ऊँचाई |

### setImageFormat(String value) {#setImageFormat-java.lang.String}
```
public final void setImageFormat(String value)
```


छवि फ़ाइल प्रारूप प्राप्त करता है या सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String | छवि फ़ाइल प्रारूप |

### setImageName(String value) {#setImageName-java.lang.String}
```
public final void setImageName(String value)
```


छवि नाम प्राप्त करता है या सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String | छवि नाम |

### setRotationPointPosition(RotationPointPosition value) {#setRotationPointPosition-com.aspose.omr.RotationPointPosition}
```
public final void setRotationPointPosition(RotationPointPosition value)
```


RotationPointPosition प्राप्त करता है या सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [RotationPointPosition](../../com.aspose.omr/rotationpointposition/) | RotationPointPosition |

### setWidth(double value) {#setWidth-double}
```
public final void setWidth(double value)
```


पृष्ठ की चौड़ाई प्राप्त करता है या सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double | पृष्ठ चौड़ाई |

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

