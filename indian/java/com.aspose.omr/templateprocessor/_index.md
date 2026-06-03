---
title: "TemplateProcessor"
second_title: "Aspose.OMR Java के लिए API रेफ़रेंस"
description: "टेम्प्लेट और छवियों को प्रोसेस करने के लिए क्लास"
type: docs
weight: 30
url: /hi/java/com.aspose.omr/templateprocessor/
---

**Inheritance:**
java.lang.Object
```
public class TemplateProcessor
```

टेम्पलेट और छवियों को प्रोसेस करने के लिए क्लास।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [recalculate(RecognitionResult result)](#recalculate-com.aspose.omr.RecognitionResult) | फ़ाइन‑ट्यून किए गए पैरामीटरों का उपयोग करके पहचान परिणाम को अपडेट करता है। |
| [recalculate(RecognitionResult result, int recognitionThreshold)](#recalculate-com.aspose.omr.RecognitionResult-int) | फ़ाइन‑ट्यून किए गए पैरामीटरों का उपयोग करके पहचान परिणाम को अपडेट करता है। |
| [recognizeImage(BufferedImage bufferedImage)](#recognizeImage-java.awt.image.BufferedImage) | छवि को पहचानता है |
| [recognizeImage(BufferedImage bufferedImage, int recognitionThreshold)](#recognizeImage-java.awt.image.BufferedImage-int) | छवि को पहचानता है |
| [recognizeImage(InputStream inputStream)](#recognizeImage-java.io.InputStream) | छवि को पहचानता है |
| [recognizeImage(InputStream inputStream, int recognitionThreshold)](#recognizeImage-java.io.InputStream-int) | छवि को पहचानता है |
| [recognizeImage(String imagePath)](#recognizeImage-java.lang.String) | छवि को पहचानता है |
| [recognizeImage(String imagePath, int recognitionThreshold)](#recognizeImage-java.lang.String-int) | छवि को पहचानता है |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
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




### recalculate(RecognitionResult result) {#recalculate-com.aspose.omr.RecognitionResult}
```
public final void recalculate(RecognitionResult result)
```


फ़ाइन‑ट्यून किए गए पैरामीटरों का उपयोग करके पहचान परिणाम को अपडेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| result | [RecognitionResult](../../com.aspose.omr/recognitionresult/) | अपडेट करने के लिए पहचान परिणाम। |

### recalculate(RecognitionResult result, int recognitionThreshold) {#recalculate-com.aspose.omr.RecognitionResult-int}
```
public final void recalculate(RecognitionResult result, int recognitionThreshold)
```


फ़ाइन‑ट्यून किए गए पैरामीटरों का उपयोग करके पहचान परिणाम को अपडेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| result | [RecognitionResult](../../com.aspose.omr/recognitionresult/) | अपडेट करने के लिए पहचान परिणाम। |
| recognitionThreshold | int | (वैकल्पिक) पहचान थ्रेशोल्ड रेंज (0..100) में। केवल उन तत्वों को जो थ्रेशोल्ड से ऊपर भरे हों, भरा हुआ माना जाएगा। |

### recognizeImage(BufferedImage bufferedImage) {#recognizeImage-java.awt.image.BufferedImage}
```
public final RecognitionResult recognizeImage(BufferedImage bufferedImage)
```


छवि को पहचानता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bufferedImage | java.awt.image.BufferedImage | पहचानने के लिए छवि |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(BufferedImage bufferedImage, int recognitionThreshold) {#recognizeImage-java.awt.image.BufferedImage-int}
```
public final RecognitionResult recognizeImage(BufferedImage bufferedImage, int recognitionThreshold)
```


छवि को पहचानता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bufferedImage | java.awt.image.BufferedImage | पहचानने के लिए छवि |
| recognitionThreshold | int | (वैकल्पिक) पहचान थ्रेशोल्ड रेंज (0..100) में। केवल उन तत्वों को जो थ्रेशोल्ड से ऊपर भरे हों, भरा हुआ माना जाएगा। |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(InputStream inputStream) {#recognizeImage-java.io.InputStream}
```
public final RecognitionResult recognizeImage(InputStream inputStream)
```


छवि को पहचानता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| inputStream | java.io.InputStream | छवि की स्ट्रीम |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(InputStream inputStream, int recognitionThreshold) {#recognizeImage-java.io.InputStream-int}
```
public final RecognitionResult recognizeImage(InputStream inputStream, int recognitionThreshold)
```


छवि को पहचानता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| inputStream | java.io.InputStream | छवि की स्ट्रीम |
| recognitionThreshold | int | (वैकल्पिक) पहचान थ्रेशोल्ड रेंज (0..100) में। केवल उन तत्वों को जो थ्रेशोल्ड से ऊपर भरे हों, भरा हुआ माना जाएगा। |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(String imagePath) {#recognizeImage-java.lang.String}
```
public final RecognitionResult recognizeImage(String imagePath)
```


छवि को पहचानता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| imagePath | java.lang.String | पहचानने के लिए छवि का पथ |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(String imagePath, int recognitionThreshold) {#recognizeImage-java.lang.String-int}
```
public final RecognitionResult recognizeImage(String imagePath, int recognitionThreshold)
```


छवि को पहचानता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| imagePath | java.lang.String | पहचानने के लिए छवि का पथ |
| recognitionThreshold | int | (वैकल्पिक) पहचान थ्रेशोल्ड रेंज (0..100) में। केवल उन तत्वों को जो थ्रेशोल्ड से ऊपर भरे हों, भरा हुआ माना जाएगा। |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
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

