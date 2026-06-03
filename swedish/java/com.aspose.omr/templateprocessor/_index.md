---
title: "TemplateProcessor"
second_title: "Aspose.OMR för Java API-referens"
description: "Klass för att bearbeta mallar och bilder"
type: docs
weight: 30
url: /sv/java/com.aspose.omr/templateprocessor/
---

**Inheritance:**
java.lang.Object
```
public class TemplateProcessor
```

Klass för bearbetning av mallar och bilder.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [recalculate(RecognitionResult result)](#recalculate-com.aspose.omr.RecognitionResult) | Uppdaterar igenkänningsresultatet med finjusterade parametrar. |
| [recalculate(RecognitionResult result, int recognitionThreshold)](#recalculate-com.aspose.omr.RecognitionResult-int) | Uppdaterar igenkänningsresultatet med finjusterade parametrar. |
| [recognizeImage(BufferedImage bufferedImage)](#recognizeImage-java.awt.image.BufferedImage) | Känner igen bild |
| [recognizeImage(BufferedImage bufferedImage, int recognitionThreshold)](#recognizeImage-java.awt.image.BufferedImage-int) | Känner igen bild |
| [recognizeImage(InputStream inputStream)](#recognizeImage-java.io.InputStream) | Känner igen bild |
| [recognizeImage(InputStream inputStream, int recognitionThreshold)](#recognizeImage-java.io.InputStream-int) | Känner igen bild |
| [recognizeImage(String imagePath)](#recognizeImage-java.lang.String) | Känner igen bild |
| [recognizeImage(String imagePath, int recognitionThreshold)](#recognizeImage-java.lang.String-int) | Känner igen bild |
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


Uppdaterar igenkänningsresultatet med finjusterade parametrar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| result | [RecognitionResult](../../com.aspose.omr/recognitionresult/) | Igenkänningsresultatet att uppdatera. |

### recalculate(RecognitionResult result, int recognitionThreshold) {#recalculate-com.aspose.omr.RecognitionResult-int}
```
public final void recalculate(RecognitionResult result, int recognitionThreshold)
```


Uppdaterar igenkänningsresultatet med finjusterade parametrar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| result | [RecognitionResult](../../com.aspose.omr/recognitionresult/) | Igenkänningsresultatet att uppdatera. |
| recognitionThreshold | int | (Valfritt) Igenkänningströskeln i intervallet (0..100). Endast element som är ifyllda över tröskeln räknas som ifyllda. |

### recognizeImage(BufferedImage bufferedImage) {#recognizeImage-java.awt.image.BufferedImage}
```
public final RecognitionResult recognizeImage(BufferedImage bufferedImage)
```


Känner igen bild

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bufferedImage | java.awt.image.BufferedImage | Bild att känna igen |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(BufferedImage bufferedImage, int recognitionThreshold) {#recognizeImage-java.awt.image.BufferedImage-int}
```
public final RecognitionResult recognizeImage(BufferedImage bufferedImage, int recognitionThreshold)
```


Känner igen bild

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bufferedImage | java.awt.image.BufferedImage | Bild att känna igen |
| recognitionThreshold | int | (Valfritt) Igenkänningströskeln i intervallet (0..100). Endast element som är ifyllda över tröskeln räknas som ifyllda. |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(InputStream inputStream) {#recognizeImage-java.io.InputStream}
```
public final RecognitionResult recognizeImage(InputStream inputStream)
```


Känner igen bild

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | java.io.InputStream | Ström av bilden |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(InputStream inputStream, int recognitionThreshold) {#recognizeImage-java.io.InputStream-int}
```
public final RecognitionResult recognizeImage(InputStream inputStream, int recognitionThreshold)
```


Känner igen bild

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | java.io.InputStream | Ström av bilden |
| recognitionThreshold | int | (Valfritt) Igenkänningströskeln i intervallet (0..100). Endast element som är ifyllda över tröskeln räknas som ifyllda. |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(String imagePath) {#recognizeImage-java.lang.String}
```
public final RecognitionResult recognizeImage(String imagePath)
```


Känner igen bild

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imagePath | java.lang.String | Sökvägen till bilden som ska kännas igen |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(String imagePath, int recognitionThreshold) {#recognizeImage-java.lang.String-int}
```
public final RecognitionResult recognizeImage(String imagePath, int recognitionThreshold)
```


Känner igen bild

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imagePath | java.lang.String | Sökvägen till bilden som ska kännas igen |
| recognitionThreshold | int | (Valfritt) Igenkänningströskeln i intervallet (0..100) Endals element som är ifyllda över tröskeln räknas som ifyllda. |

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

