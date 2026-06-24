---
title: "TemplateProcessor"
second_title: "مرجع API لـ Aspose.OMR for Java"
description: "فئة لمعالجة القوالب والصور"
type: docs
weight: 30
url: /ar/java/com.aspose.omr/templateprocessor/
---

**Inheritance:**
java.lang.Object
```
public class TemplateProcessor
```

فئة لمعالجة القوالب والصور.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [recalculate(RecognitionResult result)](#recalculate-com.aspose.omr.RecognitionResult) | يحدّث نتيجة التعرف باستخدام معلمات مُضبوطة بدقة. |
| [recalculate(RecognitionResult result, int recognitionThreshold)](#recalculate-com.aspose.omr.RecognitionResult-int) | يحدّث نتيجة التعرف باستخدام معلمات مُضبوطة بدقة. |
| [recognizeImage(BufferedImage bufferedImage)](#recognizeImage-java.awt.image.BufferedImage) | يتعرف على الصورة |
| [recognizeImage(BufferedImage bufferedImage, int recognitionThreshold)](#recognizeImage-java.awt.image.BufferedImage-int) | يتعرف على الصورة |
| [recognizeImage(InputStream inputStream)](#recognizeImage-java.io.InputStream) | يتعرف على الصورة |
| [recognizeImage(InputStream inputStream, int recognitionThreshold)](#recognizeImage-java.io.InputStream-int) | يتعرف على الصورة |
| [recognizeImage(String imagePath)](#recognizeImage-java.lang.String) | يتعرف على الصورة |
| [recognizeImage(String imagePath, int recognitionThreshold)](#recognizeImage-java.lang.String-int) | يتعرف على الصورة |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
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


يحدّث نتيجة التعرف باستخدام معلمات مُضبوطة بدقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| result | [RecognitionResult](../../com.aspose.omr/recognitionresult/) | نتيجة التعرف لتحديثها. |

### recalculate(RecognitionResult result, int recognitionThreshold) {#recalculate-com.aspose.omr.RecognitionResult-int}
```
public final void recalculate(RecognitionResult result, int recognitionThreshold)
```


يحدّث نتيجة التعرف باستخدام معلمات مُضبوطة بدقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| result | [RecognitionResult](../../com.aspose.omr/recognitionresult/) | نتيجة التعرف لتحديثها. |
| recognitionThreshold | int | (اختياري) عتبة التعرف في النطاق (0..100). فقط العناصر المملوءة فوق العتبة سيتم احتسابها كمملوءة. |

### recognizeImage(BufferedImage bufferedImage) {#recognizeImage-java.awt.image.BufferedImage}
```
public final RecognitionResult recognizeImage(BufferedImage bufferedImage)
```


يتعرف على الصورة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bufferedImage | java.awt.image.BufferedImage | الصورة للتعرف عليها |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(BufferedImage bufferedImage, int recognitionThreshold) {#recognizeImage-java.awt.image.BufferedImage-int}
```
public final RecognitionResult recognizeImage(BufferedImage bufferedImage, int recognitionThreshold)
```


يتعرف على الصورة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bufferedImage | java.awt.image.BufferedImage | الصورة للتعرف عليها |
| recognitionThreshold | int | (اختياري) عتبة التعرف في النطاق (0..100). فقط العناصر المملوءة فوق العتبة سيتم احتسابها كمملوءة. |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(InputStream inputStream) {#recognizeImage-java.io.InputStream}
```
public final RecognitionResult recognizeImage(InputStream inputStream)
```


يتعرف على الصورة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| inputStream | java.io.InputStream | تدفق الصورة |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(InputStream inputStream, int recognitionThreshold) {#recognizeImage-java.io.InputStream-int}
```
public final RecognitionResult recognizeImage(InputStream inputStream, int recognitionThreshold)
```


يتعرف على الصورة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| inputStream | java.io.InputStream | تدفق الصورة |
| recognitionThreshold | int | (اختياري) عتبة التعرف في النطاق (0..100). فقط العناصر المملوءة فوق العتبة سيتم احتسابها كمملوءة. |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(String imagePath) {#recognizeImage-java.lang.String}
```
public final RecognitionResult recognizeImage(String imagePath)
```


يتعرف على الصورة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| imagePath | java.lang.String | المسار إلى الصورة للتعرف عليها |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(String imagePath, int recognitionThreshold) {#recognizeImage-java.lang.String-int}
```
public final RecognitionResult recognizeImage(String imagePath, int recognitionThreshold)
```


يتعرف على الصورة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| imagePath | java.lang.String | المسار إلى الصورة للتعرف عليها |
| recognitionThreshold | int | (اختياري) عتبة التعرف في النطاق (0..100) فقط العناصر المملوءة فوق العتبة سيتم احتسابها كمملوءة. |

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

