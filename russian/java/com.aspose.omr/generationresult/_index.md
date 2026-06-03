---
title: "GenerationResult"
second_title: "Справочник API Aspose.OMR для Java"
description: "Результат генерации шаблона"
type: docs
weight: 14
url: /ru/java/com.aspose.omr/generationresult/
---

**Inheritance:**
java.lang.Object
```
public class GenerationResult
```

Результат генерации шаблона. Содержит изображение шаблона и сам шаблон (json, описывающий расположение элементов на изображении).
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [getErrorCode()](#getErrorCode) | Получает или задает код ошибки. |
| [getErrorMessage()](#getErrorMessage) | Получает или задает сообщение, описывающее ошибку. |
| [getTemplate()](#getTemplate) | Получает строку JSON шаблона |
| [getTemplateImage()](#getTemplateImage) | Получает или задает сгенерированное изображение шаблона |
| [getWarnings()](#getWarnings) | Получает или задает список сообщений предупреждений, описывающих некритические ошибки, возникшие во время генерации |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [save(String folder, String name)](#save-java.lang.String-java.lang.String) | Сохранить изображение шаблона и шаблон в указанную папку |
| [setErrorCode(int value)](#setErrorCode-int) | Получает или задает код ошибки. |
| [setErrorMessage(String value)](#setErrorMessage-java.lang.String) | Получает или задает сообщение, описывающее ошибку. |
| [setTemplate(String value)](#setTemplate-java.lang.String) | Задает строку JSON шаблона |
| [setTemplateImage(BufferedImage value)](#setTemplateImage-java.awt.image.BufferedImage) | Получает или задает сгенерированное изображение шаблона |
| [setWarnings(List<String> value)](#setWarnings-java.util.List-java.lang.String) | Получает или задает список сообщений предупреждений, описывающих некритические ошибки, возникшие во время генерации |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
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
### getErrorCode() {#getErrorCode}
```
public final int getErrorCode()
```


Получает или задает код ошибки. Равен 0, если ошибки не произошли.

**Returns:**
int — код ошибки
### getErrorMessage() {#getErrorMessage}
```
public final String getErrorMessage()
```


Получает или задает сообщение, описывающее ошибку. Пусто, если ошибки не произошли.

**Returns:**
java.lang.String — сообщение, описывающее ошибку
### getTemplate() {#getTemplate}
```
public final String getTemplate()
```


Получает строку JSON шаблона

**Returns:**
java.lang.String — строка JSON шаблона
### getTemplateImage() {#getTemplateImage}
```
public final BufferedImage getTemplateImage()
```


Получает или задает сгенерированное изображение шаблона

**Returns:**
java.awt.image.BufferedImage
### getWarnings() {#getWarnings}
```
public final List<String> getWarnings()
```


Получает или задает список сообщений предупреждений, описывающих некритические ошибки, возникшие во время генерации

**Returns:**
java.util.List<java.lang.String>
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




### save(String folder, String name) {#save-java.lang.String-java.lang.String}
```
public final void save(String folder, String name)
```


Сохранить изображение шаблона и шаблон в указанную папку

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| папка | java.lang.String | Папка назначения |
| имя | java.lang.String | Имя шаблона |

### setErrorCode(int value) {#setErrorCode-int}
```
public final void setErrorCode(int value)
```


Получает или задает код ошибки. Равен 0, если ошибки не произошли.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | код ошибки |

### setErrorMessage(String value) {#setErrorMessage-java.lang.String}
```
public final void setErrorMessage(String value)
```


Получает или задает сообщение, описывающее ошибку. Пусто, если ошибки не произошли.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | сообщение, описывающее ошибку |

### setTemplate(String value) {#setTemplate-java.lang.String}
```
public final void setTemplate(String value)
```


Задает строку JSON шаблона

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | строка JSON шаблона |

### setTemplateImage(BufferedImage value) {#setTemplateImage-java.awt.image.BufferedImage}
```
public final void setTemplateImage(BufferedImage value)
```


Получает или задает сгенерированное изображение шаблона

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.awt.image.BufferedImage |  |

### setWarnings(List<String> value) {#setWarnings-java.util.List-java.lang.String}
```
public final void setWarnings(List<String> value)
```


Получает или задает список сообщений предупреждений, описывающих некритические ошибки, возникшие во время генерации

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.List<java.lang.String> |  |

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

