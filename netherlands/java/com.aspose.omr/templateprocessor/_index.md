---
title: "TemplateProcessor"
second_title: "Aspose.OMR for Java API-referentie"
description: "Klasse voor het verwerken van sjablonen en afbeeldingen"
type: docs
weight: 30
url: /nl/java/com.aspose.omr/templateprocessor/
---

**Inheritance:**
java.lang.Object
```
public class TemplateProcessor
```

Klasse voor het verwerken van sjablonen en afbeeldingen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [recalculate(RecognitionResult result)](#recalculate-com.aspose.omr.RecognitionResult) | Werk de herkenningsresultaten bij met fijn afgestemde parameters. |
| [recalculate(RecognitionResult result, int recognitionThreshold)](#recalculate-com.aspose.omr.RecognitionResult-int) | Werk de herkenningsresultaten bij met fijn afgestemde parameters. |
| [recognizeImage(BufferedImage bufferedImage)](#recognizeImage-java.awt.image.BufferedImage) | Herkent afbeelding |
| [recognizeImage(BufferedImage bufferedImage, int recognitionThreshold)](#recognizeImage-java.awt.image.BufferedImage-int) | Herkent afbeelding |
| [recognizeImage(InputStream inputStream)](#recognizeImage-java.io.InputStream) | Herkent afbeelding |
| [recognizeImage(InputStream inputStream, int recognitionThreshold)](#recognizeImage-java.io.InputStream-int) | Herkent afbeelding |
| [recognizeImage(String imagePath)](#recognizeImage-java.lang.String) | Herkent afbeelding |
| [recognizeImage(String imagePath, int recognitionThreshold)](#recognizeImage-java.lang.String-int) | Herkent afbeelding |
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


Werk de herkenningsresultaten bij met fijn afgestemde parameters.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| result | [RecognitionResult](../../com.aspose.omr/recognitionresult/) | Het herkenningsresultaat om bij te werken. |

### recalculate(RecognitionResult result, int recognitionThreshold) {#recalculate-com.aspose.omr.RecognitionResult-int}
```
public final void recalculate(RecognitionResult result, int recognitionThreshold)
```


Werk de herkenningsresultaten bij met fijn afgestemde parameters.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| result | [RecognitionResult](../../com.aspose.omr/recognitionresult/) | Het herkenningsresultaat om bij te werken. |
| recognitionThreshold | int | (Optioneel) De herkenningsdrempel in bereik (0..100). Alleen elementen die boven de drempel zijn ingevuld, worden geteld als ingevuld. |

### recognizeImage(BufferedImage bufferedImage) {#recognizeImage-java.awt.image.BufferedImage}
```
public final RecognitionResult recognizeImage(BufferedImage bufferedImage)
```


Herkent afbeelding

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bufferedImage | java.awt.image.BufferedImage | Afbeelding om te herkennen |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(BufferedImage bufferedImage, int recognitionThreshold) {#recognizeImage-java.awt.image.BufferedImage-int}
```
public final RecognitionResult recognizeImage(BufferedImage bufferedImage, int recognitionThreshold)
```


Herkent afbeelding

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bufferedImage | java.awt.image.BufferedImage | Afbeelding om te herkennen |
| recognitionThreshold | int | (Optioneel) De herkenningsdrempel in bereik (0..100). Alleen elementen die boven de drempel zijn ingevuld, worden geteld als ingevuld. |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(InputStream inputStream) {#recognizeImage-java.io.InputStream}
```
public final RecognitionResult recognizeImage(InputStream inputStream)
```


Herkent afbeelding

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inputStream | java.io.InputStream | Stroom van de afbeelding |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(InputStream inputStream, int recognitionThreshold) {#recognizeImage-java.io.InputStream-int}
```
public final RecognitionResult recognizeImage(InputStream inputStream, int recognitionThreshold)
```


Herkent afbeelding

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inputStream | java.io.InputStream | Stroom van de afbeelding |
| recognitionThreshold | int | (Optioneel) De herkenningsdrempel in bereik (0..100). Alleen elementen die boven de drempel zijn ingevuld, worden geteld als ingevuld. |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(String imagePath) {#recognizeImage-java.lang.String}
```
public final RecognitionResult recognizeImage(String imagePath)
```


Herkent afbeelding

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| imagePath | java.lang.String | Het pad naar de afbeelding om te herkennen |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(String imagePath, int recognitionThreshold) {#recognizeImage-java.lang.String-int}
```
public final RecognitionResult recognizeImage(String imagePath, int recognitionThreshold)
```


Herkent afbeelding

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| imagePath | java.lang.String | Het pad naar de afbeelding om te herkennen |
| recognitionThreshold | int | (Optioneel) De herkenningsdrempel in bereik (0..100) Alleen elementen die boven de drempel zijn ingevuld, worden geteld als ingevuld. |

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

