---
title: "OmrEngine"
second_title: "Aspose.OMR Java के लिए API रेफ़रेंस"
description: "OMR इंजन"
type: docs
weight: 22
url: /hi/java/com.aspose.omr/omrengine/
---

**Inheritance:**
java.lang.Object
```
public class OmrEngine
```

OMR इंजन। टेम्पलेट और छवि प्रसंस्करण वर्गों तथा GUI घटकों के निर्माण को संभालता है।
## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [OmrEngine()](#OmrEngine) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [generateTemplate(String markupPath)](#generateTemplate-java.lang.String) | पाठ मार्कअप के आधार पर टेम्पलेट (.omr) और टेम्पलेट छवि बनाता है |
| [generateTemplate(String markupPath, GlobalPageSettings settings)](#generateTemplate-java.lang.String-com.aspose.omr.GlobalPageSettings) | पाठ मार्कअप के आधार पर टेम्पलेट (.omr) और टेम्पलेट छवि बनाता है |
| [generateTemplate(String markupPath, ImageCollection collection)](#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection) | पाठ मार्कअप के आधार पर टेम्पलेट (.omr) और टेम्पलेट छवि बनाता है |
| [generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings)](#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection-com.aspose.omr.GlobalPageSettings) | पाठ मार्कअप के आधार पर टेम्पलेट (.omr) और टेम्पलेट छवि बनाता है |
| [getClass()](#getClass) |  |
| [getTemplateProcessor(InputStream inputStream)](#getTemplateProcessor-java.io.InputStream) | निर्धारित टेम्पलेट के साथ काम करने की अनुमति देने वाला [TemplateProcessor](../../com.aspose.omr/templateprocessor/) इंस्टेंस बनाता है। |
| [getTemplateProcessor(String templatePath)](#getTemplateProcessor-java.lang.String) | निर्धारित टेम्पलेट के साथ काम करने की अनुमति देने वाला [TemplateProcessor](../../com.aspose.omr/templateprocessor/) इंस्टेंस बनाता है। |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### OmrEngine() {#OmrEngine}
```
public OmrEngine()
```


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
### generateTemplate(String markupPath) {#generateTemplate-java.lang.String}
```
public final GenerationResult generateTemplate(String markupPath)
```


पाठ मार्कअप के आधार पर टेम्पलेट (.omr) और टेम्पलेट छवि बनाता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| markupPath | java.lang.String | टेक्स्ट मार्कअप फ़ाइल का पथ |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, GlobalPageSettings settings) {#generateTemplate-java.lang.String-com.aspose.omr.GlobalPageSettings}
```
public final GenerationResult generateTemplate(String markupPath, GlobalPageSettings settings)
```


पाठ मार्कअप के आधार पर टेम्पलेट (.omr) और टेम्पलेट छवि बनाता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| markupPath | java.lang.String | टेक्स्ट मार्कअप फ़ाइल का पथ |
| settings | [GlobalPageSettings](../../com.aspose.omr/globalpagesettings/) | प्रत्येक पृष्ठ के लिए वैश्विक सेटिंग्स |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, ImageCollection collection) {#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection}
```
public final GenerationResult generateTemplate(String markupPath, ImageCollection collection)
```


पाठ मार्कअप के आधार पर टेम्पलेट (.omr) और टेम्पलेट छवि बनाता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| markupPath | java.lang.String | टेक्स्ट मार्कअप फ़ाइल का पथ |
| collection | [ImageCollection](../../com.aspose.omr/imagecollection/) | इस टेम्पलेट जनरेशन में उपयोग की जाने वाली छवियों का संग्रह |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings) {#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection-com.aspose.omr.GlobalPageSettings}
```
public final GenerationResult generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings)
```


पाठ मार्कअप के आधार पर टेम्पलेट (.omr) और टेम्पलेट छवि बनाता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| markupPath | java.lang.String | टेक्स्ट मार्कअप फ़ाइल का पथ |
| collection | [ImageCollection](../../com.aspose.omr/imagecollection/) | इस टेम्पलेट जनरेशन में उपयोग की जाने वाली छवियों का संग्रह |
| settings | [GlobalPageSettings](../../com.aspose.omr/globalpagesettings/) | प्रत्येक पृष्ठ के लिए वैश्विक सेटिंग्स |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### getClass() {#getClass}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getTemplateProcessor(InputStream inputStream) {#getTemplateProcessor-java.io.InputStream}
```
public final TemplateProcessor getTemplateProcessor(InputStream inputStream)
```


निर्धारित टेम्पलेट के साथ काम करने की अनुमति देने वाला [TemplateProcessor](../../com.aspose.omr/templateprocessor/) इंस्टेंस बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| inputStream | java.io.InputStream | OMR टेम्पलेट फ़ाइल की कंटेंट स्ट्रीम |

**Returns:**
[TemplateProcessor](../../com.aspose.omr/templateprocessor/) - The [TemplateProcessor](../../com.aspose.omr/templateprocessor/) instance
### getTemplateProcessor(String templatePath) {#getTemplateProcessor-java.lang.String}
```
public final TemplateProcessor getTemplateProcessor(String templatePath)
```


निर्धारित टेम्पलेट के साथ काम करने की अनुमति देने वाला [TemplateProcessor](../../com.aspose.omr/templateprocessor/) इंस्टेंस बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| templatePath | java.lang.String | OMR टेम्पलेट फ़ाइल का पथ |

**Returns:**
[TemplateProcessor](../../com.aspose.omr/templateprocessor/) - The [TemplateProcessor](../../com.aspose.omr/templateprocessor/) instance
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

