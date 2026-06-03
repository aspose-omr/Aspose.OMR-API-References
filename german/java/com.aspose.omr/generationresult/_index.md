---
title: "GenerationResult"
second_title: "Aspose.OMR für Java API-Referenz"
description: "Das Ergebnis der Vorlagenerstellung"
type: docs
weight: 14
url: /de/java/com.aspose.omr/generationresult/
---

**Inheritance:**
java.lang.Object
```
public class GenerationResult
```

Das Ergebnis der Vorlagenerstellung. Enthält das Vorlagenbild und die Vorlage (json, das die Position der Elemente im Bild beschreibt).
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [getErrorCode()](#getErrorCode) | Liest oder setzt den Fehlercode. |
| [getErrorMessage()](#getErrorMessage) | Liest oder setzt die Fehlermeldung. |
| [getTemplate()](#getTemplate) | Liest die Template JSON Zeichenkette |
| [getTemplateImage()](#getTemplateImage) | Liest oder setzt das generierte Template Image |
| [getWarnings()](#getWarnings) | Liest oder setzt die Liste der Warnmeldungen, die nicht kritische Fehler beschreiben, die während der Generierung aufgetreten sind. |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [save(String folder, String name)](#save-java.lang.String-java.lang.String) | Speichere das Template Image und die Vorlage im angegebenen Ordner |
| [setErrorCode(int value)](#setErrorCode-int) | Liest oder setzt den Fehlercode. |
| [setErrorMessage(String value)](#setErrorMessage-java.lang.String) | Liest oder setzt die Fehlermeldung. |
| [setTemplate(String value)](#setTemplate-java.lang.String) | Setzt die Template JSON Zeichenkette |
| [setTemplateImage(BufferedImage value)](#setTemplateImage-java.awt.image.BufferedImage) | Liest oder setzt das generierte Template Image |
| [setWarnings(List<String> value)](#setWarnings-java.util.List-java.lang.String) | Liest oder setzt die Liste der Warnmeldungen, die nicht kritische Fehler beschreiben, die während der Generierung aufgetreten sind. |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
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


Liest oder setzt den Fehlercode. Gleich 0, wenn keine Fehler aufgetreten sind.

**Returns:**
int - der Fehlercode
### getErrorMessage() {#getErrorMessage}
```
public final String getErrorMessage()
```


Liest oder setzt die Fehlermeldung. Leer, wenn keine Fehler aufgetreten sind.

**Returns:**
java.lang.String - die Fehlermeldung
### getTemplate() {#getTemplate}
```
public final String getTemplate()
```


Liest die Template JSON Zeichenkette

**Returns:**
java.lang.String - die Template JSON Zeichenkette
### getTemplateImage() {#getTemplateImage}
```
public final BufferedImage getTemplateImage()
```


Liest oder setzt das generierte Template Image

**Returns:**
java.awt.image.BufferedImage
### getWarnings() {#getWarnings}
```
public final List<String> getWarnings()
```


Liest oder setzt die Liste der Warnmeldungen, die nicht kritische Fehler beschreiben, die während der Generierung aufgetreten sind.

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


Speichere das Template Image und die Vorlage im angegebenen Ordner

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Ordner | java.lang.String | Zielordner |
| Name | java.lang.String | Name der Vorlage |

### setErrorCode(int value) {#setErrorCode-int}
```
public final void setErrorCode(int value)
```


Liest oder setzt den Fehlercode. Gleich 0, wenn keine Fehler aufgetreten sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | der Fehlercode |

### setErrorMessage(String value) {#setErrorMessage-java.lang.String}
```
public final void setErrorMessage(String value)
```


Liest oder setzt die Fehlermeldung. Leer, wenn keine Fehler aufgetreten sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | die Fehlermeldung |

### setTemplate(String value) {#setTemplate-java.lang.String}
```
public final void setTemplate(String value)
```


Setzt die Template JSON Zeichenkette

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | die Template JSON Zeichenkette |

### setTemplateImage(BufferedImage value) {#setTemplateImage-java.awt.image.BufferedImage}
```
public final void setTemplateImage(BufferedImage value)
```


Liest oder setzt das generierte Template Image

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.awt.image.BufferedImage |  |

### setWarnings(List<String> value) {#setWarnings-java.util.List-java.lang.String}
```
public final void setWarnings(List<String> value)
```


Liest oder setzt die Liste der Warnmeldungen, die nicht kritische Fehler beschreiben, die während der Generierung aufgetreten sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.List<java.lang.String> |  |

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

