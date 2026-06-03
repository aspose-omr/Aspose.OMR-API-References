---
title: "OmrEngine"
second_title: "Aspose.OMR för Java API-referens"
description: "OMR-motorn"
type: docs
weight: 22
url: /sv/java/com.aspose.omr/omrengine/
---

**Inheritance:**
java.lang.Object
```
public class OmrEngine
```

OMR-motorn. Hanterar skapandet av mall- och bildbehandlingsklasser samt GUI-komponenter.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [OmrEngine()](#OmrEngine) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [generateTemplate(String markupPath)](#generateTemplate-java.lang.String) | Skapar mall (.omr) och mallbild baserat på textmarkering |
| [generateTemplate(String markupPath, GlobalPageSettings settings)](#generateTemplate-java.lang.String-com.aspose.omr.GlobalPageSettings) | Skapar mall (.omr) och mallbild baserat på textmarkering |
| [generateTemplate(String markupPath, ImageCollection collection)](#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection) | Skapar mall (.omr) och mallbild baserat på textmarkering |
| [generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings)](#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection-com.aspose.omr.GlobalPageSettings) | Skapar mall (.omr) och mallbild baserat på textmarkering |
| [getClass()](#getClass) |  |
| [getTemplateProcessor(InputStream inputStream)](#getTemplateProcessor-java.io.InputStream) | Skapar [TemplateProcessor](../../com.aspose.omr/templateprocessor/)‑instansen som möjliggör arbete med angiven mall. |
| [getTemplateProcessor(String templatePath)](#getTemplateProcessor-java.lang.String) | Skapar [TemplateProcessor](../../com.aspose.omr/templateprocessor/)‑instansen som möjliggör arbete med angiven mall. |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateTemplate(String markupPath) {#generateTemplate-java.lang.String}
```
public final GenerationResult generateTemplate(String markupPath)
```


Skapar mall (.omr) och mallbild baserat på textmarkering

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| markupPath | java.lang.String | Sökväg till textmarkeringsfilen |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, GlobalPageSettings settings) {#generateTemplate-java.lang.String-com.aspose.omr.GlobalPageSettings}
```
public final GenerationResult generateTemplate(String markupPath, GlobalPageSettings settings)
```


Skapar mall (.omr) och mallbild baserat på textmarkering

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| markupPath | java.lang.String | Sökväg till textmarkeringsfilen |
| settings | [GlobalPageSettings](../../com.aspose.omr/globalpagesettings/) | globala inställningar för varje sida |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, ImageCollection collection) {#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection}
```
public final GenerationResult generateTemplate(String markupPath, ImageCollection collection)
```


Skapar mall (.omr) och mallbild baserat på textmarkering

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| markupPath | java.lang.String | Sökväg till textmarkeringsfilen |
| collection | [ImageCollection](../../com.aspose.omr/imagecollection/) | Samling av bilder som ska användas i denna mallgenerering |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings) {#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection-com.aspose.omr.GlobalPageSettings}
```
public final GenerationResult generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings)
```


Skapar mall (.omr) och mallbild baserat på textmarkering

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| markupPath | java.lang.String | Sökväg till textmarkeringsfilen |
| collection | [ImageCollection](../../com.aspose.omr/imagecollection/) | Samling av bilder som ska användas i denna mallgenerering |
| settings | [GlobalPageSettings](../../com.aspose.omr/globalpagesettings/) | globala inställningar för varje sida |

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


Skapar [TemplateProcessor](../../com.aspose.omr/templateprocessor/)‑instansen som möjliggör arbete med angiven mall.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | java.io.InputStream | innehållsström för OMR‑mallfilen |

**Returns:**
[TemplateProcessor](../../com.aspose.omr/templateprocessor/) - The [TemplateProcessor](../../com.aspose.omr/templateprocessor/) instance
### getTemplateProcessor(String templatePath) {#getTemplateProcessor-java.lang.String}
```
public final TemplateProcessor getTemplateProcessor(String templatePath)
```


Skapar [TemplateProcessor](../../com.aspose.omr/templateprocessor/)‑instansen som möjliggör arbete med angiven mall.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| templatePath | java.lang.String | Sökvägen till OMR‑mallfilen |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

