---
title: "ChoiceBoxElement"
second_title: "Aspose.OMR Java के लिए API रेफ़रेंस"
description: "ChoiceBox प्रश्न का प्रतिनिधित्व करता है"
type: docs
weight: 11
url: /hi/java/com.aspose.omr/choiceboxelement/
---

**Inheritance:**
java.lang.Object, [com.aspose.omr.OmrElement](../../com.aspose.omr/omrelement/)
```
public class ChoiceBoxElement extends OmrElement
```

ChoiceBox प्रश्न का प्रतिनिधित्व करता है
## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [ChoiceBoxElement()](#ChoiceBoxElement) | नया उदाहरण प्रारंभ करता है [ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) क्लास का |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [ElementType](#ElementType) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [addBubble(String name, int width, int height, int top, int left, boolean isValid)](#addBubble-java.lang.String-int-int-int-int-boolean) | प्रश्न के भीतर बबल जोड़ता है |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getBubbleHeight()](#getBubbleHeight) |  |
| [getBubbleWidth()](#getBubbleWidth) |  |
| [getBubbles()](#getBubbles) | बबल्स संग्रह को प्राप्त करता है या सेट करता है |
| [getClass()](#getClass) |  |
| [getHeight()](#getHeight) | प्रश्न की ऊँचाई प्राप्त करता है या सेट करता है |
| [getLeft()](#getLeft) | प्रश्न की बाएँ स्थिति प्राप्त करता है या सेट करता है |
| [getMultipleSelectionAllowed()](#getMultipleSelectionAllowed) | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि कई चयन की अनुमति है या नहीं |
| [getName()](#getName) | प्रश्न का नाम प्राप्त करता है |
| [getOrientation()](#getOrientation) |  |
| [getOrientationString()](#getOrientationString) | ओरिएंटेशन प्रॉपर्टी का स्ट्रिंग प्रतिनिधित्व प्राप्त करता है |
| [getRect()](#getRect) |  |
| [getTop()](#getTop) | प्रश्न की ऊपर स्थिति प्राप्त करता है या सेट करता है |
| [getWidth()](#getWidth) | प्रश्न की चौड़ाई प्राप्त करता है या सेट करता है |
| [hashCode()](#hashCode) |  |
| [isAlignedHorizontal()](#isAlignedHorizontal) | बुलबुले क्षैतिज रूप से संरेखित हैं या नहीं दर्शाने वाला मान प्राप्त करता है या सेट करता है |
| [isAlignedVertical()](#isAlignedVertical) | बुलबुले लंबवत रूप से संरेखित हैं या नहीं दर्शाने वाला मान प्राप्त करता है या सेट करता है |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [setAlignedHorizontal(boolean value)](#setAlignedHorizontal-boolean) | बुलबुले क्षैतिज रूप से संरेखित हैं या नहीं दर्शाने वाला मान प्राप्त करता है या सेट करता है |
| [setAlignedVertical(boolean value)](#setAlignedVertical-boolean) | बुलबुले लंबवत रूप से संरेखित हैं या नहीं दर्शाने वाला मान प्राप्त करता है या सेट करता है |
| [setBubbleHeight(double value)](#setBubbleHeight-double) |  |
| [setBubbleWidth(double value)](#setBubbleWidth-double) |  |
| [setBubbles(System.Collections.Generic.List<OmrBubble> value)](#setBubbles-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrBubble) | बबल्स संग्रह को प्राप्त करता है या सेट करता है |
| [setHeight(double value)](#setHeight-double) | प्रश्न की ऊँचाई प्राप्त करता है या सेट करता है |
| [setLeft(double value)](#setLeft-double) | प्रश्न की बाएँ स्थिति प्राप्त करता है या सेट करता है |
| [setMultipleSelectionAllowed(boolean value)](#setMultipleSelectionAllowed-boolean) | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि कई चयन की अनुमति है या नहीं |
| [setName(String value)](#setName-java.lang.String) | प्रश्न का नाम सेट करता है |
| [setOrientation(int value)](#setOrientation-int) |  |
| [setTop(double value)](#setTop-double) | प्रश्न की ऊपर स्थिति प्राप्त करता है या सेट करता है |
| [setWidth(double value)](#setWidth-double) | प्रश्न की चौड़ाई प्राप्त करता है या सेट करता है |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### ChoiceBoxElement() {#ChoiceBoxElement}
```
public ChoiceBoxElement()
```


नया उदाहरण प्रारंभ करता है [ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) क्लास का

### ElementType {#ElementType}
```
public String ElementType
```


### addBubble(String name, int width, int height, int top, int left, boolean isValid) {#addBubble-java.lang.String-int-int-int-int-boolean}
```
public final void addBubble(String name, int width, int height, int top, int left, boolean isValid)
```


प्रश्न के भीतर बबल जोड़ता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String | बबल नाम |
| चौड़ाई | int | बबल चौड़ाई |
| ऊँचाई | int | बबल ऊँचाई |
| ऊपर | int | बबल शीर्ष स्थिति |
| बाएँ | int | बबल बायाँ स्थिति |
| isValid | boolean | बबल वैध फ़्लैग |

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


बबल्स संग्रह को प्राप्त करता है या सेट करता है

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrBubble> - बबल्स संग्रह
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


प्रश्न की ऊँचाई प्राप्त करता है या सेट करता है

**Returns:**
double - ऊँचाई
### getLeft() {#getLeft}
```
public final double getLeft()
```


प्रश्न की बाएँ स्थिति प्राप्त करता है या सेट करता है

**Returns:**
double - बाएँ
### getMultipleSelectionAllowed() {#getMultipleSelectionAllowed}
```
public final boolean getMultipleSelectionAllowed()
```


एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि कई चयन की अनुमति है या नहीं

**Returns:**
boolean - मान जो दर्शाता है कि कई चयन की अनुमति है या नहीं
### getName() {#getName}
```
public final String getName()
```


प्रश्न का नाम प्राप्त करता है

**Returns:**
java.lang.String - प्रश्न का नाम
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


ओरिएंटेशन प्रॉपर्टी का स्ट्रिंग प्रतिनिधित्व प्राप्त करता है

**Returns:**
java.lang.String - ओरिएंटेशन प्रॉपर्टी का स्ट्रिंग प्रतिनिधित्व
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


प्रश्न की ऊपर स्थिति प्राप्त करता है या सेट करता है

**Returns:**
double - ऊपर
### getWidth() {#getWidth}
```
public final double getWidth()
```


प्रश्न की चौड़ाई प्राप्त करता है या सेट करता है

**Returns:**
double - चौड़ाई
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


बुलबुले क्षैतिज रूप से संरेखित हैं या नहीं दर्शाने वाला मान प्राप्त करता है या सेट करता है

**Returns:**
boolean - बुलबुले क्षैतिज रूप से संरेखित हैं या नहीं दर्शाने वाला मान
### isAlignedVertical() {#isAlignedVertical}
```
public final boolean isAlignedVertical()
```


बुलबुले लंबवत रूप से संरेखित हैं या नहीं दर्शाने वाला मान प्राप्त करता है या सेट करता है

**Returns:**
boolean - बुलबुले लंबवत रूप से संरेखित हैं या नहीं दर्शाने वाला मान
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


बुलबुले क्षैतिज रूप से संरेखित हैं या नहीं दर्शाने वाला मान प्राप्त करता है या सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | बुलबुले क्षैतिज रूप से संरेखित हैं या नहीं दर्शाने वाला मान |

### setAlignedVertical(boolean value) {#setAlignedVertical-boolean}
```
public final void setAlignedVertical(boolean value)
```


बुलबुले लंबवत रूप से संरेखित हैं या नहीं दर्शाने वाला मान प्राप्त करता है या सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | बुलबुले लंबवत रूप से संरेखित हैं या नहीं दर्शाने वाला मान |

### setBubbleHeight(double value) {#setBubbleHeight-double}
```
public final void setBubbleHeight(double value)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### setBubbleWidth(double value) {#setBubbleWidth-double}
```
public final void setBubbleWidth(double value)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### setBubbles(System.Collections.Generic.List<OmrBubble> value) {#setBubbles-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrBubble}
```
public final void setBubbles(System.Collections.Generic.List<OmrBubble> value)
```


बबल्स संग्रह को प्राप्त करता है या सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrBubble> | बबल्स संग्रह |

### setHeight(double value) {#setHeight-double}
```
public final void setHeight(double value)
```


प्रश्न की ऊँचाई प्राप्त करता है या सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double | ऊँचाई |

### setLeft(double value) {#setLeft-double}
```
public final void setLeft(double value)
```


प्रश्न की बाएँ स्थिति प्राप्त करता है या सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double | बाएँ |

### setMultipleSelectionAllowed(boolean value) {#setMultipleSelectionAllowed-boolean}
```
public final void setMultipleSelectionAllowed(boolean value)
```


एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि कई चयन की अनुमति है या नहीं

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | एक मान जो दर्शाता है कि कई चयन की अनुमति है या नहीं |

### setName(String value) {#setName-java.lang.String}
```
public final void setName(String value)
```


प्रश्न का नाम सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String | प्रश्न का नाम |

### setOrientation(int value) {#setOrientation-int}
```
public final void setOrientation(int value)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setTop(double value) {#setTop-double}
```
public final void setTop(double value)
```


प्रश्न की ऊपर स्थिति प्राप्त करता है या सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double | ऊपर |

### setWidth(double value) {#setWidth-double}
```
public final void setWidth(double value)
```


प्रश्न की चौड़ाई प्राप्त करता है या सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double | चौड़ाई |

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

