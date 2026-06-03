---
title: "OmrEngine"
second_title: "Référence API d'Aspose.OMR pour Java"
description: "Le moteur OMR"
type: docs
weight: 22
url: /fr/java/com.aspose.omr/omrengine/
---

**Inheritance:**
java.lang.Object
```
public class OmrEngine
```

Le moteur OMR. Gère la création du modèle et des classes de traitement d'image ainsi que des composants GUI.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [OmrEngine()](#OmrEngine) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [generateTemplate(String markupPath)](#generateTemplate-java.lang.String) | Crée le modèle (.omr) et l'image du modèle à partir du balisage texte |
| [generateTemplate(String markupPath, GlobalPageSettings settings)](#generateTemplate-java.lang.String-com.aspose.omr.GlobalPageSettings) | Crée le modèle (.omr) et l'image du modèle à partir du balisage texte |
| [generateTemplate(String markupPath, ImageCollection collection)](#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection) | Crée le modèle (.omr) et l'image du modèle à partir du balisage texte |
| [generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings)](#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection-com.aspose.omr.GlobalPageSettings) | Crée le modèle (.omr) et l'image du modèle à partir du balisage texte |
| [getClass()](#getClass) |  |
| [getTemplateProcessor(InputStream inputStream)](#getTemplateProcessor-java.io.InputStream) | Crée l'instance [TemplateProcessor](../../com.aspose.omr/templateprocessor/) qui permet de travailler avec le modèle spécifié. |
| [getTemplateProcessor(String templatePath)](#getTemplateProcessor-java.lang.String) | Crée l'instance [TemplateProcessor](../../com.aspose.omr/templateprocessor/) qui permet de travailler avec le modèle spécifié. |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateTemplate(String markupPath) {#generateTemplate-java.lang.String}
```
public final GenerationResult generateTemplate(String markupPath)
```


Crée le modèle (.omr) et l'image du modèle à partir du balisage texte

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| markupPath | java.lang.String | Chemin du fichier de balisage texte |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, GlobalPageSettings settings) {#generateTemplate-java.lang.String-com.aspose.omr.GlobalPageSettings}
```
public final GenerationResult generateTemplate(String markupPath, GlobalPageSettings settings)
```


Crée le modèle (.omr) et l'image du modèle à partir du balisage texte

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| markupPath | java.lang.String | Chemin du fichier de balisage texte |
| settings | [GlobalPageSettings](../../com.aspose.omr/globalpagesettings/) | paramètres globaux pour chaque page |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, ImageCollection collection) {#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection}
```
public final GenerationResult generateTemplate(String markupPath, ImageCollection collection)
```


Crée le modèle (.omr) et l'image du modèle à partir du balisage texte

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| markupPath | java.lang.String | Chemin du fichier de balisage texte |
| collection | [ImageCollection](../../com.aspose.omr/imagecollection/) | Collection d'images à utiliser dans la génération de ce modèle |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings) {#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection-com.aspose.omr.GlobalPageSettings}
```
public final GenerationResult generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings)
```


Crée le modèle (.omr) et l'image du modèle à partir du balisage texte

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| markupPath | java.lang.String | Chemin du fichier de balisage texte |
| collection | [ImageCollection](../../com.aspose.omr/imagecollection/) | Collection d'images à utiliser dans la génération de ce modèle |
| settings | [GlobalPageSettings](../../com.aspose.omr/globalpagesettings/) | paramètres globaux pour chaque page |

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


Crée l'instance [TemplateProcessor](../../com.aspose.omr/templateprocessor/) qui permet de travailler avec le modèle spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | flux de contenu du fichier de modèle OMR |

**Returns:**
[TemplateProcessor](../../com.aspose.omr/templateprocessor/) - The [TemplateProcessor](../../com.aspose.omr/templateprocessor/) instance
### getTemplateProcessor(String templatePath) {#getTemplateProcessor-java.lang.String}
```
public final TemplateProcessor getTemplateProcessor(String templatePath)
```


Crée l'instance [TemplateProcessor](../../com.aspose.omr/templateprocessor/) qui permet de travailler avec le modèle spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| templatePath | java.lang.String | Le chemin du fichier de modèle OMR |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

