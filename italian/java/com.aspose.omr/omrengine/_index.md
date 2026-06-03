---
title: "OmrEngine"
second_title: "Riferimento API Aspose.OMR per Java"
description: "Il motore OMR"
type: docs
weight: 22
url: /it/java/com.aspose.omr/omrengine/
---

**Inheritance:**
java.lang.Object
```
public class OmrEngine
```

Il motore OMR. Gestisce la creazione del modello e delle classi di elaborazione delle immagini e dei componenti GUI.
## Costruttori

| Costruttore | Description |
| --- | --- |
| [OmrEngine()](#OmrEngine) |  |
## Metodi

| Metodo | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [generateTemplate(String markupPath)](#generateTemplate-java.lang.String) | Crea il modello (.omr) e l'immagine del modello basati sul markup del testo |
| [generateTemplate(String markupPath, GlobalPageSettings settings)](#generateTemplate-java.lang.String-com.aspose.omr.GlobalPageSettings) | Crea il modello (.omr) e l'immagine del modello basati sul markup del testo |
| [generateTemplate(String markupPath, ImageCollection collection)](#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection) | Crea il modello (.omr) e l'immagine del modello basati sul markup del testo |
| [generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings)](#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection-com.aspose.omr.GlobalPageSettings) | Crea il modello (.omr) e l'immagine del modello basati sul markup del testo |
| [getClass()](#getClass) |  |
| [getTemplateProcessor(InputStream inputStream)](#getTemplateProcessor-java.io.InputStream) | Crea l'istanza [TemplateProcessor](../../com.aspose.omr/templateprocessor/) che consente di lavorare con il modello specificato. |
| [getTemplateProcessor(String templatePath)](#getTemplateProcessor-java.lang.String) | Crea l'istanza [TemplateProcessor](../../com.aspose.omr/templateprocessor/) che consente di lavorare con il modello specificato. |
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
| Parametro | Tipo | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateTemplate(String markupPath) {#generateTemplate-java.lang.String}
```
public final GenerationResult generateTemplate(String markupPath)
```


Crea il modello (.omr) e l'immagine del modello basati sul markup del testo

**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| markupPath | java.lang.String | Percorso del file di markup del testo |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, GlobalPageSettings settings) {#generateTemplate-java.lang.String-com.aspose.omr.GlobalPageSettings}
```
public final GenerationResult generateTemplate(String markupPath, GlobalPageSettings settings)
```


Crea il modello (.omr) e l'immagine del modello basati sul markup del testo

**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| markupPath | java.lang.String | Percorso del file di markup del testo |
| settings | [GlobalPageSettings](../../com.aspose.omr/globalpagesettings/) | impostazioni globali per ogni pagina |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, ImageCollection collection) {#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection}
```
public final GenerationResult generateTemplate(String markupPath, ImageCollection collection)
```


Crea il modello (.omr) e l'immagine del modello basati sul markup del testo

**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| markupPath | java.lang.String | Percorso del file di markup del testo |
| collection | [ImageCollection](../../com.aspose.omr/imagecollection/) | Collezione di immagini da utilizzare in questa generazione del modello |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings) {#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection-com.aspose.omr.GlobalPageSettings}
```
public final GenerationResult generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings)
```


Crea il modello (.omr) e l'immagine del modello basati sul markup del testo

**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| markupPath | java.lang.String | Percorso del file di markup del testo |
| collection | [ImageCollection](../../com.aspose.omr/imagecollection/) | Collezione di immagini da utilizzare in questa generazione del modello |
| settings | [GlobalPageSettings](../../com.aspose.omr/globalpagesettings/) | impostazioni globali per ogni pagina |

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


Crea l'istanza [TemplateProcessor](../../com.aspose.omr/templateprocessor/) che consente di lavorare con il modello specificato.

**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | flusso di contenuto del file modello OMR |

**Returns:**
[TemplateProcessor](../../com.aspose.omr/templateprocessor/) - The [TemplateProcessor](../../com.aspose.omr/templateprocessor/) instance
### getTemplateProcessor(String templatePath) {#getTemplateProcessor-java.lang.String}
```
public final TemplateProcessor getTemplateProcessor(String templatePath)
```


Crea l'istanza [TemplateProcessor](../../com.aspose.omr/templateprocessor/) che consente di lavorare con il modello specificato.

**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| templatePath | java.lang.String | Il percorso del file modello OMR |

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
| Parametro | Tipo | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

