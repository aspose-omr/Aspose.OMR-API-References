---
title: "TemplateProcessor"
second_title: "Referencia de API de Aspose.OMR for Java"
description: "Clase para procesar plantillas e imágenes"
type: docs
weight: 30
url: /es/java/com.aspose.omr/templateprocessor/
---

**Inheritance:**
java.lang.Object
```
public class TemplateProcessor
```

Clase para procesar plantillas e imágenes.
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [recalculate(RecognitionResult result)](#recalculate-com.aspose.omr.RecognitionResult) | Actualiza el resultado del reconocimiento usando parámetros afinados. |
| [recalculate(RecognitionResult result, int recognitionThreshold)](#recalculate-com.aspose.omr.RecognitionResult-int) | Actualiza el resultado del reconocimiento usando parámetros afinados. |
| [recognizeImage(BufferedImage bufferedImage)](#recognizeImage-java.awt.image.BufferedImage) | Reconoce la imagen |
| [recognizeImage(BufferedImage bufferedImage, int recognitionThreshold)](#recognizeImage-java.awt.image.BufferedImage-int) | Reconoce la imagen |
| [recognizeImage(InputStream inputStream)](#recognizeImage-java.io.InputStream) | Reconoce la imagen |
| [recognizeImage(InputStream inputStream, int recognitionThreshold)](#recognizeImage-java.io.InputStream-int) | Reconoce la imagen |
| [recognizeImage(String imagePath)](#recognizeImage-java.lang.String) | Reconoce la imagen |
| [recognizeImage(String imagePath, int recognitionThreshold)](#recognizeImage-java.lang.String-int) | Reconoce la imagen |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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


Actualiza el resultado del reconocimiento usando parámetros afinados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| result | [RecognitionResult](../../com.aspose.omr/recognitionresult/) | El resultado del reconocimiento a actualizar. |

### recalculate(RecognitionResult result, int recognitionThreshold) {#recalculate-com.aspose.omr.RecognitionResult-int}
```
public final void recalculate(RecognitionResult result, int recognitionThreshold)
```


Actualiza el resultado del reconocimiento usando parámetros afinados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| result | [RecognitionResult](../../com.aspose.omr/recognitionresult/) | El resultado del reconocimiento a actualizar. |
| recognitionThreshold | int | (Opcional) El umbral de reconocimiento en el rango (0..100). Sólo los elementos rellenados por encima del umbral se contarán como rellenados. |

### recognizeImage(BufferedImage bufferedImage) {#recognizeImage-java.awt.image.BufferedImage}
```
public final RecognitionResult recognizeImage(BufferedImage bufferedImage)
```


Reconoce la imagen

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bufferedImage | java.awt.image.BufferedImage | Imagen a reconocer |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(BufferedImage bufferedImage, int recognitionThreshold) {#recognizeImage-java.awt.image.BufferedImage-int}
```
public final RecognitionResult recognizeImage(BufferedImage bufferedImage, int recognitionThreshold)
```


Reconoce la imagen

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bufferedImage | java.awt.image.BufferedImage | Imagen a reconocer |
| recognitionThreshold | int | (Opcional) El umbral de reconocimiento en el rango (0..100). Sólo los elementos rellenados por encima del umbral se contarán como rellenados. |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(InputStream inputStream) {#recognizeImage-java.io.InputStream}
```
public final RecognitionResult recognizeImage(InputStream inputStream)
```


Reconoce la imagen

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | java.io.InputStream | Flujo de la imagen |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(InputStream inputStream, int recognitionThreshold) {#recognizeImage-java.io.InputStream-int}
```
public final RecognitionResult recognizeImage(InputStream inputStream, int recognitionThreshold)
```


Reconoce la imagen

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | java.io.InputStream | Flujo de la imagen |
| recognitionThreshold | int | (Opcional) El umbral de reconocimiento en el rango (0..100). Sólo los elementos rellenados por encima del umbral se contarán como rellenados. |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(String imagePath) {#recognizeImage-java.lang.String}
```
public final RecognitionResult recognizeImage(String imagePath)
```


Reconoce la imagen

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imagePath | java.lang.String | La ruta a la imagen a reconocer |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(String imagePath, int recognitionThreshold) {#recognizeImage-java.lang.String-int}
```
public final RecognitionResult recognizeImage(String imagePath, int recognitionThreshold)
```


Reconoce la imagen

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imagePath | java.lang.String | La ruta a la imagen a reconocer |
| recognitionThreshold | int | (Opcional) El umbral de reconocimiento en el rango (0..100). Sólo los elementos rellenados por encima del umbral se contarán como rellenados. |

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

