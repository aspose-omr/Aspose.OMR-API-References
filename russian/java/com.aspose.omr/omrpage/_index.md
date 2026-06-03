---
title: "OmrPage"
second_title: "Справочник API Aspose.OMR для Java"
description: "Представляет отдельную страницу OMR"
type: docs
weight: 24
url: /ru/java/com.aspose.omr/omrpage/
---

**Inheritance:**
java.lang.Object
```
public class OmrPage
```

Представляет отдельную страницу OMR
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [OmrPage()](#OmrPage) | Инициализирует новый экземпляр класса [OmrPage](../../com.aspose.omr/omrpage/) |
## Методы

| Метод | Описание |
| --- | --- |
| [addBarcodeElement(BarcodeElement element)](#addBarcodeElement-com.aspose.omr.BarcodeElement) |  |
| [addChoiceBoxElement(String name, int width, int height, int top, int left)](#addChoiceBoxElement-java.lang.String-int-int-int-int) | Добавить элемент поля выбора на страницу |
| [addClipAreaElement(String name, int width, int height, int top, int left)](#addClipAreaElement-java.lang.String-int-int-int-int) |  |
| [addGridElement(GridElement grid)](#addGridElement-com.aspose.omr.GridElement) |  |
| [addGridElement(String name, int width, int height, int top, int left)](#addGridElement-java.lang.String-int-int-int-int) |  |
| [addRefPointElement(ReferencePointElement item)](#addRefPointElement-com.aspose.omr.ReferencePointElement) |  |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [getElements()](#getElements) | Получает или задает список элементов на странице |
| [getHeight()](#getHeight) | Получает или задает высоту страницы |
| [getImageFormat()](#getImageFormat) | Получает или задает формат файла изображения |
| [getImageName()](#getImageName) | Получает или задает данные изображения |
| [getRotationPointPosition()](#getRotationPointPosition) | Получает или задает RotationPointPosition |
| [getWidth()](#getWidth) | Получает или задает ширину страницы |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [setElements(System.Collections.Generic.List<OmrElement> value)](#setElements-com.aspose.ms.System.Collections.Generic.List-com.aspose.omr.OmrElement) | Получает или задает список элементов на странице |
| [setHeight(double value)](#setHeight-double) | Получает или задает высоту страницы |
| [setImageFormat(String value)](#setImageFormat-java.lang.String) | Получает или задает формат файла изображения |
| [setImageName(String value)](#setImageName-java.lang.String) | Получает или задает имя изображения |
| [setRotationPointPosition(RotationPointPosition value)](#setRotationPointPosition-com.aspose.omr.RotationPointPosition) | Получает или задает RotationPointPosition |
| [setWidth(double value)](#setWidth-double) | Получает или задает ширину страницы |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### OmrPage() {#OmrPage}
```
public OmrPage()
```


Инициализирует новый экземпляр класса [OmrPage](../../com.aspose.omr/omrpage/)

### addBarcodeElement(BarcodeElement element) {#addBarcodeElement-com.aspose.omr.BarcodeElement}
```
public final void addBarcodeElement(BarcodeElement element)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [BarcodeElement](../../com.aspose.omr/barcodeelement/) |  |

### addChoiceBoxElement(String name, int width, int height, int top, int left) {#addChoiceBoxElement-java.lang.String-int-int-int-int}
```
public final ChoiceBoxElement addChoiceBoxElement(String name, int width, int height, int top, int left)
```


Добавить элемент поля выбора на страницу

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String | Имя элемента |
| ширина | int | Ширина элемента |
| высота | int | Высота элемента |
| верх | int | Позиция верхнего края элемента |
| лево | int | Позиция левого края элемента |

**Returns:**
[ChoiceBoxElement](../../com.aspose.omr/choiceboxelement/) - Created choice box
### addClipAreaElement(String name, int width, int height, int top, int left) {#addClipAreaElement-java.lang.String-int-int-int-int}
```
public final ClipAreaElement addClipAreaElement(String name, int width, int height, int top, int left)
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
[ClipAreaElement](../../com.aspose.omr/clipareaelement/)
### addGridElement(GridElement grid) {#addGridElement-com.aspose.omr.GridElement}
```
public final void addGridElement(GridElement grid)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| grid | [GridElement](../../com.aspose.omr/gridelement/) |  |

### addGridElement(String name, int width, int height, int top, int left) {#addGridElement-java.lang.String-int-int-int-int}
```
public final GridElement addGridElement(String name, int width, int height, int top, int left)
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
[GridElement](../../com.aspose.omr/gridelement/)
### addRefPointElement(ReferencePointElement item) {#addRefPointElement-com.aspose.omr.ReferencePointElement}
```
public final void addRefPointElement(ReferencePointElement item)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [ReferencePointElement](../../com.aspose.omr/referencepointelement/) |  |

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


Получает или задает список элементов на странице

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrElement> - список элементов на странице
### getHeight() {#getHeight}
```
public final double getHeight()
```


Получает или задает высоту страницы

**Returns:**
double - высота страницы
### getImageFormat() {#getImageFormat}
```
public final String getImageFormat()
```


Получает или задает формат файла изображения

**Returns:**
java.lang.String - формат файла изображения
### getImageName() {#getImageName}
```
public final String getImageName()
```


Получает или задает данные изображения

**Returns:**
java.lang.String - имя изображения
### getRotationPointPosition() {#getRotationPointPosition}
```
public final RotationPointPosition getRotationPointPosition()
```


Получает или задает RotationPointPosition

**Returns:**
[RotationPointPosition](../../com.aspose.omr/rotationpointposition/) - RotationPointPosition
### getWidth() {#getWidth}
```
public final double getWidth()
```


Получает или задает ширину страницы

**Returns:**
double - ширина страницы
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


Получает или задает список элементов на странице

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | com.aspose.ms.System.Collections.Generic.List<com.aspose.omr.OmrElement> | список элементов на странице |

### setHeight(double value) {#setHeight-double}
```
public final void setHeight(double value)
```


Получает или задает высоту страницы

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | высота страницы |

### setImageFormat(String value) {#setImageFormat-java.lang.String}
```
public final void setImageFormat(String value)
```


Получает или задает формат файла изображения

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | формат файла изображения |

### setImageName(String value) {#setImageName-java.lang.String}
```
public final void setImageName(String value)
```


Получает или задает имя изображения

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Имя изображения |

### setRotationPointPosition(RotationPointPosition value) {#setRotationPointPosition-com.aspose.omr.RotationPointPosition}
```
public final void setRotationPointPosition(RotationPointPosition value)
```


Получает или задает RotationPointPosition

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RotationPointPosition](../../com.aspose.omr/rotationpointposition/) | RotationPointPosition |

### setWidth(double value) {#setWidth-double}
```
public final void setWidth(double value)
```


Получает или задает ширину страницы

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Ширина страницы |

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

