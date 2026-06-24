---
title: "ChoiceBoxElement"
second_title: "Aspose.OMR for Java API 参考"
description: "表示 ChoiceBox 问题"
type: docs
weight: 11
url: /zh/java/com.aspose.omr/choiceboxelement/
---

**Inheritance:**
java.lang.Object, [com.aspose.omr.OmrElement](../../com.aspose.omr/omrelement/)
```
public class ChoiceBoxElement extends OmrElement
```

表示 ChoiceBox 问题
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ChoiceBoxElement()](#ChoiceBoxElement) | 初始化一个新的 [ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) 类实例 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [ElementType](#ElementType) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [addBubble(String name, int width, int height, int top, int left, boolean isValid)](#addBubble-java.lang.String-int-int-int-int-boolean) | 在问题中添加气泡 |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getBubbleHeight()](#getBubbleHeight) |  |
| [getBubbleWidth()](#getBubbleWidth) |  |
| [getBubbles()](#getBubbles) | 获取或设置气泡集合 |
| [getClass()](#getClass) |  |
| [getHeight()](#getHeight) | 获取或设置问题高度 |
| [getLeft()](#getLeft) | 获取或设置问题左侧位置 |
| [getMultipleSelectionAllowed()](#getMultipleSelectionAllowed) | 获取或设置一个指示是否允许多选的值 |
| [getName()](#getName) | 获取问题名称 |
| [getOrientation()](#getOrientation) |  |
| [getOrientationString()](#getOrientationString) | 获取方向属性的字符串表示 |
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
| [setBubbleHeight(double value)](#setBubbleHeight-double) |  |
| [setBubbleWidth(double value)](#setBubbleWidth-double) |  |
| [setBubbles(System.Collections.Generic.List<OmrBubble> value)](#setBubbles-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrBubble) | 获取或设置气泡集合 |
| [setHeight(double value)](#setHeight-double) | 获取或设置问题高度 |
| [setLeft(double value)](#setLeft-double) | 获取或设置问题左侧位置 |
| [setMultipleSelectionAllowed(boolean value)](#setMultipleSelectionAllowed-boolean) | 获取或设置一个指示是否允许多选的值 |
| [setName(String value)](#setName-java.lang.String) | 设置问题名称 |
| [setOrientation(int value)](#setOrientation-int) |  |
| [setTop(double value)](#setTop-double) | 获取或设置问题顶部位置 |
| [setWidth(double value)](#setWidth-double) | 获取或设置问题宽度 |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### ChoiceBoxElement() {#ChoiceBoxElement}
```
public ChoiceBoxElement()
```


初始化一个新的 [ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) 类实例

### ElementType {#ElementType}
```
public String ElementType
```


### addBubble(String name, int width, int height, int top, int left, boolean isValid) {#addBubble-java.lang.String-int-int-int-int-boolean}
```
public final void addBubble(String name, int width, int height, int top, int left, boolean isValid)
```


在问题中添加气泡

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 气泡名称 |
| 宽度 | int | 气泡宽度 |
| 高度 | int | 气泡高度 |
| 顶部 | int | 气泡顶部位置 |
| 左侧 | int | 气泡左侧位置 |
| isValid | boolean | 气泡有效标志 |

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


获取或设置气泡集合

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrBubble> - 气泡集合
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
### getMultipleSelectionAllowed() {#getMultipleSelectionAllowed}
```
public final boolean getMultipleSelectionAllowed()
```


获取或设置一个指示是否允许多选的值

**Returns:**
boolean - 指示是否允许多选的值
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


获取方向属性的字符串表示

**Returns:**
java.lang.String - 方向属性的字符串表示
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

### setBubbleHeight(double value) {#setBubbleHeight-double}
```
public final void setBubbleHeight(double value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setBubbleWidth(double value) {#setBubbleWidth-double}
```
public final void setBubbleWidth(double value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setBubbles(System.Collections.Generic.List<OmrBubble> value) {#setBubbles-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrBubble}
```
public final void setBubbles(System.Collections.Generic.List<OmrBubble> value)
```


获取或设置气泡集合

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrBubble> | 气泡集合 |

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

### setMultipleSelectionAllowed(boolean value) {#setMultipleSelectionAllowed-boolean}
```
public final void setMultipleSelectionAllowed(boolean value)
```


获取或设置一个指示是否允许多选的值

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean | 一个指示是否允许多选的值 |

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

