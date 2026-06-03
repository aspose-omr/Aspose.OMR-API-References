---
title: "TemplateProcessor"
second_title: "Aspose.OMR for Java API 참조"
description: "템플릿 및 이미지를 처리하기 위한 클래스"
type: docs
weight: 30
url: /ko/java/com.aspose.omr/templateprocessor/
---

**Inheritance:**
java.lang.Object
```
public class TemplateProcessor
```

템플릿 및 이미지를 처리하기 위한 클래스입니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [recalculate(RecognitionResult result)](#recalculate-com.aspose.omr.RecognitionResult) | 세밀하게 조정된 매개변수를 사용하여 인식 결과를 업데이트합니다. |
| [recalculate(RecognitionResult result, int recognitionThreshold)](#recalculate-com.aspose.omr.RecognitionResult-int) | 세밀하게 조정된 매개변수를 사용하여 인식 결과를 업데이트합니다. |
| [recognizeImage(BufferedImage bufferedImage)](#recognizeImage-java.awt.image.BufferedImage) | 이미지를 인식합니다 |
| [recognizeImage(BufferedImage bufferedImage, int recognitionThreshold)](#recognizeImage-java.awt.image.BufferedImage-int) | 이미지를 인식합니다 |
| [recognizeImage(InputStream inputStream)](#recognizeImage-java.io.InputStream) | 이미지를 인식합니다 |
| [recognizeImage(InputStream inputStream, int recognitionThreshold)](#recognizeImage-java.io.InputStream-int) | 이미지를 인식합니다 |
| [recognizeImage(String imagePath)](#recognizeImage-java.lang.String) | 이미지를 인식합니다 |
| [recognizeImage(String imagePath, int recognitionThreshold)](#recognizeImage-java.lang.String-int) | 이미지를 인식합니다 |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
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


세밀하게 조정된 매개변수를 사용하여 인식 결과를 업데이트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| result | [RecognitionResult](../../com.aspose.omr/recognitionresult/) | 업데이트할 인식 결과입니다. |

### recalculate(RecognitionResult result, int recognitionThreshold) {#recalculate-com.aspose.omr.RecognitionResult-int}
```
public final void recalculate(RecognitionResult result, int recognitionThreshold)
```


세밀하게 조정된 매개변수를 사용하여 인식 결과를 업데이트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| result | [RecognitionResult](../../com.aspose.omr/recognitionresult/) | 업데이트할 인식 결과입니다. |
| recognitionThreshold | int | (선택 사항) 인식 임계값은 (0..100) 범위입니다. 임계값을 초과한 요소만 채워진 것으로 간주됩니다. |

### recognizeImage(BufferedImage bufferedImage) {#recognizeImage-java.awt.image.BufferedImage}
```
public final RecognitionResult recognizeImage(BufferedImage bufferedImage)
```


이미지를 인식합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| bufferedImage | java.awt.image.BufferedImage | 인식할 이미지 |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(BufferedImage bufferedImage, int recognitionThreshold) {#recognizeImage-java.awt.image.BufferedImage-int}
```
public final RecognitionResult recognizeImage(BufferedImage bufferedImage, int recognitionThreshold)
```


이미지를 인식합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| bufferedImage | java.awt.image.BufferedImage | 인식할 이미지 |
| recognitionThreshold | int | (선택 사항) 인식 임계값은 (0..100) 범위입니다. 임계값을 초과한 요소만 채워진 것으로 간주됩니다. |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(InputStream inputStream) {#recognizeImage-java.io.InputStream}
```
public final RecognitionResult recognizeImage(InputStream inputStream)
```


이미지를 인식합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 이미지 스트림 |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(InputStream inputStream, int recognitionThreshold) {#recognizeImage-java.io.InputStream-int}
```
public final RecognitionResult recognizeImage(InputStream inputStream, int recognitionThreshold)
```


이미지를 인식합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 이미지 스트림 |
| recognitionThreshold | int | (선택 사항) 인식 임계값은 (0..100) 범위입니다. 임계값을 초과한 요소만 채워진 것으로 간주됩니다. |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(String imagePath) {#recognizeImage-java.lang.String}
```
public final RecognitionResult recognizeImage(String imagePath)
```


이미지를 인식합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imagePath | java.lang.String | 인식할 이미지의 경로 |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(String imagePath, int recognitionThreshold) {#recognizeImage-java.lang.String-int}
```
public final RecognitionResult recognizeImage(String imagePath, int recognitionThreshold)
```


이미지를 인식합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imagePath | java.lang.String | 인식할 이미지의 경로 |
| recognitionThreshold | int | (선택 사항) 인식 임계값은 (0..100) 범위입니다. 임계값을 초과한 요소만 채워진 것으로 간주됩니다. |

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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

