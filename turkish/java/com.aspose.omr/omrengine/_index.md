---
title: "OmrEngine"
second_title: "Aspose.OMR for Java API Referansı"
description: "OMR motoru"
type: docs
weight: 22
url: /tr/java/com.aspose.omr/omrengine/
---

**Inheritance:**
java.lang.Object
```
public class OmrEngine
```

OMR motoru. Şablon ve görüntü işleme sınıflarının ve GUI bileşenlerinin oluşturulmasını yönetir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [OmrEngine()](#OmrEngine) |  |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [generateTemplate(String markupPath)](#generateTemplate-java.lang.String) | Metin işaretlemesine dayanarak şablon (.omr) ve şablon görüntüsü oluşturur |
| [generateTemplate(String markupPath, GlobalPageSettings settings)](#generateTemplate-java.lang.String-com.aspose.omr.GlobalPageSettings) | Metin işaretlemesine dayanarak şablon (.omr) ve şablon görüntüsü oluşturur |
| [generateTemplate(String markupPath, ImageCollection collection)](#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection) | Metin işaretlemesine dayanarak şablon (.omr) ve şablon görüntüsü oluşturur |
| [generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings)](#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection-com.aspose.omr.GlobalPageSettings) | Metin işaretlemesine dayanarak şablon (.omr) ve şablon görüntüsü oluşturur |
| [getClass()](#getClass) |  |
| [getTemplateProcessor(InputStream inputStream)](#getTemplateProcessor-java.io.InputStream) | Belirtilen şablonla çalışmaya izin veren [TemplateProcessor](../../com.aspose.omr/templateprocessor/) örneğini oluşturur. |
| [getTemplateProcessor(String templatePath)](#getTemplateProcessor-java.lang.String) | Belirtilen şablonla çalışmaya izin veren [TemplateProcessor](../../com.aspose.omr/templateprocessor/) örneğini oluşturur. |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateTemplate(String markupPath) {#generateTemplate-java.lang.String}
```
public final GenerationResult generateTemplate(String markupPath)
```


Metin işaretlemesine dayanarak şablon (.omr) ve şablon görüntüsü oluşturur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| markupPath | java.lang.String | Metin işaretleme dosyasının yolu |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, GlobalPageSettings settings) {#generateTemplate-java.lang.String-com.aspose.omr.GlobalPageSettings}
```
public final GenerationResult generateTemplate(String markupPath, GlobalPageSettings settings)
```


Metin işaretlemesine dayanarak şablon (.omr) ve şablon görüntüsü oluşturur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| markupPath | java.lang.String | Metin işaretleme dosyasının yolu |
| settings | [GlobalPageSettings](../../com.aspose.omr/globalpagesettings/) | her sayfa için genel ayarlar |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, ImageCollection collection) {#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection}
```
public final GenerationResult generateTemplate(String markupPath, ImageCollection collection)
```


Metin işaretlemesine dayanarak şablon (.omr) ve şablon görüntüsü oluşturur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| markupPath | java.lang.String | Metin işaretleme dosyasının yolu |
| collection | [ImageCollection](../../com.aspose.omr/imagecollection/) | Bu şablon oluşturulmasında kullanılacak görüntülerin koleksiyonu |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings) {#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection-com.aspose.omr.GlobalPageSettings}
```
public final GenerationResult generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings)
```


Metin işaretlemesine dayanarak şablon (.omr) ve şablon görüntüsü oluşturur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| markupPath | java.lang.String | Metin işaretleme dosyasının yolu |
| collection | [ImageCollection](../../com.aspose.omr/imagecollection/) | Bu şablon oluşturulmasında kullanılacak görüntülerin koleksiyonu |
| settings | [GlobalPageSettings](../../com.aspose.omr/globalpagesettings/) | her sayfa için genel ayarlar |

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


Belirtilen şablonla çalışmaya izin veren [TemplateProcessor](../../com.aspose.omr/templateprocessor/) örneğini oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | java.io.InputStream | OMR şablon dosyasının içerik akışı |

**Returns:**
[TemplateProcessor](../../com.aspose.omr/templateprocessor/) - The [TemplateProcessor](../../com.aspose.omr/templateprocessor/) instance
### getTemplateProcessor(String templatePath) {#getTemplateProcessor-java.lang.String}
```
public final TemplateProcessor getTemplateProcessor(String templatePath)
```


Belirtilen şablonla çalışmaya izin veren [TemplateProcessor](../../com.aspose.omr/templateprocessor/) örneğini oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| templatePath | java.lang.String | OMR şablon dosyasının yolu |

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

