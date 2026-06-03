---
title: "GenerationResult"
second_title: "Aspose.OMR för Java API-referens"
description: "Resultatet av mallgenereringen"
type: docs
weight: 14
url: /sv/java/com.aspose.omr/generationresult/
---

**Inheritance:**
java.lang.Object
```
public class GenerationResult
```

Resultatet av mallgenereringen. Innehåller mallbilden och mallen (json som beskriver elementens placering på bilden).
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [getErrorCode()](#getErrorCode) | Hämtar eller anger felkoden. |
| [getErrorMessage()](#getErrorMessage) | Hämtar eller anger meddelandet som beskriver felet. |
| [getTemplate()](#getTemplate) | Hämtar mallens JSON-sträng |
| [getTemplateImage()](#getTemplateImage) | Hämtar eller anger den genererade mallbilden |
| [getWarnings()](#getWarnings) | Hämtar eller anger en lista med varningsmeddelanden som beskriver icke-kritiska fel som uppstod under genereringen |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [save(String folder, String name)](#save-java.lang.String-java.lang.String) | Spara mallbilden och mallen till den angivna mappen |
| [setErrorCode(int value)](#setErrorCode-int) | Hämtar eller anger felkoden. |
| [setErrorMessage(String value)](#setErrorMessage-java.lang.String) | Hämtar eller anger meddelandet som beskriver felet. |
| [setTemplate(String value)](#setTemplate-java.lang.String) | Anger mallens JSON-sträng |
| [setTemplateImage(BufferedImage value)](#setTemplateImage-java.awt.image.BufferedImage) | Hämtar eller anger den genererade mallbilden |
| [setWarnings(List<String> value)](#setWarnings-java.util.List-java.lang.String) | Hämtar eller anger en lista med varningsmeddelanden som beskriver icke-kritiska fel som uppstod under genereringen |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
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


Hämtar eller anger felkoden. Är 0 om inga fel inträffade.

**Returns:**
int – felkoden
### getErrorMessage() {#getErrorMessage}
```
public final String getErrorMessage()
```


Hämtar eller anger meddelandet som beskriver felet. Tomt om inga fel inträffade.

**Returns:**
java.lang.String – meddelandet som beskriver felet
### getTemplate() {#getTemplate}
```
public final String getTemplate()
```


Hämtar mallens JSON-sträng

**Returns:**
java.lang.String – mallens JSON-sträng
### getTemplateImage() {#getTemplateImage}
```
public final BufferedImage getTemplateImage()
```


Hämtar eller anger den genererade mallbilden

**Returns:**
java.awt.image.BufferedImage
### getWarnings() {#getWarnings}
```
public final List<String> getWarnings()
```


Hämtar eller anger en lista med varningsmeddelanden som beskriver icke-kritiska fel som uppstod under genereringen

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


Spara mallbilden och mallen till den angivna mappen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mapp | java.lang.String | Målmapp |
| namn | java.lang.String | Mallens namn |

### setErrorCode(int value) {#setErrorCode-int}
```
public final void setErrorCode(int value)
```


Hämtar eller anger felkoden. Är 0 om inga fel inträffade.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | felkoden |

### setErrorMessage(String value) {#setErrorMessage-java.lang.String}
```
public final void setErrorMessage(String value)
```


Hämtar eller anger meddelandet som beskriver felet. Tomt om inga fel inträffade.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | meddelandet som beskriver felet |

### setTemplate(String value) {#setTemplate-java.lang.String}
```
public final void setTemplate(String value)
```


Anger mallens JSON-sträng

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | mallens JSON-sträng |

### setTemplateImage(BufferedImage value) {#setTemplateImage-java.awt.image.BufferedImage}
```
public final void setTemplateImage(BufferedImage value)
```


Hämtar eller anger den genererade mallbilden

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.awt.image.BufferedImage |  |

### setWarnings(List<String> value) {#setWarnings-java.util.List-java.lang.String}
```
public final void setWarnings(List<String> value)
```


Hämtar eller anger en lista med varningsmeddelanden som beskriver icke-kritiska fel som uppstod under genereringen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.List<java.lang.String> |  |

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

