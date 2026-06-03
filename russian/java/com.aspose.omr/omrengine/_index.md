---
title: "OmrEngine"
second_title: "Справочник API Aspose.OMR для Java"
description: "Движок OMR"
type: docs
weight: 22
url: /ru/java/com.aspose.omr/omrengine/
---

**Inheritance:**
java.lang.Object
```
public class OmrEngine
```

Движок OMR. Обрабатывает создание шаблона, классов обработки изображений и компонентов графического интерфейса.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [OmrEngine()](#OmrEngine) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [generateTemplate(String markupPath)](#generateTemplate-java.lang.String) | Создаёт шаблон (.omr) и изображение шаблона на основе разметки текста |
| [generateTemplate(String markupPath, GlobalPageSettings settings)](#generateTemplate-java.lang.String-com.aspose.omr.GlobalPageSettings) | Создаёт шаблон (.omr) и изображение шаблона на основе разметки текста |
| [generateTemplate(String markupPath, ImageCollection collection)](#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection) | Создаёт шаблон (.omr) и изображение шаблона на основе разметки текста |
| [generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings)](#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection-com.aspose.omr.GlobalPageSettings) | Создаёт шаблон (.omr) и изображение шаблона на основе разметки текста |
| [getClass()](#getClass) |  |
| [getTemplateProcessor(InputStream inputStream)](#getTemplateProcessor-java.io.InputStream) | Создает [TemplateProcessor](../../com.aspose.omr/templateprocessor/) экземпляр, который позволяет работать с указанным шаблоном. |
| [getTemplateProcessor(String templatePath)](#getTemplateProcessor-java.lang.String) | Создает [TemplateProcessor](../../com.aspose.omr/templateprocessor/) экземпляр, который позволяет работать с указанным шаблоном. |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### OmrEngine() {#OmrEngine}
```
public OmrEngine()
```


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
### generateTemplate(String markupPath) {#generateTemplate-java.lang.String}
```
public final GenerationResult generateTemplate(String markupPath)
```


Создаёт шаблон (.omr) и изображение шаблона на основе разметки текста

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| markupPath | java.lang.String | Путь к файлу разметки текста |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, GlobalPageSettings settings) {#generateTemplate-java.lang.String-com.aspose.omr.GlobalPageSettings}
```
public final GenerationResult generateTemplate(String markupPath, GlobalPageSettings settings)
```


Создаёт шаблон (.omr) и изображение шаблона на основе разметки текста

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| markupPath | java.lang.String | Путь к файлу разметки текста |
| settings | [GlobalPageSettings](../../com.aspose.omr/globalpagesettings/) | глобальные настройки для каждой страницы |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, ImageCollection collection) {#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection}
```
public final GenerationResult generateTemplate(String markupPath, ImageCollection collection)
```


Создаёт шаблон (.omr) и изображение шаблона на основе разметки текста

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| markupPath | java.lang.String | Путь к файлу разметки текста |
| collection | [ImageCollection](../../com.aspose.omr/imagecollection/) | Коллекция изображений, используемых при генерации этого шаблона |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings) {#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection-com.aspose.omr.GlobalPageSettings}
```
public final GenerationResult generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings)
```


Создаёт шаблон (.omr) и изображение шаблона на основе разметки текста

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| markupPath | java.lang.String | Путь к файлу разметки текста |
| collection | [ImageCollection](../../com.aspose.omr/imagecollection/) | Коллекция изображений, используемых при генерации этого шаблона |
| settings | [GlobalPageSettings](../../com.aspose.omr/globalpagesettings/) | глобальные настройки для каждой страницы |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### getClass() {#getClass}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getTemplateProcessor(InputStream inputStream) {#getTemplateProcessor-java.io.InputStream}
```
public final TemplateProcessor getTemplateProcessor(InputStream inputStream)
```


Создает [TemplateProcessor](../../com.aspose.omr/templateprocessor/) экземпляр, который позволяет работать с указанным шаблоном.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | поток содержимого файла шаблона OMR |

**Returns:**
[TemplateProcessor](../../com.aspose.omr/templateprocessor/) - The [TemplateProcessor](../../com.aspose.omr/templateprocessor/) instance
### getTemplateProcessor(String templatePath) {#getTemplateProcessor-java.lang.String}
```
public final TemplateProcessor getTemplateProcessor(String templatePath)
```


Создает [TemplateProcessor](../../com.aspose.omr/templateprocessor/) экземпляр, который позволяет работать с указанным шаблоном.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| templatePath | java.lang.String | Путь к файлу шаблона OMR |

**Returns:**
[TemplateProcessor](../../com.aspose.omr/templateprocessor/) - The [TemplateProcessor](../../com.aspose.omr/templateprocessor/) instance
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

