---
title: "ChoiceBoxElement"
second_title: "Aspose.OMR for Java API 참조"
description: "ChoiceBox 질문을 나타냅니다."
type: docs
weight: 11
url: /ko/java/com.aspose.omr/choiceboxelement/
---

**Inheritance:**
java.lang.Object, [com.aspose.omr.OmrElement](../../com.aspose.omr/omrelement/)
```
public class ChoiceBoxElement extends OmrElement
```

ChoiceBox 질문을 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ChoiceBoxElement()](#ChoiceBoxElement) | 새 인스턴스를 초기화합니다 [ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) 클래스 |
## 필드

| 필드 | 설명 |
| --- | --- |
| [ElementType](#ElementType) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addBubble(String name, int width, int height, int top, int left, boolean isValid)](#addBubble-java.lang.String-int-int-int-int-boolean) | 질문 내부에 버블을 추가합니다 |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getBubbleHeight()](#getBubbleHeight) |  |
| [getBubbleWidth()](#getBubbleWidth) |  |
| [getBubbles()](#getBubbles) | 버블 컬렉션을 가져오거나 설정합니다 |
| [getClass()](#getClass) |  |
| [getHeight()](#getHeight) | 질문의 높이를 가져오거나 설정합니다 |
| [getLeft()](#getLeft) | 질문의 왼쪽 위치를 가져오거나 설정합니다 |
| [getMultipleSelectionAllowed()](#getMultipleSelectionAllowed) | 다중 선택이 허용되는지 여부를 나타내는 값을 가져오거나 설정합니다 |
| [getName()](#getName) | 질문 이름을 가져옵니다 |
| [getOrientation()](#getOrientation) |  |
| [getOrientationString()](#getOrientationString) | orientation 속성의 문자열 표현을 가져옵니다 |
| [getRect()](#getRect) |  |
| [getTop()](#getTop) | 질문의 위쪽 위치를 가져오거나 설정합니다 |
| [getWidth()](#getWidth) | 질문의 너비를 가져오거나 설정합니다 |
| [hashCode()](#hashCode) |  |
| [isAlignedHorizontal()](#isAlignedHorizontal) | 버블이 수평으로 정렬되는지 여부를 나타내는 값을 가져오거나 설정합니다 |
| [isAlignedVertical()](#isAlignedVertical) | 버블이 수직으로 정렬되는지 여부를 나타내는 값을 가져오거나 설정합니다 |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [setAlignedHorizontal(boolean value)](#setAlignedHorizontal-boolean) | 버블이 수평으로 정렬되는지 여부를 나타내는 값을 가져오거나 설정합니다 |
| [setAlignedVertical(boolean value)](#setAlignedVertical-boolean) | 버블이 수직으로 정렬되는지 여부를 나타내는 값을 가져오거나 설정합니다 |
| [setBubbleHeight(double value)](#setBubbleHeight-double) |  |
| [setBubbleWidth(double value)](#setBubbleWidth-double) |  |
| [setBubbles(System.Collections.Generic.List<OmrBubble> value)](#setBubbles-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrBubble) | 버블 컬렉션을 가져오거나 설정합니다 |
| [setHeight(double value)](#setHeight-double) | 질문의 높이를 가져오거나 설정합니다 |
| [setLeft(double value)](#setLeft-double) | 질문의 왼쪽 위치를 가져오거나 설정합니다 |
| [setMultipleSelectionAllowed(boolean value)](#setMultipleSelectionAllowed-boolean) | 다중 선택이 허용되는지 여부를 나타내는 값을 가져오거나 설정합니다 |
| [setName(String value)](#setName-java.lang.String) | 질문 이름을 설정합니다 |
| [setOrientation(int value)](#setOrientation-int) |  |
| [setTop(double value)](#setTop-double) | 질문의 위쪽 위치를 가져오거나 설정합니다 |
| [setWidth(double value)](#setWidth-double) | 질문의 너비를 가져오거나 설정합니다 |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### ChoiceBoxElement() {#ChoiceBoxElement}
```
public ChoiceBoxElement()
```


새 인스턴스를 초기화합니다 [ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) 클래스

### ElementType {#ElementType}
```
public String ElementType
```


### addBubble(String name, int width, int height, int top, int left, boolean isValid) {#addBubble-java.lang.String-int-int-int-int-boolean}
```
public final void addBubble(String name, int width, int height, int top, int left, boolean isValid)
```


질문 내부에 버블을 추가합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 버블 이름 |
| 너비 | int | 버블 너비 |
| 높이 | int | 버블 높이 |
| 위쪽 | int | 버블 상단 위치 |
| 왼쪽 | int | 버블 왼쪽 위치 |
| isValid | boolean | 버블 유효 플래그 |

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
### getBubbleHeight() {#getBubbleHeight}
```
public final double getBubbleHeight()
```




**Returns:**
double
### getBubbleWidth() {#getBubbleWidth}
```
public final double getBubbleWidth()
```




**Returns:**
double
### getBubbles() {#getBubbles}
```
public final System.Collections.Generic.List<OmrBubble> getBubbles()
```


버블 컬렉션을 가져오거나 설정합니다

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrBubble> - 버블 컬렉션
### getClass() {#getClass}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getHeight() {#getHeight}
```
public final double getHeight()
```


질문의 높이를 가져오거나 설정합니다

**Returns:**
double - 높이
### getLeft() {#getLeft}
```
public final double getLeft()
```


질문의 왼쪽 위치를 가져오거나 설정합니다

**Returns:**
double - 왼쪽
### getMultipleSelectionAllowed() {#getMultipleSelectionAllowed}
```
public final boolean getMultipleSelectionAllowed()
```


다중 선택이 허용되는지 여부를 나타내는 값을 가져오거나 설정합니다

**Returns:**
boolean - 다중 선택이 허용되는지 여부를 나타내는 값
### getName() {#getName}
```
public final String getName()
```


질문 이름을 가져옵니다

**Returns:**
java.lang.String - 질문 이름
### getOrientation() {#getOrientation}
```
public final int getOrientation()
```




**Returns:**
int
### getOrientationString() {#getOrientationString}
```
public final String getOrientationString()
```


orientation 속성의 문자열 표현을 가져옵니다

**Returns:**
java.lang.String - orientation 속성의 문자열 표현
### getRect() {#getRect}
```
public System.Drawing.RectangleF getRect()
```




**Returns:**
com.aspose.ms.System.Drawing.RectangleF
### getTop() {#getTop}
```
public final double getTop()
```


질문의 위쪽 위치를 가져오거나 설정합니다

**Returns:**
double - 위쪽
### getWidth() {#getWidth}
```
public final double getWidth()
```


질문의 너비를 가져오거나 설정합니다

**Returns:**
double - 너비
### hashCode() {#hashCode}
```
public native int hashCode()
```




**Returns:**
int
### isAlignedHorizontal() {#isAlignedHorizontal}
```
public final boolean isAlignedHorizontal()
```


버블이 수평으로 정렬되는지 여부를 나타내는 값을 가져오거나 설정합니다

**Returns:**
boolean - 버블이 수평으로 정렬되는지 여부를 나타내는 값
### isAlignedVertical() {#isAlignedVertical}
```
public final boolean isAlignedVertical()
```


버블이 수직으로 정렬되는지 여부를 나타내는 값을 가져오거나 설정합니다

**Returns:**
boolean - 버블이 수직으로 정렬되는지 여부를 나타내는 값
### notify() {#notify}
```
public final native void notify()
```




### notifyAll() {#notifyAll}
```
public final native void notifyAll()
```




### setAlignedHorizontal(boolean value) {#setAlignedHorizontal-boolean}
```
public final void setAlignedHorizontal(boolean value)
```


버블이 수평으로 정렬되는지 여부를 나타내는 값을 가져오거나 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean | 버블이 수평으로 정렬되는지 여부를 나타내는 값 |

### setAlignedVertical(boolean value) {#setAlignedVertical-boolean}
```
public final void setAlignedVertical(boolean value)
```


버블이 수직으로 정렬되는지 여부를 나타내는 값을 가져오거나 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean | 버블이 수직으로 정렬되는지 여부를 나타내는 값 |

### setBubbleHeight(double value) {#setBubbleHeight-double}
```
public final void setBubbleHeight(double value)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setBubbleWidth(double value) {#setBubbleWidth-double}
```
public final void setBubbleWidth(double value)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setBubbles(System.Collections.Generic.List<OmrBubble> value) {#setBubbles-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrBubble}
```
public final void setBubbles(System.Collections.Generic.List<OmrBubble> value)
```


버블 컬렉션을 가져오거나 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrBubble> | 버블 컬렉션 |

### setHeight(double value) {#setHeight-double}
```
public final void setHeight(double value)
```


질문의 높이를 가져오거나 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | double | 높이 |

### setLeft(double value) {#setLeft-double}
```
public final void setLeft(double value)
```


질문의 왼쪽 위치를 가져오거나 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | double | 왼쪽 |

### setMultipleSelectionAllowed(boolean value) {#setMultipleSelectionAllowed-boolean}
```
public final void setMultipleSelectionAllowed(boolean value)
```


다중 선택이 허용되는지 여부를 나타내는 값을 가져오거나 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean | 다중 선택이 허용되는지 여부를 나타내는 값 |

### setName(String value) {#setName-java.lang.String}
```
public final void setName(String value)
```


질문 이름을 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 질문 이름 |

### setOrientation(int value) {#setOrientation-int}
```
public final void setOrientation(int value)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setTop(double value) {#setTop-double}
```
public final void setTop(double value)
```


질문의 위쪽 위치를 가져오거나 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | double | 위쪽 |

### setWidth(double value) {#setWidth-double}
```
public final void setWidth(double value)
```


질문의 너비를 가져오거나 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | double | 너비 |

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

