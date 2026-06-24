---
title: "GenerationResult"
second_title: "مرجع API لـ Aspose.OMR for Java"
description: "نتيجة توليد القالب"
type: docs
weight: 14
url: /ar/java/com.aspose.omr/generationresult/
---

**Inheritance:**
java.lang.Object
```
public class GenerationResult
```

نتيجة توليد القالب. يحتوي على صورة القالب والقالب (json الذي يصف موقع العناصر على الصورة).
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [getErrorCode()](#getErrorCode) | يحصل أو يعيّن رمز الخطأ. |
| [getErrorMessage()](#getErrorMessage) | يحصل أو يعيّن الرسالة التي تصف الخطأ. |
| [getTemplate()](#getTemplate) | يحصل على سلسلة Template JSON |
| [getTemplateImage()](#getTemplateImage) | يحصل أو يعيّن Template Image المولدة |
| [getWarnings()](#getWarnings) | يحصل أو يعيّن قائمة رسائل التحذير التي تصف الأخطاء غير الحرجة التي ظهرت أثناء التوليد |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [save(String folder, String name)](#save-java.lang.String-java.lang.String) | احفظ template image والقالب في المجلد المحدد |
| [setErrorCode(int value)](#setErrorCode-int) | يحصل أو يعيّن رمز الخطأ. |
| [setErrorMessage(String value)](#setErrorMessage-java.lang.String) | يحصل أو يعيّن الرسالة التي تصف الخطأ. |
| [setTemplate(String value)](#setTemplate-java.lang.String) | يضبط سلسلة Template JSON |
| [setTemplateImage(BufferedImage value)](#setTemplateImage-java.awt.image.BufferedImage) | يحصل أو يعيّن Template Image المولدة |
| [setWarnings(List<String> value)](#setWarnings-java.util.List-java.lang.String) | يحصل أو يعيّن قائمة رسائل التحذير التي تصف الأخطاء غير الحرجة التي ظهرت أثناء التوليد |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
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


يحصل أو يعيّن رمز الخطأ. يساوي 0 إذا لم تحدث أخطاء.

**Returns:**
int - رمز الخطأ
### getErrorMessage() {#getErrorMessage}
```
public final String getErrorMessage()
```


يحصل أو يعيّن الرسالة التي تصف الخطأ. فارغ إذا لم تحدث أخطاء.

**Returns:**
java.lang.String - الرسالة التي تصف الخطأ
### getTemplate() {#getTemplate}
```
public final String getTemplate()
```


يحصل على سلسلة Template JSON

**Returns:**
java.lang.String - سلسلة Template JSON
### getTemplateImage() {#getTemplateImage}
```
public final BufferedImage getTemplateImage()
```


يحصل أو يعيّن Template Image المولدة

**Returns:**
java.awt.image.BufferedImage
### getWarnings() {#getWarnings}
```
public final List<String> getWarnings()
```


يحصل أو يعيّن قائمة رسائل التحذير التي تصف الأخطاء غير الحرجة التي ظهرت أثناء التوليد

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


احفظ template image والقالب في المجلد المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| مجلد | java.lang.String | مجلد الوجهة |
| الاسم | java.lang.String | اسم القالب |

### setErrorCode(int value) {#setErrorCode-int}
```
public final void setErrorCode(int value)
```


يحصل أو يعيّن رمز الخطأ. يساوي 0 إذا لم تحدث أخطاء.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int | رمز الخطأ |

### setErrorMessage(String value) {#setErrorMessage-java.lang.String}
```
public final void setErrorMessage(String value)
```


يحصل أو يعيّن الرسالة التي تصف الخطأ. فارغ إذا لم تحدث أخطاء.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String | الرسالة التي تصف الخطأ |

### setTemplate(String value) {#setTemplate-java.lang.String}
```
public final void setTemplate(String value)
```


يضبط سلسلة Template JSON

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String | سلسلة Template JSON |

### setTemplateImage(BufferedImage value) {#setTemplateImage-java.awt.image.BufferedImage}
```
public final void setTemplateImage(BufferedImage value)
```


يحصل أو يعيّن Template Image المولدة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.awt.image.BufferedImage |  |

### setWarnings(List<String> value) {#setWarnings-java.util.List-java.lang.String}
```
public final void setWarnings(List<String> value)
```


يحصل أو يعيّن قائمة رسائل التحذير التي تصف الأخطاء غير الحرجة التي ظهرت أثناء التوليد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.util.List<java.lang.String> |  |

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

