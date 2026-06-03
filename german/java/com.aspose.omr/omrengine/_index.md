---
title: "OmrEngine"
second_title: "Aspose.OMR für Java API-Referenz"
description: "Die OMR-Engine"
type: docs
weight: 22
url: /de/java/com.aspose.omr/omrengine/
---

**Inheritance:**
java.lang.Object
```
public class OmrEngine
```

Die OMR-Engine. Verwaltet die Erstellung der Vorlagen- und Bildverarbeitungsklassen sowie der GUI‑Komponenten.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [OmrEngine()](#OmrEngine) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [generateTemplate(String markupPath)](#generateTemplate-java.lang.String) | Erstellt eine Vorlage (.omr) und ein Vorlagenbild basierend auf Text‑Markup |
| [generateTemplate(String markupPath, GlobalPageSettings settings)](#generateTemplate-java.lang.String-com.aspose.omr.GlobalPageSettings) | Erstellt eine Vorlage (.omr) und ein Vorlagenbild basierend auf Text‑Markup |
| [generateTemplate(String markupPath, ImageCollection collection)](#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection) | Erstellt eine Vorlage (.omr) und ein Vorlagenbild basierend auf Text‑Markup |
| [generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings)](#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection-com.aspose.omr.GlobalPageSettings) | Erstellt eine Vorlage (.omr) und ein Vorlagenbild basierend auf Text‑Markup |
| [getClass()](#getClass) |  |
| [getTemplateProcessor(InputStream inputStream)](#getTemplateProcessor-java.io.InputStream) | Erstellt die [TemplateProcessor](../../com.aspose.omr/templateprocessor/) Instanz, die die Arbeit mit der angegebenen Vorlage ermöglicht. |
| [getTemplateProcessor(String templatePath)](#getTemplateProcessor-java.lang.String) | Erstellt die [TemplateProcessor](../../com.aspose.omr/templateprocessor/) Instanz, die die Arbeit mit der angegebenen Vorlage ermöglicht. |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateTemplate(String markupPath) {#generateTemplate-java.lang.String}
```
public final GenerationResult generateTemplate(String markupPath)
```


Erstellt eine Vorlage (.omr) und ein Vorlagenbild basierend auf Text‑Markup

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| markupPath | java.lang.String | Pfad zur Text-Markup-Datei |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, GlobalPageSettings settings) {#generateTemplate-java.lang.String-com.aspose.omr.GlobalPageSettings}
```
public final GenerationResult generateTemplate(String markupPath, GlobalPageSettings settings)
```


Erstellt eine Vorlage (.omr) und ein Vorlagenbild basierend auf Text‑Markup

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| markupPath | java.lang.String | Pfad zur Text-Markup-Datei |
| settings | [GlobalPageSettings](../../com.aspose.omr/globalpagesettings/) | Globale Einstellungen für jede Seite |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, ImageCollection collection) {#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection}
```
public final GenerationResult generateTemplate(String markupPath, ImageCollection collection)
```


Erstellt eine Vorlage (.omr) und ein Vorlagenbild basierend auf Text‑Markup

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| markupPath | java.lang.String | Pfad zur Text-Markup-Datei |
| collection | [ImageCollection](../../com.aspose.omr/imagecollection/) | Sammlung von Bildern, die bei dieser Vorlagengenerierung verwendet werden |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings) {#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection-com.aspose.omr.GlobalPageSettings}
```
public final GenerationResult generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings)
```


Erstellt eine Vorlage (.omr) und ein Vorlagenbild basierend auf Text‑Markup

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| markupPath | java.lang.String | Pfad zur Text-Markup-Datei |
| collection | [ImageCollection](../../com.aspose.omr/imagecollection/) | Sammlung von Bildern, die bei dieser Vorlagengenerierung verwendet werden |
| settings | [GlobalPageSettings](../../com.aspose.omr/globalpagesettings/) | Globale Einstellungen für jede Seite |

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


Erstellt die [TemplateProcessor](../../com.aspose.omr/templateprocessor/) Instanz, die die Arbeit mit der angegebenen Vorlage ermöglicht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | java.io.InputStream | Inhaltsstrom der OMR-Vorlagendatei |

**Returns:**
[TemplateProcessor](../../com.aspose.omr/templateprocessor/) - The [TemplateProcessor](../../com.aspose.omr/templateprocessor/) instance
### getTemplateProcessor(String templatePath) {#getTemplateProcessor-java.lang.String}
```
public final TemplateProcessor getTemplateProcessor(String templatePath)
```


Erstellt die [TemplateProcessor](../../com.aspose.omr/templateprocessor/) Instanz, die die Arbeit mit der angegebenen Vorlage ermöglicht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| templatePath | java.lang.String | Der Pfad zur OMR-Vorlagendatei |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

