---
title: "OmrEngine"
second_title: "Referensi API Aspose.OMR for Java"
description: "Mesin OMR"
type: docs
weight: 22
url: /id/java/com.aspose.omr/omrengine/
---

**Inheritance:**
java.lang.Object
```
public class OmrEngine
```

Mesin OMR. Menangani pembuatan kelas templat dan pemrosesan gambar serta komponen GUI.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [OmrEngine()](#OmrEngine) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [generateTemplate(String markupPath)](#generateTemplate-java.lang.String) | Membuat templat (.omr) dan gambar templat berdasarkan markup teks |
| [generateTemplate(String markupPath, GlobalPageSettings settings)](#generateTemplate-java.lang.String-com.aspose.omr.GlobalPageSettings) | Membuat templat (.omr) dan gambar templat berdasarkan markup teks |
| [generateTemplate(String markupPath, ImageCollection collection)](#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection) | Membuat templat (.omr) dan gambar templat berdasarkan markup teks |
| [generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings)](#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection-com.aspose.omr.GlobalPageSettings) | Membuat templat (.omr) dan gambar templat berdasarkan markup teks |
| [getClass()](#getClass) |  |
| [getTemplateProcessor(InputStream inputStream)](#getTemplateProcessor-java.io.InputStream) | Membuat instance [TemplateProcessor](../../com.aspose.omr/templateprocessor/) yang memungkinkan bekerja dengan templat yang ditentukan. |
| [getTemplateProcessor(String templatePath)](#getTemplateProcessor-java.lang.String) | Membuat instance [TemplateProcessor](../../com.aspose.omr/templateprocessor/) yang memungkinkan bekerja dengan templat yang ditentukan. |
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateTemplate(String markupPath) {#generateTemplate-java.lang.String}
```
public final GenerationResult generateTemplate(String markupPath)
```


Membuat templat (.omr) dan gambar templat berdasarkan markup teks

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| markupPath | java.lang.String | Jalur ke file markup teks |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, GlobalPageSettings settings) {#generateTemplate-java.lang.String-com.aspose.omr.GlobalPageSettings}
```
public final GenerationResult generateTemplate(String markupPath, GlobalPageSettings settings)
```


Membuat templat (.omr) dan gambar templat berdasarkan markup teks

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| markupPath | java.lang.String | Jalur ke file markup teks |
| settings | [GlobalPageSettings](../../com.aspose.omr/globalpagesettings/) | pengaturan global untuk setiap halaman |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, ImageCollection collection) {#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection}
```
public final GenerationResult generateTemplate(String markupPath, ImageCollection collection)
```


Membuat templat (.omr) dan gambar templat berdasarkan markup teks

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| markupPath | java.lang.String | Jalur ke file markup teks |
| collection | [ImageCollection](../../com.aspose.omr/imagecollection/) | Koleksi gambar yang akan digunakan dalam pembuatan templat ini |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings) {#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection-com.aspose.omr.GlobalPageSettings}
```
public final GenerationResult generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings)
```


Membuat templat (.omr) dan gambar templat berdasarkan markup teks

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| markupPath | java.lang.String | Jalur ke file markup teks |
| collection | [ImageCollection](../../com.aspose.omr/imagecollection/) | Koleksi gambar yang akan digunakan dalam pembuatan templat ini |
| settings | [GlobalPageSettings](../../com.aspose.omr/globalpagesettings/) | pengaturan global untuk setiap halaman |

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


Membuat instance [TemplateProcessor](../../com.aspose.omr/templateprocessor/) yang memungkinkan bekerja dengan templat yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | java.io.InputStream | stream konten file templat OMR |

**Returns:**
[TemplateProcessor](../../com.aspose.omr/templateprocessor/) - The [TemplateProcessor](../../com.aspose.omr/templateprocessor/) instance
### getTemplateProcessor(String templatePath) {#getTemplateProcessor-java.lang.String}
```
public final TemplateProcessor getTemplateProcessor(String templatePath)
```


Membuat instance [TemplateProcessor](../../com.aspose.omr/templateprocessor/) yang memungkinkan bekerja dengan templat yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| templatePath | java.lang.String | Jalur ke file templat OMR |

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

