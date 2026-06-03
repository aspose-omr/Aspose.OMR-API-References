---
title: "TemplateProcessor"
second_title: "Referensi API Aspose.OMR for Java"
description: "Kelas untuk memproses templat dan gambar"
type: docs
weight: 30
url: /id/java/com.aspose.omr/templateprocessor/
---

**Inheritance:**
java.lang.Object
```
public class TemplateProcessor
```

Kelas untuk memproses templat dan gambar.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [recalculate(RecognitionResult result)](#recalculate-com.aspose.omr.RecognitionResult) | Memperbarui hasil pengenalan menggunakan parameter yang disetel halus. |
| [recalculate(RecognitionResult result, int recognitionThreshold)](#recalculate-com.aspose.omr.RecognitionResult-int) | Memperbarui hasil pengenalan menggunakan parameter yang disetel halus. |
| [recognizeImage(BufferedImage bufferedImage)](#recognizeImage-java.awt.image.BufferedImage) | Mengenali gambar |
| [recognizeImage(BufferedImage bufferedImage, int recognitionThreshold)](#recognizeImage-java.awt.image.BufferedImage-int) | Mengenali gambar |
| [recognizeImage(InputStream inputStream)](#recognizeImage-java.io.InputStream) | Mengenali gambar |
| [recognizeImage(InputStream inputStream, int recognitionThreshold)](#recognizeImage-java.io.InputStream-int) | Mengenali gambar |
| [recognizeImage(String imagePath)](#recognizeImage-java.lang.String) | Mengenali gambar |
| [recognizeImage(String imagePath, int recognitionThreshold)](#recognizeImage-java.lang.String-int) | Mengenali gambar |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
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


Memperbarui hasil pengenalan menggunakan parameter yang disetel halus.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| result | [RecognitionResult](../../com.aspose.omr/recognitionresult/) | Hasil pengenalan yang akan diperbarui. |

### recalculate(RecognitionResult result, int recognitionThreshold) {#recalculate-com.aspose.omr.RecognitionResult-int}
```
public final void recalculate(RecognitionResult result, int recognitionThreshold)
```


Memperbarui hasil pengenalan menggunakan parameter yang disetel halus.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| result | [RecognitionResult](../../com.aspose.omr/recognitionresult/) | Hasil pengenalan yang akan diperbarui. |
| recognitionThreshold | int | (Opsional) Ambang batas pengenalan dalam rentang (0..100). Hanya elemen yang terisi di atas ambang batas yang akan dihitung sebagai terisi. |

### recognizeImage(BufferedImage bufferedImage) {#recognizeImage-java.awt.image.BufferedImage}
```
public final RecognitionResult recognizeImage(BufferedImage bufferedImage)
```


Mengenali gambar

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bufferedImage | java.awt.image.BufferedImage | Gambar untuk dikenali |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(BufferedImage bufferedImage, int recognitionThreshold) {#recognizeImage-java.awt.image.BufferedImage-int}
```
public final RecognitionResult recognizeImage(BufferedImage bufferedImage, int recognitionThreshold)
```


Mengenali gambar

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bufferedImage | java.awt.image.BufferedImage | Gambar untuk dikenali |
| recognitionThreshold | int | (Opsional) Ambang batas pengenalan dalam rentang (0..100). Hanya elemen yang terisi di atas ambang batas yang akan dihitung sebagai terisi. |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(InputStream inputStream) {#recognizeImage-java.io.InputStream}
```
public final RecognitionResult recognizeImage(InputStream inputStream)
```


Mengenali gambar

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | java.io.InputStream | Aliran gambar |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(InputStream inputStream, int recognitionThreshold) {#recognizeImage-java.io.InputStream-int}
```
public final RecognitionResult recognizeImage(InputStream inputStream, int recognitionThreshold)
```


Mengenali gambar

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | java.io.InputStream | Aliran gambar |
| recognitionThreshold | int | (Opsional) Ambang batas pengenalan dalam rentang (0..100). Hanya elemen yang terisi di atas ambang batas yang akan dihitung sebagai terisi. |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(String imagePath) {#recognizeImage-java.lang.String}
```
public final RecognitionResult recognizeImage(String imagePath)
```


Mengenali gambar

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imagePath | java.lang.String | Jalur ke gambar untuk dikenali |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(String imagePath, int recognitionThreshold) {#recognizeImage-java.lang.String-int}
```
public final RecognitionResult recognizeImage(String imagePath, int recognitionThreshold)
```


Mengenali gambar

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imagePath | java.lang.String | Jalur ke gambar untuk dikenali |
| recognitionThreshold | int | (Opsional) Ambang batas pengenalan dalam rentang (0..100) Hanya elemen yang terisi di atas ambang batas yang akan dihitung sebagai terisi. |

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

