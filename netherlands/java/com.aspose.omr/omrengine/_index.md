---
title: "OmrEngine"
second_title: "Aspose.OMR for Java API-referentie"
description: "De OMR-engine"
type: docs
weight: 22
url: /nl/java/com.aspose.omr/omrengine/
---

**Inheritance:**
java.lang.Object
```
public class OmrEngine
```

De OMR-engine. Behandelt de creatie van de sjabloon- en beeldverwerkingsklassen en GUI-componenten.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [OmrEngine()](#OmrEngine) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [generateTemplate(String markupPath)](#generateTemplate-java.lang.String) | Maakt sjabloon (.omr) en sjabloonafbeelding op basis van tekstmarkering |
| [generateTemplate(String markupPath, GlobalPageSettings settings)](#generateTemplate-java.lang.String-com.aspose.omr.GlobalPageSettings) | Maakt sjabloon (.omr) en sjabloonafbeelding op basis van tekstmarkering |
| [generateTemplate(String markupPath, ImageCollection collection)](#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection) | Maakt sjabloon (.omr) en sjabloonafbeelding op basis van tekstmarkering |
| [generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings)](#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection-com.aspose.omr.GlobalPageSettings) | Maakt sjabloon (.omr) en sjabloonafbeelding op basis van tekstmarkering |
| [getClass()](#getClass) |  |
| [getTemplateProcessor(InputStream inputStream)](#getTemplateProcessor-java.io.InputStream) | Maakt de [TemplateProcessor](../../com.aspose.omr/templateprocessor/) instantie die werken met een opgegeven sjabloon mogelijk. |
| [getTemplateProcessor(String templatePath)](#getTemplateProcessor-java.lang.String) | Maakt de [TemplateProcessor](../../com.aspose.omr/templateprocessor/) instantie die werken met een opgegeven sjabloon mogelijk. |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateTemplate(String markupPath) {#generateTemplate-java.lang.String}
```
public final GenerationResult generateTemplate(String markupPath)
```


Maakt sjabloon (.omr) en sjabloonafbeelding op basis van tekstmarkering

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| markupPath | java.lang.String | Pad naar het tekstmarkeringbestand |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, GlobalPageSettings settings) {#generateTemplate-java.lang.String-com.aspose.omr.GlobalPageSettings}
```
public final GenerationResult generateTemplate(String markupPath, GlobalPageSettings settings)
```


Maakt sjabloon (.omr) en sjabloonafbeelding op basis van tekstmarkering

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| markupPath | java.lang.String | Pad naar het tekstmarkeringbestand |
| settings | [GlobalPageSettings](../../com.aspose.omr/globalpagesettings/) | globale instellingen voor elke pagina |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, ImageCollection collection) {#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection}
```
public final GenerationResult generateTemplate(String markupPath, ImageCollection collection)
```


Maakt sjabloon (.omr) en sjabloonafbeelding op basis van tekstmarkering

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| markupPath | java.lang.String | Pad naar het tekstmarkeringbestand |
| collection | [ImageCollection](../../com.aspose.omr/imagecollection/) | Collectie van afbeeldingen die gebruikt worden bij deze sjabloongeneratie |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings) {#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection-com.aspose.omr.GlobalPageSettings}
```
public final GenerationResult generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings)
```


Maakt sjabloon (.omr) en sjabloonafbeelding op basis van tekstmarkering

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| markupPath | java.lang.String | Pad naar het tekstmarkeringbestand |
| collection | [ImageCollection](../../com.aspose.omr/imagecollection/) | Collectie van afbeeldingen die gebruikt worden bij deze sjabloongeneratie |
| settings | [GlobalPageSettings](../../com.aspose.omr/globalpagesettings/) | globale instellingen voor elke pagina |

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


Maakt de [TemplateProcessor](../../com.aspose.omr/templateprocessor/) instantie die werken met een opgegeven sjabloon mogelijk.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inputStream | java.io.InputStream | inhoudsstroom van het OMR-sjabloonbestand |

**Returns:**
[TemplateProcessor](../../com.aspose.omr/templateprocessor/) - The [TemplateProcessor](../../com.aspose.omr/templateprocessor/) instance
### getTemplateProcessor(String templatePath) {#getTemplateProcessor-java.lang.String}
```
public final TemplateProcessor getTemplateProcessor(String templatePath)
```


Maakt de [TemplateProcessor](../../com.aspose.omr/templateprocessor/) instantie die werken met een opgegeven sjabloon mogelijk.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| templatePath | java.lang.String | Het pad naar het OMR-sjabloonbestand |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

