---
title: "GridElement"
second_title: "Справочник API Aspose.OMR для Java"
description: 
type: docs
weight: 16
url: /ru/java/com.aspose.omr/gridelement/
---

**Inheritance:**
java.lang.Object, [com.aspose.omr.OmrElement](../../com.aspose.omr/omrelement/)
```
public class GridElement extends OmrElement
```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [GridElement()](#GridElement) |  |
## Поля

| Поле | Описание |
| --- | --- |
| [ElementType](#ElementType) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [addChoiceBox(ChoiceBoxElement choiceBox)](#addChoiceBox-com.aspose.omr.ChoiceBoxElement) |  |
| [addChoiceBox(String name, int width, int height, int top, int left)](#addChoiceBox-java.lang.String-int-int-int-int) |  |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getChoiceBoxes()](#getChoiceBoxes) |  |
| [getClass()](#getClass) |  |
| [getHeight()](#getHeight) | Получает или задает высоту вопроса |
| [getLeft()](#getLeft) | Получает или задает левую позицию вопроса |
| [getName()](#getName) | Получает имя вопроса |
| [getOrientation()](#getOrientation) |  |
| [getOrientationString()](#getOrientationString) |  |
| [getRect()](#getRect) |  |
| [getTop()](#getTop) | Получает или задает верхнюю позицию вопроса |
| [getWidth()](#getWidth) | Получает или задает ширину вопроса |
| [hashCode()](#hashCode) |  |
| [isAlignedHorizontal()](#isAlignedHorizontal) | Получает или задает значение, указывающее, выровнены ли пузыри по горизонтали |
| [isAlignedVertical()](#isAlignedVertical) | Получает или задает значение, указывающее, выровнены ли пузыри по вертикали |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [setAlignedHorizontal(boolean value)](#setAlignedHorizontal-boolean) | Получает или задает значение, указывающее, выровнены ли пузыри по горизонтали |
| [setAlignedVertical(boolean value)](#setAlignedVertical-boolean) | Получает или задает значение, указывающее, выровнены ли пузыри по вертикали |
| [setChoiceBoxes(System.Collections.Generic.List<OmrElement> value)](#setChoiceBoxes-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement) |  |
| [setHeight(double value)](#setHeight-double) | Получает или задает высоту вопроса |
| [setLeft(double value)](#setLeft-double) | Получает или задает левую позицию вопроса |
| [setName(String value)](#setName-java.lang.String) | Задает имя вопроса |
| [setOrientation(int value)](#setOrientation-int) |  |
| [setTop(double value)](#setTop-double) | Получает или задает верхнюю позицию вопроса |
| [setWidth(double value)](#setWidth-double) | Получает или задает ширину вопроса |
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| choiceBox | [ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) |  |

### addChoiceBox(String name, int width, int height, int top, int left) {#addChoiceBox-java.lang.String-int-int-int-int}
```
public final ChoiceBoxElement addChoiceBox(String name, int width, int height, int top, int left)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String |  |
| ширина | int |  |
| высота | int |  |
| верх | int |  |
| лево | int |  |

**Returns:**
[ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/)
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


Получает или задает высоту вопроса

**Returns:**
double - Высота
### getLeft() {#getLeft}
```
public final double getLeft()
```


Получает или задает левую позицию вопроса

**Returns:**
double - Левый
### getName() {#getName}
```
public final String getName()
```


Получает имя вопроса

**Returns:**
java.lang.String - Имя вопроса
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


Получает или задает верхнюю позицию вопроса

**Returns:**
double - Верх
### getWidth() {#getWidth}
```
public final double getWidth()
```


Получает или задает ширину вопроса

**Returns:**
double - Ширина
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


Получает или задает значение, указывающее, выровнены ли пузыри по горизонтали

**Returns:**
boolean — значение, указывающее, выровнены ли пузыри по горизонтали
### isAlignedVertical() {#isAlignedVertical}
```
public final boolean isAlignedVertical()
```


Получает или задает значение, указывающее, выровнены ли пузыри по вертикали

**Returns:**
boolean — значение, указывающее, выровнены ли пузыри по вертикали
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


Получает или задает значение, указывающее, выровнены ли пузыри по горизонтали

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | значение, указывающее, выровнены ли пузыри по горизонтали |

### setAlignedVertical(boolean value) {#setAlignedVertical-boolean}
```
public final void setAlignedVertical(boolean value)
```


Получает или задает значение, указывающее, выровнены ли пузыри по вертикали

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | значение, указывающее, выровнены ли пузыри по вертикали |

### setChoiceBoxes(System.Collections.Generic.List<OmrElement> value) {#setChoiceBoxes-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement}
```
public final void setChoiceBoxes(System.Collections.Generic.List<OmrElement> value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrElement> |  |

### setHeight(double value) {#setHeight-double}
```
public final void setHeight(double value)
```


Получает или задает высоту вопроса

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Высота |

### setLeft(double value) {#setLeft-double}
```
public final void setLeft(double value)
```


Получает или задает левую позицию вопроса

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Левый |

### setName(String value) {#setName-java.lang.String}
```
public final void setName(String value)
```


Задает имя вопроса

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Имя вопроса |

### setOrientation(int value) {#setOrientation-int}
```
public final void setOrientation(int value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setTop(double value) {#setTop-double}
```
public final void setTop(double value)
```


Получает или задает верхнюю позицию вопроса

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Верх |

### setWidth(double value) {#setWidth-double}
```
public final void setWidth(double value)
```


Получает или задает ширину вопроса

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Ширина |

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

