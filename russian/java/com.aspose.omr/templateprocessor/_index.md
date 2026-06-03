---
title: "TemplateProcessor"
second_title: "Справочник API Aspose.OMR для Java"
description: "Класс для обработки шаблонов и изображений"
type: docs
weight: 30
url: /ru/java/com.aspose.omr/templateprocessor/
---

**Inheritance:**
java.lang.Object
```
public class TemplateProcessor
```

Класс для обработки шаблонов и изображений.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [recalculate(RecognitionResult result)](#recalculate-com.aspose.omr.RecognitionResult) | Обновляет результат распознавания, используя точно настроенные параметры. |
| [recalculate(RecognitionResult result, int recognitionThreshold)](#recalculate-com.aspose.omr.RecognitionResult-int) | Обновляет результат распознавания, используя точно настроенные параметры. |
| [recognizeImage(BufferedImage bufferedImage)](#recognizeImage-java.awt.image.BufferedImage) | Распознает изображение |
| [recognizeImage(BufferedImage bufferedImage, int recognitionThreshold)](#recognizeImage-java.awt.image.BufferedImage-int) | Распознает изображение |
| [recognizeImage(InputStream inputStream)](#recognizeImage-java.io.InputStream) | Распознает изображение |
| [recognizeImage(InputStream inputStream, int recognitionThreshold)](#recognizeImage-java.io.InputStream-int) | Распознает изображение |
| [recognizeImage(String imagePath)](#recognizeImage-java.lang.String) | Распознает изображение |
| [recognizeImage(String imagePath, int recognitionThreshold)](#recognizeImage-java.lang.String-int) | Распознает изображение |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
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


Обновляет результат распознавания, используя точно настроенные параметры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| result | [RecognitionResult](../../com.aspose.omr/recognitionresult/) | Результат распознавания для обновления. |

### recalculate(RecognitionResult result, int recognitionThreshold) {#recalculate-com.aspose.omr.RecognitionResult-int}
```
public final void recalculate(RecognitionResult result, int recognitionThreshold)
```


Обновляет результат распознавания, используя точно настроенные параметры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| result | [RecognitionResult](../../com.aspose.omr/recognitionresult/) | Результат распознавания для обновления. |
| recognitionThreshold | int | (Необязательно) Порог распознавания в диапазоне (0..100). Только элементы, заполненные выше порога, будут учитываться как заполненные. |

### recognizeImage(BufferedImage bufferedImage) {#recognizeImage-java.awt.image.BufferedImage}
```
public final RecognitionResult recognizeImage(BufferedImage bufferedImage)
```


Распознает изображение

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bufferedImage | java.awt.image.BufferedImage | Изображение для распознавания |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(BufferedImage bufferedImage, int recognitionThreshold) {#recognizeImage-java.awt.image.BufferedImage-int}
```
public final RecognitionResult recognizeImage(BufferedImage bufferedImage, int recognitionThreshold)
```


Распознает изображение

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bufferedImage | java.awt.image.BufferedImage | Изображение для распознавания |
| recognitionThreshold | int | (Необязательно) Порог распознавания в диапазоне (0..100). Только элементы, заполненные выше порога, будут учитываться как заполненные. |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(InputStream inputStream) {#recognizeImage-java.io.InputStream}
```
public final RecognitionResult recognizeImage(InputStream inputStream)
```


Распознает изображение

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Поток изображения |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(InputStream inputStream, int recognitionThreshold) {#recognizeImage-java.io.InputStream-int}
```
public final RecognitionResult recognizeImage(InputStream inputStream, int recognitionThreshold)
```


Распознает изображение

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Поток изображения |
| recognitionThreshold | int | (Необязательно) Порог распознавания в диапазоне (0..100). Только элементы, заполненные выше порога, будут учитываться как заполненные. |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(String imagePath) {#recognizeImage-java.lang.String}
```
public final RecognitionResult recognizeImage(String imagePath)
```


Распознает изображение

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| imagePath | java.lang.String | Путь к изображению для распознавания |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(String imagePath, int recognitionThreshold) {#recognizeImage-java.lang.String-int}
```
public final RecognitionResult recognizeImage(String imagePath, int recognitionThreshold)
```


Распознает изображение

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| imagePath | java.lang.String | Путь к изображению для распознавания |
| recognitionThreshold | int | (Необязательно) Порог распознавания в диапазоне (0..100). Только элементы, заполненные выше порога, будут учитываться как заполненные. |

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

