---
title: "GenerationResult"
second_title: "Aspose.OMR Java के लिए API रेफ़रेंस"
description: "टेम्प्लेट जनरेशन का परिणाम"
type: docs
weight: 14
url: /hi/java/com.aspose.omr/generationresult/
---

**Inheritance:**
java.lang.Object
```
public class GenerationResult
```

टेम्प्लेट जनरेशन का परिणाम। इसमें टेम्प्लेट छवि और टेम्प्लेट (json जो छवि पर तत्वों के स्थान का वर्णन करता है) शामिल हैं।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [getErrorCode()](#getErrorCode) | त्रुटि कोड को प्राप्त करता है या सेट करता है। |
| [getErrorMessage()](#getErrorMessage) | त्रुटि का वर्णन करने वाले संदेश को प्राप्त करता है या सेट करता है। |
| [getTemplate()](#getTemplate) | टेम्प्लेट JSON स्ट्रिंग प्राप्त करता है |
| [getTemplateImage()](#getTemplateImage) | जनरेट की गई टेम्प्लेट छवि को प्राप्त करता है या सेट करता है |
| [getWarnings()](#getWarnings) | जनरेशन के दौरान उत्पन्न गैर-आवश्यक त्रुटियों का वर्णन करने वाले चेतावनी संदेशों की सूची को प्राप्त करता है या सेट करता है |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [save(String folder, String name)](#save-java.lang.String-java.lang.String) | निर्दिष्ट फ़ोल्डर में टेम्प्लेट छवि और टेम्प्लेट को सहेजें |
| [setErrorCode(int value)](#setErrorCode-int) | त्रुटि कोड को प्राप्त करता है या सेट करता है। |
| [setErrorMessage(String value)](#setErrorMessage-java.lang.String) | त्रुटि का वर्णन करने वाले संदेश को प्राप्त करता है या सेट करता है। |
| [setTemplate(String value)](#setTemplate-java.lang.String) | टेम्प्लेट JSON स्ट्रिंग सेट करता है |
| [setTemplateImage(BufferedImage value)](#setTemplateImage-java.awt.image.BufferedImage) | जनरेट की गई टेम्प्लेट छवि को प्राप्त करता है या सेट करता है |
| [setWarnings(List<String> value)](#setWarnings-java.util.List-java.lang.String) | जनरेशन के दौरान उत्पन्न गैर-आवश्यक त्रुटियों का वर्णन करने वाले चेतावनी संदेशों की सूची को प्राप्त करता है या सेट करता है |
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
### getErrorCode() {#getErrorCode}
```
public final int getErrorCode()
```


त्रुटि कोड को प्राप्त करता है या सेट करता है। यदि कोई त्रुटि नहीं हुई तो 0 के बराबर होता है।

**Returns:**
int - त्रुटि कोड
### getErrorMessage() {#getErrorMessage}
```
public final String getErrorMessage()
```


त्रुटि का वर्णन करने वाले संदेश को प्राप्त करता है या सेट करता है। यदि कोई त्रुटि नहीं हुई तो खाली।

**Returns:**
java.lang.String - त्रुटि का वर्णन करने वाला संदेश
### getTemplate() {#getTemplate}
```
public final String getTemplate()
```


टेम्प्लेट JSON स्ट्रिंग प्राप्त करता है

**Returns:**
java.lang.String - टेम्प्लेट JSON स्ट्रिंग
### getTemplateImage() {#getTemplateImage}
```
public final BufferedImage getTemplateImage()
```


जनरेट की गई टेम्प्लेट छवि को प्राप्त करता है या सेट करता है

**Returns:**
java.awt.image.BufferedImage
### getWarnings() {#getWarnings}
```
public final List<String> getWarnings()
```


जनरेशन के दौरान उत्पन्न गैर-आवश्यक त्रुटियों का वर्णन करने वाले चेतावनी संदेशों की सूची को प्राप्त करता है या सेट करता है

**Returns:**
java.util.List<java.lang.String>
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




### save(String folder, String name) {#save-java.lang.String-java.lang.String}
```
public final void save(String folder, String name)
```


निर्दिष्ट फ़ोल्डर में टेम्प्लेट छवि और टेम्प्लेट को सहेजें

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ोल्डर | java.lang.String | गंतव्य फ़ोल्डर |
| नाम | java.lang.String | टेम्प्लेट का नाम |

### setErrorCode(int value) {#setErrorCode-int}
```
public final void setErrorCode(int value)
```


त्रुटि कोड को प्राप्त करता है या सेट करता है। यदि कोई त्रुटि नहीं हुई तो 0 के बराबर होता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | त्रुटि कोड |

### setErrorMessage(String value) {#setErrorMessage-java.lang.String}
```
public final void setErrorMessage(String value)
```


त्रुटि का वर्णन करने वाले संदेश को प्राप्त करता है या सेट करता है। यदि कोई त्रुटि नहीं हुई तो खाली।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String | त्रुटि का वर्णन करने वाला संदेश |

### setTemplate(String value) {#setTemplate-java.lang.String}
```
public final void setTemplate(String value)
```


टेम्प्लेट JSON स्ट्रिंग सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String | टेम्प्लेट JSON स्ट्रिंग |

### setTemplateImage(BufferedImage value) {#setTemplateImage-java.awt.image.BufferedImage}
```
public final void setTemplateImage(BufferedImage value)
```


जनरेट की गई टेम्प्लेट छवि को प्राप्त करता है या सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.awt.image.BufferedImage |  |

### setWarnings(List<String> value) {#setWarnings-java.util.List-java.lang.String}
```
public final void setWarnings(List<String> value)
```


जनरेशन के दौरान उत्पन्न गैर-आवश्यक त्रुटियों का वर्णन करने वाले चेतावनी संदेशों की सूची को प्राप्त करता है या सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.util.List<java.lang.String> |  |

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

