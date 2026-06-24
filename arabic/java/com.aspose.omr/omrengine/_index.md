---
title: "OmrEngine"
second_title: "مرجع API لـ Aspose.OMR for Java"
description: "محرك OMR"
type: docs
weight: 22
url: /ar/java/com.aspose.omr/omrengine/
---

**Inheritance:**
java.lang.Object
```
public class OmrEngine
```

محرك OMR. يتعامل مع إنشاء القالب وفئات معالجة الصور ومكونات واجهة المستخدم الرسومية.
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [OmrEngine()](#OmrEngine) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [generateTemplate(String markupPath)](#generateTemplate-java.lang.String) | ينشئ قالب (.omr) وصورة القالب بناءً على تنسيق النص |
| [generateTemplate(String markupPath, GlobalPageSettings settings)](#generateTemplate-java.lang.String-com.aspose.omr.GlobalPageSettings) | ينشئ قالب (.omr) وصورة القالب بناءً على تنسيق النص |
| [generateTemplate(String markupPath, ImageCollection collection)](#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection) | ينشئ قالب (.omr) وصورة القالب بناءً على تنسيق النص |
| [generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings)](#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection-com.aspose.omr.GlobalPageSettings) | ينشئ قالب (.omr) وصورة القالب بناءً على تنسيق النص |
| [getClass()](#getClass) |  |
| [getTemplateProcessor(InputStream inputStream)](#getTemplateProcessor-java.io.InputStream) | ينشئ مثيل [TemplateProcessor](../../com.aspose.omr/templateprocessor/) الذي يسمح بالعمل مع القالب المحدد. |
| [getTemplateProcessor(String templatePath)](#getTemplateProcessor-java.lang.String) | ينشئ مثيل [TemplateProcessor](../../com.aspose.omr/templateprocessor/) الذي يسمح بالعمل مع القالب المحدد. |
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateTemplate(String markupPath) {#generateTemplate-java.lang.String}
```
public final GenerationResult generateTemplate(String markupPath)
```


ينشئ قالب (.omr) وصورة القالب بناءً على تنسيق النص

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| markupPath | java.lang.String | مسار ملف ترميز النص |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, GlobalPageSettings settings) {#generateTemplate-java.lang.String-com.aspose.omr.GlobalPageSettings}
```
public final GenerationResult generateTemplate(String markupPath, GlobalPageSettings settings)
```


ينشئ قالب (.omr) وصورة القالب بناءً على تنسيق النص

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| markupPath | java.lang.String | مسار ملف ترميز النص |
| settings | [GlobalPageSettings](../../com.aspose.omr/globalpagesettings/) | الإعدادات العامة لكل صفحة |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, ImageCollection collection) {#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection}
```
public final GenerationResult generateTemplate(String markupPath, ImageCollection collection)
```


ينشئ قالب (.omr) وصورة القالب بناءً على تنسيق النص

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| markupPath | java.lang.String | مسار ملف ترميز النص |
| collection | [ImageCollection](../../com.aspose.omr/imagecollection/) | مجموعة الصور التي ستُستخدم في إنشاء هذا القالب |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings) {#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection-com.aspose.omr.GlobalPageSettings}
```
public final GenerationResult generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings)
```


ينشئ قالب (.omr) وصورة القالب بناءً على تنسيق النص

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| markupPath | java.lang.String | مسار ملف ترميز النص |
| collection | [ImageCollection](../../com.aspose.omr/imagecollection/) | مجموعة الصور التي ستُستخدم في إنشاء هذا القالب |
| settings | [GlobalPageSettings](../../com.aspose.omr/globalpagesettings/) | الإعدادات العامة لكل صفحة |

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


ينشئ مثيل [TemplateProcessor](../../com.aspose.omr/templateprocessor/) الذي يسمح بالعمل مع القالب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| inputStream | java.io.InputStream | تدفق المحتوى لملف قالب OMR |

**Returns:**
[TemplateProcessor](../../com.aspose.omr/templateprocessor/) - The [TemplateProcessor](../../com.aspose.omr/templateprocessor/) instance
### getTemplateProcessor(String templatePath) {#getTemplateProcessor-java.lang.String}
```
public final TemplateProcessor getTemplateProcessor(String templatePath)
```


ينشئ مثيل [TemplateProcessor](../../com.aspose.omr/templateprocessor/) الذي يسمح بالعمل مع القالب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| templatePath | java.lang.String | مسار ملف قالب OMR |

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

