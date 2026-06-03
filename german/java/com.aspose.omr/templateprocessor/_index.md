---
title: "TemplateProcessor"
second_title: "Aspose.OMR für Java API-Referenz"
description: "Klasse zur Verarbeitung von Vorlagen und Bildern"
type: docs
weight: 30
url: /de/java/com.aspose.omr/templateprocessor/
---

**Inheritance:**
java.lang.Object
```
public class TemplateProcessor
```

Klasse zur Verarbeitung von Vorlagen und Bildern.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [recalculate(RecognitionResult result)](#recalculate-com.aspose.omr.RecognitionResult) | Aktualisiert das Erkennungsergebnis mithilfe fein abgestimmter Parameter. |
| [recalculate(RecognitionResult result, int recognitionThreshold)](#recalculate-com.aspose.omr.RecognitionResult-int) | Aktualisiert das Erkennungsergebnis mithilfe fein abgestimmter Parameter. |
| [recognizeImage(BufferedImage bufferedImage)](#recognizeImage-java.awt.image.BufferedImage) | Erkennt Bild |
| [recognizeImage(BufferedImage bufferedImage, int recognitionThreshold)](#recognizeImage-java.awt.image.BufferedImage-int) | Erkennt Bild |
| [recognizeImage(InputStream inputStream)](#recognizeImage-java.io.InputStream) | Erkennt Bild |
| [recognizeImage(InputStream inputStream, int recognitionThreshold)](#recognizeImage-java.io.InputStream-int) | Erkennt Bild |
| [recognizeImage(String imagePath)](#recognizeImage-java.lang.String) | Erkennt Bild |
| [recognizeImage(String imagePath, int recognitionThreshold)](#recognizeImage-java.lang.String-int) | Erkennt Bild |
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




### recalculate(RecognitionResult result) {#recalculate-com.aspose.omr.RecognitionResult}
```
public final void recalculate(RecognitionResult result)
```


Aktualisiert das Erkennungsergebnis mithilfe fein abgestimmter Parameter.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| result | [RecognitionResult](../../com.aspose.omr/recognitionresult/) | Das zu aktualisierende Erkennungsergebnis. |

### recalculate(RecognitionResult result, int recognitionThreshold) {#recalculate-com.aspose.omr.RecognitionResult-int}
```
public final void recalculate(RecognitionResult result, int recognitionThreshold)
```


Aktualisiert das Erkennungsergebnis mithilfe fein abgestimmter Parameter.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| result | [RecognitionResult](../../com.aspose.omr/recognitionresult/) | Das zu aktualisierende Erkennungsergebnis. |
| recognitionThreshold | int | (Optional) Der Erkennungsschwellenwert im Bereich (0..100). Nur Elemente, die über dem Schwellenwert liegen, werden als ausgefüllt gezählt. |

### recognizeImage(BufferedImage bufferedImage) {#recognizeImage-java.awt.image.BufferedImage}
```
public final RecognitionResult recognizeImage(BufferedImage bufferedImage)
```


Erkennt Bild

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bufferedImage | java.awt.image.BufferedImage | Bild zum Erkennen |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(BufferedImage bufferedImage, int recognitionThreshold) {#recognizeImage-java.awt.image.BufferedImage-int}
```
public final RecognitionResult recognizeImage(BufferedImage bufferedImage, int recognitionThreshold)
```


Erkennt Bild

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bufferedImage | java.awt.image.BufferedImage | Bild zum Erkennen |
| recognitionThreshold | int | (Optional) Der Erkennungsschwellenwert im Bereich (0..100). Nur Elemente, die über dem Schwellenwert liegen, werden als ausgefüllt gezählt. |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(InputStream inputStream) {#recognizeImage-java.io.InputStream}
```
public final RecognitionResult recognizeImage(InputStream inputStream)
```


Erkennt Bild

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | java.io.InputStream | Stream des Bildes |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(InputStream inputStream, int recognitionThreshold) {#recognizeImage-java.io.InputStream-int}
```
public final RecognitionResult recognizeImage(InputStream inputStream, int recognitionThreshold)
```


Erkennt Bild

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | java.io.InputStream | Stream des Bildes |
| recognitionThreshold | int | (Optional) Der Erkennungsschwellenwert im Bereich (0..100). Nur Elemente, die über dem Schwellenwert liegen, werden als ausgefüllt gezählt. |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(String imagePath) {#recognizeImage-java.lang.String}
```
public final RecognitionResult recognizeImage(String imagePath)
```


Erkennt Bild

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imagePath | java.lang.String | Der Pfad zum zu erkennenden Bild |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(String imagePath, int recognitionThreshold) {#recognizeImage-java.lang.String-int}
```
public final RecognitionResult recognizeImage(String imagePath, int recognitionThreshold)
```


Erkennt Bild

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imagePath | java.lang.String | Der Pfad zum zu erkennenden Bild |
| recognitionThreshold | int | (Optional) Der Erkennungsschwellenwert im Bereich (0..100). Nur Elemente, die über dem Schwellenwert liegen, werden als ausgefüllt gezählt. |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
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

