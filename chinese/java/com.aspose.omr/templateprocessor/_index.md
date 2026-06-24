---
title: "TemplateProcessor"
second_title: "Aspose.OMR for Java API 参考"
description: "用于处理模板和图像的类"
type: docs
weight: 30
url: /zh/java/com.aspose.omr/templateprocessor/
---

**Inheritance:**
java.lang.Object
```
public class TemplateProcessor
```

用于处理模板和图像的类。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [recalculate(RecognitionResult result)](#recalculate-com.aspose.omr.RecognitionResult) | 使用微调参数更新识别结果。 |
| [recalculate(RecognitionResult result, int recognitionThreshold)](#recalculate-com.aspose.omr.RecognitionResult-int) | 使用微调参数更新识别结果。 |
| [recognizeImage(BufferedImage bufferedImage)](#recognizeImage-java.awt.image.BufferedImage) | 识别图像 |
| [recognizeImage(BufferedImage bufferedImage, int recognitionThreshold)](#recognizeImage-java.awt.image.BufferedImage-int) | 识别图像 |
| [recognizeImage(InputStream inputStream)](#recognizeImage-java.io.InputStream) | 识别图像 |
| [recognizeImage(InputStream inputStream, int recognitionThreshold)](#recognizeImage-java.io.InputStream-int) | 识别图像 |
| [recognizeImage(String imagePath)](#recognizeImage-java.lang.String) | 识别图像 |
| [recognizeImage(String imagePath, int recognitionThreshold)](#recognizeImage-java.lang.String-int) | 识别图像 |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
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


使用微调参数更新识别结果。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| result | [RecognitionResult](../../com.aspose.omr/recognitionresult/) | 要更新的识别结果。 |

### recalculate(RecognitionResult result, int recognitionThreshold) {#recalculate-com.aspose.omr.RecognitionResult-int}
```
public final void recalculate(RecognitionResult result, int recognitionThreshold)
```


使用微调参数更新识别结果。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| result | [RecognitionResult](../../com.aspose.omr/recognitionresult/) | 要更新的识别结果。 |
| recognitionThreshold | int | （可选）识别阈值，范围为 (0..100)。仅在阈值以上填充的元素会被计为已填充。 |

### recognizeImage(BufferedImage bufferedImage) {#recognizeImage-java.awt.image.BufferedImage}
```
public final RecognitionResult recognizeImage(BufferedImage bufferedImage)
```


识别图像

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bufferedImage | java.awt.image.BufferedImage | 待识别的图像 |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(BufferedImage bufferedImage, int recognitionThreshold) {#recognizeImage-java.awt.image.BufferedImage-int}
```
public final RecognitionResult recognizeImage(BufferedImage bufferedImage, int recognitionThreshold)
```


识别图像

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bufferedImage | java.awt.image.BufferedImage | 待识别的图像 |
| recognitionThreshold | int | （可选）识别阈值，范围为 (0..100)。仅在阈值以上填充的元素会被计为已填充。 |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(InputStream inputStream) {#recognizeImage-java.io.InputStream}
```
public final RecognitionResult recognizeImage(InputStream inputStream)
```


识别图像

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 图像的流 |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(InputStream inputStream, int recognitionThreshold) {#recognizeImage-java.io.InputStream-int}
```
public final RecognitionResult recognizeImage(InputStream inputStream, int recognitionThreshold)
```


识别图像

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 图像的流 |
| recognitionThreshold | int | （可选）识别阈值，范围为 (0..100)。仅在阈值以上填充的元素会被计为已填充。 |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(String imagePath) {#recognizeImage-java.lang.String}
```
public final RecognitionResult recognizeImage(String imagePath)
```


识别图像

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imagePath | java.lang.String | 待识别图像的路径 |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(String imagePath, int recognitionThreshold) {#recognizeImage-java.lang.String-int}
```
public final RecognitionResult recognizeImage(String imagePath, int recognitionThreshold)
```


识别图像

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imagePath | java.lang.String | 待识别图像的路径 |
| recognitionThreshold | int | （可选）识别阈值，范围为 (0..100)。仅在阈值以上填充的元素会被计为已填充。 |

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

