---
title: "OmrPage"
second_title: "Aspose.OMR for Java API 참조"
description: "단일 OMR 페이지를 나타냅니다."
type: docs
weight: 24
url: /ko/java/com.aspose.omr/omrpage/
---

**Inheritance:**
java.lang.Object
```
public class OmrPage
```

단일 OMR 페이지를 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [OmrPage()](#OmrPage) | 새로운 [OmrPage](../../com.aspose.omr/omrpage/) 클래스 인스턴스를 초기화합니다 |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addBarcodeElement(BarcodeElement element)](#addBarcodeElement-com.aspose.omr.BarcodeElement) |  |
| [addChoiceBoxElement(String name, int width, int height, int top, int left)](#addChoiceBoxElement-java.lang.String-int-int-int-int) | 페이지에 선택 상자 요소를 추가합니다 |
| [addClipAreaElement(String name, int width, int height, int top, int left)](#addClipAreaElement-java.lang.String-int-int-int-int) |  |
| [addGridElement(GridElement grid)](#addGridElement-com.aspose.omr.GridElement) |  |
| [addGridElement(String name, int width, int height, int top, int left)](#addGridElement-java.lang.String-int-int-int-int) |  |
| [addRefPointElement(ReferencePointElement item)](#addRefPointElement-com.aspose.omr.ReferencePointElement) |  |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [getElements()](#getElements) | 페이지의 요소 목록을 가져오거나 설정합니다 |
| [getHeight()](#getHeight) | 페이지 높이를 가져오거나 설정합니다 |
| [getImageFormat()](#getImageFormat) | 이미지 파일 형식을 가져오거나 설정합니다 |
| [getImageName()](#getImageName) | 이미지 데이터를 가져오거나 설정합니다 |
| [getRotationPointPosition()](#getRotationPointPosition) | RotationPointPosition을 가져오거나 설정합니다 |
| [getWidth()](#getWidth) | 페이지 너비를 가져오거나 설정합니다 |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [setElements(System.Collections.Generic.List<OmrElement> value)](#setElements-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement) | 페이지의 요소 목록을 가져오거나 설정합니다 |
| [setHeight(double value)](#setHeight-double) | 페이지 높이를 가져오거나 설정합니다 |
| [setImageFormat(String value)](#setImageFormat-java.lang.String) | 이미지 파일 형식을 가져오거나 설정합니다 |
| [setImageName(String value)](#setImageName-java.lang.String) | 이미지 이름을 가져오거나 설정합니다 |
| [setRotationPointPosition(RotationPointPosition value)](#setRotationPointPosition-com.aspose.omr.RotationPointPosition) | RotationPointPosition을 가져오거나 설정합니다 |
| [setWidth(double value)](#setWidth-double) | 페이지 너비를 가져오거나 설정합니다 |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### OmrPage() {#OmrPage}
```
public OmrPage()
```


새로운 [OmrPage](../../com.aspose.omr/omrpage/) 클래스 인스턴스를 초기화합니다

### addBarcodeElement(BarcodeElement element) {#addBarcodeElement-com.aspose.omr.BarcodeElement}
```
public final void addBarcodeElement(BarcodeElement element)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| element | [BarcodeElement](../../com.aspose.omr/barcodeelement/) |  |

### addChoiceBoxElement(String name, int width, int height, int top, int left) {#addChoiceBoxElement-java.lang.String-int-int-int-int}
```
public final ChoiceBoxElement addChoiceBoxElement(String name, int width, int height, int top, int left)
```


페이지에 선택 상자 요소를 추가합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 요소 이름 |
| 너비 | int | 요소 너비 |
| 높이 | int | 요소 높이 |
| 위쪽 | int | 요소 위쪽 위치 |
| 왼쪽 | int | 요소 왼쪽 위치 |

**Returns:**
[ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) - Created choice box
### addClipAreaElement(String name, int width, int height, int top, int left) {#addClipAreaElement-java.lang.String-int-int-int-int}
```
public final ClipAreaElement addClipAreaElement(String name, int width, int height, int top, int left)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |
| 너비 | int |  |
| 높이 | int |  |
| 위쪽 | int |  |
| 왼쪽 | int |  |

**Returns:**
[ClipAreaElement](../../com.aspose.omr/clipareaelement/)
### addGridElement(GridElement grid) {#addGridElement-com.aspose.omr.GridElement}
```
public final void addGridElement(GridElement grid)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| grid | [GridElement](../../com.aspose.omr/gridelement/) |  |

### addGridElement(String name, int width, int height, int top, int left) {#addGridElement-java.lang.String-int-int-int-int}
```
public final GridElement addGridElement(String name, int width, int height, int top, int left)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |
| 너비 | int |  |
| 높이 | int |  |
| 위쪽 | int |  |
| 왼쪽 | int |  |

**Returns:**
[GridElement](../../com.aspose.omr/gridelement/)
### addRefPointElement(ReferencePointElement item) {#addRefPointElement-com.aspose.omr.ReferencePointElement}
```
public final void addRefPointElement(ReferencePointElement item)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| item | [ReferencePointElement](../../com.aspose.omr/referencepointelement/) |  |

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
### getElements() {#getElements}
```
public final System.Collections.Generic.List<OmrElement> getElements()
```


페이지의 요소 목록을 가져오거나 설정합니다

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrElement> - 페이지의 요소 목록
### getHeight() {#getHeight}
```
public final double getHeight()
```


페이지 높이를 가져오거나 설정합니다

**Returns:**
double - 페이지 높이
### getImageFormat() {#getImageFormat}
```
public final String getImageFormat()
```


이미지 파일 형식을 가져오거나 설정합니다

**Returns:**
java.lang.String - 이미지 파일 형식
### getImageName() {#getImageName}
```
public final String getImageName()
```


이미지 데이터를 가져오거나 설정합니다

**Returns:**
java.lang.String - 이미지 이름
### getRotationPointPosition() {#getRotationPointPosition}
```
public final RotationPointPosition getRotationPointPosition()
```


RotationPointPosition을 가져오거나 설정합니다

**Returns:**
[RotationPointPosition](../../com.aspose.omr/rotationpointposition/) - RotationPointPosition
### getWidth() {#getWidth}
```
public final double getWidth()
```


페이지 너비를 가져오거나 설정합니다

**Returns:**
double - 페이지 너비
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




### setElements(System.Collections.Generic.List<OmrElement> value) {#setElements-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement}
```
public final void setElements(System.Collections.Generic.List<OmrElement> value)
```


페이지의 요소 목록을 가져오거나 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrElement> | 페이지의 요소 목록 |

### setHeight(double value) {#setHeight-double}
```
public final void setHeight(double value)
```


페이지 높이를 가져오거나 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | double | 페이지 높이 |

### setImageFormat(String value) {#setImageFormat-java.lang.String}
```
public final void setImageFormat(String value)
```


이미지 파일 형식을 가져오거나 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 이미지 파일 형식 |

### setImageName(String value) {#setImageName-java.lang.String}
```
public final void setImageName(String value)
```


이미지 이름을 가져오거나 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 이미지 이름 |

### setRotationPointPosition(RotationPointPosition value) {#setRotationPointPosition-com.aspose.omr.RotationPointPosition}
```
public final void setRotationPointPosition(RotationPointPosition value)
```


RotationPointPosition을 가져오거나 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [RotationPointPosition](../../com.aspose.omr/rotationpointposition/) | RotationPointPosition |

### setWidth(double value) {#setWidth-double}
```
public final void setWidth(double value)
```


페이지 너비를 가져오거나 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | double | 페이지 너비 |

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

