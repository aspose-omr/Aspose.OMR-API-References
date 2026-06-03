---
title: "ChoiceBoxElement"
second_title: "Справочник API Aspose.OMR для Java"
description: "Представляет вопрос ChoiceBox"
type: docs
weight: 11
url: /ru/java/com.aspose.omr/choiceboxelement/
---

**Inheritance:**
java.lang.Object, [com.aspose.omr.OmrElement](../../com.aspose.omr/omrelement/)
```
public class ChoiceBoxElement extends OmrElement
```

Представляет вопрос ChoiceBox
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ChoiceBoxElement()](#ChoiceBoxElement) | Инициализирует новый экземпляр класса [ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) |
## Поля

| Поле | Описание |
| --- | --- |
| [ElementType](#ElementType) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [addBubble(String name, int width, int height, int top, int left, boolean isValid)](#addBubble-java.lang.String-int-int-int-int-boolean) | Добавляет пузырёк внутри вопроса |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getBubbleHeight()](#getBubbleHeight) |  |
| [getBubbleWidth()](#getBubbleWidth) |  |
| [getBubbles()](#getBubbles) | Получает или задаёт коллекцию пузырьков |
| [getClass()](#getClass) |  |
| [getHeight()](#getHeight) | Получает или задает высоту вопроса |
| [getLeft()](#getLeft) | Получает или задает левую позицию вопроса |
| [getMultipleSelectionAllowed()](#getMultipleSelectionAllowed) | Получает или задаёт значение, указывающее, разрешён ли множественный выбор |
| [getName()](#getName) | Получает имя вопроса |
| [getOrientation()](#getOrientation) |  |
| [getOrientationString()](#getOrientationString) | Получает строковое представление свойства ориентации |
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
| [setBubbleHeight(double value)](#setBubbleHeight-double) |  |
| [setBubbleWidth(double value)](#setBubbleWidth-double) |  |
| [setBubbles(System.Collections.Generic.List<OmrBubble> value)](#setBubbles-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrBubble) | Получает или задаёт коллекцию пузырьков |
| [setHeight(double value)](#setHeight-double) | Получает или задает высоту вопроса |
| [setLeft(double value)](#setLeft-double) | Получает или задает левую позицию вопроса |
| [setMultipleSelectionAllowed(boolean value)](#setMultipleSelectionAllowed-boolean) | Получает или задаёт значение, указывающее, разрешён ли множественный выбор |
| [setName(String value)](#setName-java.lang.String) | Задает имя вопроса |
| [setOrientation(int value)](#setOrientation-int) |  |
| [setTop(double value)](#setTop-double) | Получает или задает верхнюю позицию вопроса |
| [setWidth(double value)](#setWidth-double) | Получает или задает ширину вопроса |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### ChoiceBoxElement() {#ChoiceBoxElement}
```
public ChoiceBoxElement()
```


Инициализирует новый экземпляр класса [ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/)

### ElementType {#ElementType}
```
public String ElementType
```


### addBubble(String name, int width, int height, int top, int left, boolean isValid) {#addBubble-java.lang.String-int-int-int-int-boolean}
```
public final void addBubble(String name, int width, int height, int top, int left, boolean isValid)
```


Добавляет пузырёк внутри вопроса

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String | Имя пузырька |
| ширина | int | Ширина пузырька |
| высота | int | Высота пузырька |
| верх | int | Верхняя позиция пузырька |
| лево | int | Левая позиция пузырька |
| isValid | boolean | Флаг валидности пузырька |

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


Получает или задаёт коллекцию пузырьков

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrBubble> - коллекция пузырьков
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
### getMultipleSelectionAllowed() {#getMultipleSelectionAllowed}
```
public final boolean getMultipleSelectionAllowed()
```


Получает или задаёт значение, указывающее, разрешён ли множественный выбор

**Returns:**
boolean - значение, указывающее, разрешён ли множественный выбор
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


Получает строковое представление свойства ориентации

**Returns:**
java.lang.String - строковое представление свойства ориентации
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

### setBubbleHeight(double value) {#setBubbleHeight-double}
```
public final void setBubbleHeight(double value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setBubbleWidth(double value) {#setBubbleWidth-double}
```
public final void setBubbleWidth(double value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setBubbles(System.Collections.Generic.List<OmrBubble> value) {#setBubbles-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrBubble}
```
public final void setBubbles(System.Collections.Generic.List<OmrBubble> value)
```


Получает или задаёт коллекцию пузырьков

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrBubble> | коллекция пузырьков |

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

### setMultipleSelectionAllowed(boolean value) {#setMultipleSelectionAllowed-boolean}
```
public final void setMultipleSelectionAllowed(boolean value)
```


Получает или задаёт значение, указывающее, разрешён ли множественный выбор

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | значение, указывающее, разрешён ли множественный выбор |

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

