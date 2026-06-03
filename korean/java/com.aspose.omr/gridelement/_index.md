---
title: "GridElement"
second_title: "Aspose.OMR for Java API 참조"
description: 
type: docs
weight: 16
url: /ko/java/com.aspose.omr/gridelement/
---

**Inheritance:**
java.lang.Object, [com.aspose.omr.OmrElement](../../com.aspose.omr/omrelement/)
```
public class GridElement extends OmrElement
```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [GridElement()](#GridElement) |  |
## 필드

| 필드 | 설명 |
| --- | --- |
| [ElementType](#ElementType) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addChoiceBox(ChoiceBoxElement choiceBox)](#addChoiceBox-com.aspose.omr.ChoiceBoxElement) |  |
| [addChoiceBox(String name, int width, int height, int top, int left)](#addChoiceBox-java.lang.String-int-int-int-int) |  |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getChoiceBoxes()](#getChoiceBoxes) |  |
| [getClass()](#getClass) |  |
| [getHeight()](#getHeight) | 질문의 높이를 가져오거나 설정합니다 |
| [getLeft()](#getLeft) | 질문의 왼쪽 위치를 가져오거나 설정합니다 |
| [getName()](#getName) | 질문 이름을 가져옵니다 |
| [getOrientation()](#getOrientation) |  |
| [getOrientationString()](#getOrientationString) |  |
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
| [setChoiceBoxes(System.Collections.Generic.List<OmrElement> value)](#setChoiceBoxes-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement) |  |
| [setHeight(double value)](#setHeight-double) | 질문의 높이를 가져오거나 설정합니다 |
| [setLeft(double value)](#setLeft-double) | 질문의 왼쪽 위치를 가져오거나 설정합니다 |
| [setName(String value)](#setName-java.lang.String) | 질문 이름을 설정합니다 |
| [setOrientation(int value)](#setOrientation-int) |  |
| [setTop(double value)](#setTop-double) | 질문의 위쪽 위치를 가져오거나 설정합니다 |
| [setWidth(double value)](#setWidth-double) | 질문의 너비를 가져오거나 설정합니다 |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### GridElement() {#GridElement}
```
public GridElement()
```


### ElementType {#ElementType}
```
public String ElementType
```


### addChoiceBox(ChoiceBoxElement choiceBox) {#addChoiceBox-com.aspose.omr.ChoiceBoxElement}
```
public final void addChoiceBox(ChoiceBoxElement choiceBox)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| choiceBox | [ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) |  |

### addChoiceBox(String name, int width, int height, int top, int left) {#addChoiceBox-java.lang.String-int-int-int-int}
```
public final ChoiceBoxElement addChoiceBox(String name, int width, int height, int top, int left)
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
[ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/)
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
### getChoiceBoxes() {#getChoiceBoxes}
```
public final System.Collections.Generic.List<OmrElement> getChoiceBoxes()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrElement>
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




**Returns:**
java.lang.String
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

### setChoiceBoxes(System.Collections.Generic.List<OmrElement> value) {#setChoiceBoxes-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement}
```
public final void setChoiceBoxes(System.Collections.Generic.List<OmrElement> value)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrElement> |  |

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

