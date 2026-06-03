---
title: "TemplateProcessor"
second_title: "Riferimento API Aspose.OMR per Java"
description: "Classe per l'elaborazione di modelli e immagini"
type: docs
weight: 30
url: /it/java/com.aspose.omr/templateprocessor/
---

**Inheritance:**
java.lang.Object
```
public class TemplateProcessor
```

Classe per l'elaborazione di modelli e immagini.
## Metodi

| Metodo | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [recalculate(RecognitionResult result)](#recalculate-com.aspose.omr.RecognitionResult) | Aggiorna il risultato del riconoscimento usando parametri finemente regolati. |
| [recalculate(RecognitionResult result, int recognitionThreshold)](#recalculate-com.aspose.omr.RecognitionResult-int) | Aggiorna il risultato del riconoscimento usando parametri finemente regolati. |
| [recognizeImage(BufferedImage bufferedImage)](#recognizeImage-java.awt.image.BufferedImage) | Riconosce l'immagine |
| [recognizeImage(BufferedImage bufferedImage, int recognitionThreshold)](#recognizeImage-java.awt.image.BufferedImage-int) | Riconosce l'immagine |
| [recognizeImage(InputStream inputStream)](#recognizeImage-java.io.InputStream) | Riconosce l'immagine |
| [recognizeImage(InputStream inputStream, int recognitionThreshold)](#recognizeImage-java.io.InputStream-int) | Riconosce l'immagine |
| [recognizeImage(String imagePath)](#recognizeImage-java.lang.String) | Riconosce l'immagine |
| [recognizeImage(String imagePath, int recognitionThreshold)](#recognizeImage-java.lang.String-int) | Riconosce l'immagine |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
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


Aggiorna il risultato del riconoscimento usando parametri finemente regolati.

**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| result | [RecognitionResult](../../com.aspose.omr/recognitionresult/) | Il risultato del riconoscimento da aggiornare. |

### recalculate(RecognitionResult result, int recognitionThreshold) {#recalculate-com.aspose.omr.RecognitionResult-int}
```
public final void recalculate(RecognitionResult result, int recognitionThreshold)
```


Aggiorna il risultato del riconoscimento usando parametri finemente regolati.

**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| result | [RecognitionResult](../../com.aspose.omr/recognitionresult/) | Il risultato del riconoscimento da aggiornare. |
| recognitionThreshold | int | (Opzionale) La soglia di riconoscimento nell'intervallo (0..100). Solo gli elementi riempiti sopra la soglia saranno conteggiati come riempiti. |

### recognizeImage(BufferedImage bufferedImage) {#recognizeImage-java.awt.image.BufferedImage}
```
public final RecognitionResult recognizeImage(BufferedImage bufferedImage)
```


Riconosce l'immagine

**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| bufferedImage | java.awt.image.BufferedImage | Immagine da riconoscere |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(BufferedImage bufferedImage, int recognitionThreshold) {#recognizeImage-java.awt.image.BufferedImage-int}
```
public final RecognitionResult recognizeImage(BufferedImage bufferedImage, int recognitionThreshold)
```


Riconosce l'immagine

**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| bufferedImage | java.awt.image.BufferedImage | Immagine da riconoscere |
| recognitionThreshold | int | (Opzionale) La soglia di riconoscimento nell'intervallo (0..100). Solo gli elementi riempiti sopra la soglia saranno conteggiati come riempiti. |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(InputStream inputStream) {#recognizeImage-java.io.InputStream}
```
public final RecognitionResult recognizeImage(InputStream inputStream)
```


Riconosce l'immagine

**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Flusso dell'immagine |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(InputStream inputStream, int recognitionThreshold) {#recognizeImage-java.io.InputStream-int}
```
public final RecognitionResult recognizeImage(InputStream inputStream, int recognitionThreshold)
```


Riconosce l'immagine

**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Flusso dell'immagine |
| recognitionThreshold | int | (Opzionale) La soglia di riconoscimento nell'intervallo (0..100). Solo gli elementi riempiti sopra la soglia saranno conteggiati come riempiti. |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(String imagePath) {#recognizeImage-java.lang.String}
```
public final RecognitionResult recognizeImage(String imagePath)
```


Riconosce l'immagine

**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| imagePath | java.lang.String | Il percorso dell'immagine da riconoscere |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(String imagePath, int recognitionThreshold) {#recognizeImage-java.lang.String-int}
```
public final RecognitionResult recognizeImage(String imagePath, int recognitionThreshold)
```


Riconosce l'immagine

**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| imagePath | java.lang.String | Il percorso dell'immagine da riconoscere |
| recognitionThreshold | int | (Opzionale) La soglia di riconoscimento nell'intervallo (0..100). Solo gli elementi riempiti sopra la soglia saranno conteggiati come riempiti. |

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

