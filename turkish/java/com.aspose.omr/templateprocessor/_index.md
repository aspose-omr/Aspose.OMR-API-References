---
title: "TemplateProcessor"
second_title: "Aspose.OMR for Java API Referansı"
description: "Şablonları ve görüntüleri işlemek için sınıf"
type: docs
weight: 30
url: /tr/java/com.aspose.omr/templateprocessor/
---

**Inheritance:**
java.lang.Object
```
public class TemplateProcessor
```

Şablonları ve görüntüleri işlemek için sınıf.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [recalculate(RecognitionResult result)](#recalculate-com.aspose.omr.RecognitionResult) | İnce ayarlanmış parametreler kullanarak tanıma sonucunu günceller. |
| [recalculate(RecognitionResult result, int recognitionThreshold)](#recalculate-com.aspose.omr.RecognitionResult-int) | İnce ayarlanmış parametreler kullanarak tanıma sonucunu günceller. |
| [recognizeImage(BufferedImage bufferedImage)](#recognizeImage-java.awt.image.BufferedImage) | Görüntüyü tanır |
| [recognizeImage(BufferedImage bufferedImage, int recognitionThreshold)](#recognizeImage-java.awt.image.BufferedImage-int) | Görüntüyü tanır |
| [recognizeImage(InputStream inputStream)](#recognizeImage-java.io.InputStream) | Görüntüyü tanır |
| [recognizeImage(InputStream inputStream, int recognitionThreshold)](#recognizeImage-java.io.InputStream-int) | Görüntüyü tanır |
| [recognizeImage(String imagePath)](#recognizeImage-java.lang.String) | Görüntüyü tanır |
| [recognizeImage(String imagePath, int recognitionThreshold)](#recognizeImage-java.lang.String-int) | Görüntüyü tanır |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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


İnce ayarlanmış parametreler kullanarak tanıma sonucunu günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| result | [RecognitionResult](../../com.aspose.omr/recognitionresult/) | Güncellenecek tanıma sonucu. |

### recalculate(RecognitionResult result, int recognitionThreshold) {#recalculate-com.aspose.omr.RecognitionResult-int}
```
public final void recalculate(RecognitionResult result, int recognitionThreshold)
```


İnce ayarlanmış parametreler kullanarak tanıma sonucunu günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| result | [RecognitionResult](../../com.aspose.omr/recognitionresult/) | Güncellenecek tanıma sonucu. |
| recognitionThreshold | int | (İsteğe bağlı) Tanıma eşiği (0..100) aralığında. Eşiğin üzerindeki doldurulmuş öğeler doldurulmuş sayılacaktır. |

### recognizeImage(BufferedImage bufferedImage) {#recognizeImage-java.awt.image.BufferedImage}
```
public final RecognitionResult recognizeImage(BufferedImage bufferedImage)
```


Görüntüyü tanır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bufferedImage | java.awt.image.BufferedImage | Tanınacak görüntü |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(BufferedImage bufferedImage, int recognitionThreshold) {#recognizeImage-java.awt.image.BufferedImage-int}
```
public final RecognitionResult recognizeImage(BufferedImage bufferedImage, int recognitionThreshold)
```


Görüntüyü tanır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bufferedImage | java.awt.image.BufferedImage | Tanınacak görüntü |
| recognitionThreshold | int | (İsteğe bağlı) Tanıma eşiği (0..100) aralığında. Eşiğin üzerindeki doldurulmuş öğeler doldurulmuş sayılacaktır. |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(InputStream inputStream) {#recognizeImage-java.io.InputStream}
```
public final RecognitionResult recognizeImage(InputStream inputStream)
```


Görüntüyü tanır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | java.io.InputStream | Görüntünün akışı |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(InputStream inputStream, int recognitionThreshold) {#recognizeImage-java.io.InputStream-int}
```
public final RecognitionResult recognizeImage(InputStream inputStream, int recognitionThreshold)
```


Görüntüyü tanır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | java.io.InputStream | Görüntünün akışı |
| recognitionThreshold | int | (İsteğe bağlı) Tanıma eşiği (0..100) aralığında. Eşiğin üzerindeki doldurulmuş öğeler doldurulmuş sayılacaktır. |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(String imagePath) {#recognizeImage-java.lang.String}
```
public final RecognitionResult recognizeImage(String imagePath)
```


Görüntüyü tanır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imagePath | java.lang.String | Tanınacak görüntünün yolu |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(String imagePath, int recognitionThreshold) {#recognizeImage-java.lang.String-int}
```
public final RecognitionResult recognizeImage(String imagePath, int recognitionThreshold)
```


Görüntüyü tanır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imagePath | java.lang.String | Tanınacak görüntünün yolu |
| recognitionThreshold | int | (İsteğe bağlı) Tanıma eşiği (0..100) aralığında. Eşiğin üzerindeki doldurulmuş öğeler doldurulmuş sayılacaktır. |

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

