---
title: "GridElement"
second_title: "Aspose.OMR for Java API リファレンス"
description: 
type: docs
weight: 16
url: /ja/java/com.aspose.omr/gridelement/
---

**Inheritance:**
java.lang.Object, [com.aspose.omr.OmrElement](../../com.aspose.omr/omrelement/)
```
public class GridElement extends OmrElement
```
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [GridElement()](#GridElement) |  |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [ElementType](#ElementType) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addChoiceBox(ChoiceBoxElement choiceBox)](#addChoiceBox-com.aspose.omr.ChoiceBoxElement) |  |
| [addChoiceBox(String name, int width, int height, int top, int left)](#addChoiceBox-java.lang.String-int-int-int-int) |  |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getChoiceBoxes()](#getChoiceBoxes) |  |
| [getClass()](#getClass) |  |
| [getHeight()](#getHeight) | 質問の高さを取得または設定します |
| [getLeft()](#getLeft) | 質問の左位置を取得または設定します |
| [getName()](#getName) | 質問名を取得します |
| [getOrientation()](#getOrientation) |  |
| [getOrientationString()](#getOrientationString) |  |
| [getRect()](#getRect) |  |
| [getTop()](#getTop) | 質問の上位置を取得または設定します |
| [getWidth()](#getWidth) | 質問の幅を取得または設定します |
| [hashCode()](#hashCode) |  |
| [isAlignedHorizontal()](#isAlignedHorizontal) | バブルが水平に配置されているかどうかを示す値を取得または設定します |
| [isAlignedVertical()](#isAlignedVertical) | バブルが垂直に配置されているかどうかを示す値を取得または設定します |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [setAlignedHorizontal(boolean value)](#setAlignedHorizontal-boolean) | バブルが水平に配置されているかどうかを示す値を取得または設定します |
| [setAlignedVertical(boolean value)](#setAlignedVertical-boolean) | バブルが垂直に配置されているかどうかを示す値を取得または設定します |
| [setChoiceBoxes(System.Collections.Generic.List<OmrElement> value)](#setChoiceBoxes-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement) |  |
| [setHeight(double value)](#setHeight-double) | 質問の高さを取得または設定します |
| [setLeft(double value)](#setLeft-double) | 質問の左位置を取得または設定します |
| [setName(String value)](#setName-java.lang.String) | 質問名を設定します |
| [setOrientation(int value)](#setOrientation-int) |  |
| [setTop(double value)](#setTop-double) | 質問の上位置を取得または設定します |
| [setWidth(double value)](#setWidth-double) | 質問の幅を取得または設定します |
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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| choiceBox | [ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) |  |

### addChoiceBox(String name, int width, int height, int top, int left) {#addChoiceBox-java.lang.String-int-int-int-int}
```
public final ChoiceBoxElement addChoiceBox(String name, int width, int height, int top, int left)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 名前 | java.lang.String |  |
| 幅 | int |  |
| 高さ | int |  |
| 上 | int |  |
| 左 | int |  |

**Returns:**
[ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/)
### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
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


質問の高さを取得または設定します

**Returns:**
double - 高さ
### getLeft() {#getLeft}
```
public final double getLeft()
```


質問の左位置を取得または設定します

**Returns:**
double - 左
### getName() {#getName}
```
public final String getName()
```


質問名を取得します

**Returns:**
java.lang.String - 質問名
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


質問の上位置を取得または設定します

**Returns:**
double - 上
### getWidth() {#getWidth}
```
public final double getWidth()
```


質問の幅を取得または設定します

**Returns:**
double - 幅
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


バブルが水平に配置されているかどうかを示す値を取得または設定します

**Returns:**
boolean - バブルが水平に配置されているかどうかを示す値
### isAlignedVertical() {#isAlignedVertical}
```
public final boolean isAlignedVertical()
```


バブルが垂直に配置されているかどうかを示す値を取得または設定します

**Returns:**
boolean - バブルが垂直に配置されているかどうかを示す値
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


バブルが水平に配置されているかどうかを示す値を取得または設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean | バブルが水平に配置されているかどうかを示す値 |

### setAlignedVertical(boolean value) {#setAlignedVertical-boolean}
```
public final void setAlignedVertical(boolean value)
```


バブルが垂直に配置されているかどうかを示す値を取得または設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean | バブルが垂直に配置されているかどうかを示す値 |

### setChoiceBoxes(System.Collections.Generic.List<OmrElement> value) {#setChoiceBoxes-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement}
```
public final void setChoiceBoxes(System.Collections.Generic.List<OmrElement> value)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrElement> |  |

### setHeight(double value) {#setHeight-double}
```
public final void setHeight(double value)
```


質問の高さを取得または設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double | 高さ |

### setLeft(double value) {#setLeft-double}
```
public final void setLeft(double value)
```


質問の左位置を取得または設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double | 左 |

### setName(String value) {#setName-java.lang.String}
```
public final void setName(String value)
```


質問名を設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 質問名 |

### setOrientation(int value) {#setOrientation-int}
```
public final void setOrientation(int value)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setTop(double value) {#setTop-double}
```
public final void setTop(double value)
```


質問の上位置を取得または設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double | 上 |

### setWidth(double value) {#setWidth-double}
```
public final void setWidth(double value)
```


質問の幅を取得または設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double | 幅 |

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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

