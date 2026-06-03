---
title: "GenerationResult"
second_title: "Aspose.OMR for Java API-referentie"
description: "Het resultaat van de sjabloongeneratie"
type: docs
weight: 14
url: /nl/java/com.aspose.omr/generationresult/
---

**Inheritance:**
java.lang.Object
```
public class GenerationResult
```

Het resultaat van de sjabloongeneratie. Bevat de sjabloonafbeelding en het sjabloon (json die de locatie van elementen op de afbeelding beschrijft).
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [getErrorCode()](#getErrorCode) | Haalt of stelt de foutcode in. |
| [getErrorMessage()](#getErrorMessage) | Haalt of stelt het bericht dat de fout beschrijft in. |
| [getTemplate()](#getTemplate) | Haalt de sjabloon JSON‑string op. |
| [getTemplateImage()](#getTemplateImage) | Haalt of stelt de gegenereerde sjabloonafbeelding in. |
| [getWarnings()](#getWarnings) | Haalt of stelt de lijst met waarschuwingsberichten in die niet‑kritieke fouten beschrijven die tijdens de generatie zijn opgetreden. |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [save(String folder, String name)](#save-java.lang.String-java.lang.String) | Sla de sjabloonafbeelding en het sjabloon op in de opgegeven map. |
| [setErrorCode(int value)](#setErrorCode-int) | Haalt of stelt de foutcode in. |
| [setErrorMessage(String value)](#setErrorMessage-java.lang.String) | Haalt of stelt het bericht dat de fout beschrijft in. |
| [setTemplate(String value)](#setTemplate-java.lang.String) | Stelt de sjabloon JSON‑string in. |
| [setTemplateImage(BufferedImage value)](#setTemplateImage-java.awt.image.BufferedImage) | Haalt of stelt de gegenereerde sjabloonafbeelding in. |
| [setWarnings(List<String> value)](#setWarnings-java.util.List-java.lang.String) | Haalt of stelt de lijst met waarschuwingsberichten in die niet‑kritieke fouten beschrijven die tijdens de generatie zijn opgetreden. |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
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


Haalt of stelt de foutcode in. Is gelijk aan 0 als er geen fouten zijn opgetreden.

**Returns:**
int - de foutcode
### getErrorMessage() {#getErrorMessage}
```
public final String getErrorMessage()
```


Haalt of stelt het bericht dat de fout beschrijft in. Leeg als er geen fouten zijn opgetreden.

**Returns:**
java.lang.String - het bericht dat de fout beschrijft
### getTemplate() {#getTemplate}
```
public final String getTemplate()
```


Haalt de sjabloon JSON‑string op.

**Returns:**
java.lang.String - de sjabloon JSON‑string
### getTemplateImage() {#getTemplateImage}
```
public final BufferedImage getTemplateImage()
```


Haalt of stelt de gegenereerde sjabloonafbeelding in.

**Returns:**
java.awt.image.BufferedImage
### getWarnings() {#getWarnings}
```
public final List<String> getWarnings()
```


Haalt of stelt de lijst met waarschuwingsberichten in die niet‑kritieke fouten beschrijven die tijdens de generatie zijn opgetreden.

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


Sla de sjabloonafbeelding en het sjabloon op in de opgegeven map.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| map | java.lang.String | Doelmap |
| naam | java.lang.String | Naam van het sjabloon |

### setErrorCode(int value) {#setErrorCode-int}
```
public final void setErrorCode(int value)
```


Haalt of stelt de foutcode in. Is gelijk aan 0 als er geen fouten zijn opgetreden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | de foutcode |

### setErrorMessage(String value) {#setErrorMessage-java.lang.String}
```
public final void setErrorMessage(String value)
```


Haalt of stelt het bericht dat de fout beschrijft in. Leeg als er geen fouten zijn opgetreden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | het bericht dat de fout beschrijft |

### setTemplate(String value) {#setTemplate-java.lang.String}
```
public final void setTemplate(String value)
```


Stelt de sjabloon JSON‑string in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | de sjabloon JSON‑string |

### setTemplateImage(BufferedImage value) {#setTemplateImage-java.awt.image.BufferedImage}
```
public final void setTemplateImage(BufferedImage value)
```


Haalt of stelt de gegenereerde sjabloonafbeelding in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.awt.image.BufferedImage |  |

### setWarnings(List<String> value) {#setWarnings-java.util.List-java.lang.String}
```
public final void setWarnings(List<String> value)
```


Haalt of stelt de lijst met waarschuwingsberichten in die niet‑kritieke fouten beschrijven die tijdens de generatie zijn opgetreden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.List<java.lang.String> |  |

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

