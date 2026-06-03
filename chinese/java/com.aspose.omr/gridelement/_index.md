---
title: "GridElement"
second_title: "Aspose.OMR for Java API 参考"
description: 
type: docs
weight: 16
url: /zh/java/com.aspose.omr/gridelement/
---

**Inheritance:**
java.lang.Object, [com.aspose.omr.OmrElement](../../com.aspose.omr/omrelement/)
```
public class GridElement extends OmrElement
```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [GridElement()](#GridElement) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
| [ElementType](#ElementType) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [addChoiceBox(ChoiceBoxElement choiceBox)](#addChoiceBox-com.aspose.omr.ChoiceBoxElement) |  |
| [addChoiceBox(String name, int width, int height, int top, int left)](#addChoiceBox-java.lang.String-int-int-int-int) |  |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getChoiceBoxes()](#getChoiceBoxes) |  |
| [getClass()](#getClass) |  |
| [getHeight()](#getHeight) | 获取或设置问题高度 |
| [getLeft()](#getLeft) | 获取或设置问题左侧位置 |
| [getName()](#getName) | 获取问题名称 |
| [getOrientation()](#getOrientation) |  |
| [getOrientationString()](#getOrientationString) |  |
| [getRect()](#getRect) |  |
| [getTop()](#getTop) | 获取或设置问题顶部位置 |
| [getWidth()](#getWidth) | 获取或设置问题宽度 |
| [hashCode()](#hashCode) |  |
| [isAlignedHorizontal()](#isAlignedHorizontal) | 获取或设置一个值，指示气泡是否水平对齐 |
| [isAlignedVertical()](#isAlignedVertical) | 获取或设置一个值，指示气泡是否垂直对齐 |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [setAlignedHorizontal(boolean value)](#setAlignedHorizontal-boolean) | 获取或设置一个值，指示气泡是否水平对齐 |
| [setAlignedVertical(boolean value)](#setAlignedVertical-boolean) | 获取或设置一个值，指示气泡是否垂直对齐 |
| [setChoiceBoxes(System.Collections.Generic.List<OmrElement> value)](#setChoiceBoxes-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement) |  |
| [setHeight(double value)](#setHeight-double) | 获取或设置问题高度 |
| [setLeft(double value)](#setLeft-double) | 获取或设置问题左侧位置 |
| [setName(String value)](#setName-java.lang.String) | 设置问题名称 |
| [setOrientation(int value)](#setOrientation-int) |  |
| [setTop(double value)](#setTop-double) | 获取或设置问题顶部位置 |
| [setWidth(double value)](#setWidth-double) | 获取或设置问题宽度 |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| choiceBox | [ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) |  |

### addChoiceBox(String name, int width, int height, int top, int left) {#addChoiceBox-java.lang.String-int-int-int-int}
```
public final ChoiceBoxElement addChoiceBox(String name, int width, int height, int top, int left)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |
| 宽度 | int |  |
| 高度 | int |  |
| 顶部 | int |  |
| 左侧 | int |  |

**Returns:**
[ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/)
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


获取或设置问题高度

**Returns:**
double - 高度
### getLeft() {#getLeft}
```
public final double getLeft()
```


获取或设置问题左侧位置

**Returns:**
double - 左侧
### getName() {#getName}
```
public final String getName()
```


获取问题名称

**Returns:**
java.lang.String - 问题名称
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


获取或设置问题顶部位置

**Returns:**
double - 顶部
### getWidth() {#getWidth}
```
public final double getWidth()
```


获取或设置问题宽度

**Returns:**
double - 宽度
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


获取或设置一个值，指示气泡是否水平对齐

**Returns:**
boolean - 指示气泡是否水平对齐的值
### isAlignedVertical() {#isAlignedVertical}
```
public final boolean isAlignedVertical()
```


获取或设置一个值，指示气泡是否垂直对齐

**Returns:**
boolean - 指示气泡是否垂直对齐的值
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


获取或设置一个值，指示气泡是否水平对齐

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean | 指示气泡是否水平对齐的值 |

### setAlignedVertical(boolean value) {#setAlignedVertical-boolean}
```
public final void setAlignedVertical(boolean value)
```


获取或设置一个值，指示气泡是否垂直对齐

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean | 指示气泡是否垂直对齐的值 |

### setChoiceBoxes(System.Collections.Generic.List<OmrElement> value) {#setChoiceBoxes-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement}
```
public final void setChoiceBoxes(System.Collections.Generic.List<OmrElement> value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrElement> |  |

### setHeight(double value) {#setHeight-double}
```
public final void setHeight(double value)
```


获取或设置问题高度

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 高度 |

### setLeft(double value) {#setLeft-double}
```
public final void setLeft(double value)
```


获取或设置问题左侧位置

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 左侧 |

### setName(String value) {#setName-java.lang.String}
```
public final void setName(String value)
```


设置问题名称

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 问题名称 |

### setOrientation(int value) {#setOrientation-int}
```
public final void setOrientation(int value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setTop(double value) {#setTop-double}
```
public final void setTop(double value)
```


获取或设置问题顶部位置

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 顶部 |

### setWidth(double value) {#setWidth-double}
```
public final void setWidth(double value)
```


获取或设置问题宽度

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 宽度 |

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

