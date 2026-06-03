---
title: "OmrEngine"
second_title: "Referencia de API de Aspose.OMR for Java"
description: "El motor OMR"
type: docs
weight: 22
url: /es/java/com.aspose.omr/omrengine/
---

**Inheritance:**
java.lang.Object
```
public class OmrEngine
```

El motor OMR. Maneja la creación de la plantilla y de las clases de procesamiento de imágenes y componentes GUI.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [OmrEngine()](#OmrEngine) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [generateTemplate(String markupPath)](#generateTemplate-java.lang.String) | Crea la plantilla (.omr) y la imagen de plantilla basándose en el marcado de texto |
| [generateTemplate(String markupPath, GlobalPageSettings settings)](#generateTemplate-java.lang.String-com.aspose.omr.GlobalPageSettings) | Crea la plantilla (.omr) y la imagen de plantilla basándose en el marcado de texto |
| [generateTemplate(String markupPath, ImageCollection collection)](#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection) | Crea la plantilla (.omr) y la imagen de plantilla basándose en el marcado de texto |
| [generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings)](#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection-com.aspose.omr.GlobalPageSettings) | Crea la plantilla (.omr) y la imagen de plantilla basándose en el marcado de texto |
| [getClass()](#getClass) |  |
| [getTemplateProcessor(InputStream inputStream)](#getTemplateProcessor-java.io.InputStream) | Crea la instancia de [TemplateProcessor](../../com.aspose.omr/templateprocessor/) que permite trabajar con la plantilla especificada. |
| [getTemplateProcessor(String templatePath)](#getTemplateProcessor-java.lang.String) | Crea la instancia de [TemplateProcessor](../../com.aspose.omr/templateprocessor/) que permite trabajar con la plantilla especificada. |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateTemplate(String markupPath) {#generateTemplate-java.lang.String}
```
public final GenerationResult generateTemplate(String markupPath)
```


Crea la plantilla (.omr) y la imagen de plantilla basándose en el marcado de texto

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| markupPath | java.lang.String | Ruta al archivo de marcado de texto |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, GlobalPageSettings settings) {#generateTemplate-java.lang.String-com.aspose.omr.GlobalPageSettings}
```
public final GenerationResult generateTemplate(String markupPath, GlobalPageSettings settings)
```


Crea la plantilla (.omr) y la imagen de plantilla basándose en el marcado de texto

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| markupPath | java.lang.String | Ruta al archivo de marcado de texto |
| settings | [GlobalPageSettings](../../com.aspose.omr/globalpagesettings/) | configuraciones globales para cada página |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, ImageCollection collection) {#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection}
```
public final GenerationResult generateTemplate(String markupPath, ImageCollection collection)
```


Crea la plantilla (.omr) y la imagen de plantilla basándose en el marcado de texto

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| markupPath | java.lang.String | Ruta al archivo de marcado de texto |
| collection | [ImageCollection](../../com.aspose.omr/imagecollection/) | Colección de imágenes que se usarán en la generación de esta plantilla |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings) {#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection-com.aspose.omr.GlobalPageSettings}
```
public final GenerationResult generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings)
```


Crea la plantilla (.omr) y la imagen de plantilla basándose en el marcado de texto

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| markupPath | java.lang.String | Ruta al archivo de marcado de texto |
| collection | [ImageCollection](../../com.aspose.omr/imagecollection/) | Colección de imágenes que se usarán en la generación de esta plantilla |
| settings | [GlobalPageSettings](../../com.aspose.omr/globalpagesettings/) | configuraciones globales para cada página |

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


Crea la instancia de [TemplateProcessor](../../com.aspose.omr/templateprocessor/) que permite trabajar con la plantilla especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | java.io.InputStream | flujo de contenido del archivo de plantilla OMR |

**Returns:**
[TemplateProcessor](../../com.aspose.omr/templateprocessor/) - The [TemplateProcessor](../../com.aspose.omr/templateprocessor/) instance
### getTemplateProcessor(String templatePath) {#getTemplateProcessor-java.lang.String}
```
public final TemplateProcessor getTemplateProcessor(String templatePath)
```


Crea la instancia de [TemplateProcessor](../../com.aspose.omr/templateprocessor/) que permite trabajar con la plantilla especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| templatePath | java.lang.String | La ruta al archivo de plantilla OMR |

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

