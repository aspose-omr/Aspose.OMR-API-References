---
title: "OmrEngine"
second_title: "Aspose.OMR for Java API 参考"
description: "OMR 引擎"
type: docs
weight: 22
url: /zh/java/com.aspose.omr/omrengine/
---

**Inheritance:**
java.lang.Object
```
public class OmrEngine
```

OMR 引擎。负责模板和图像处理类以及 GUI 组件的创建。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [OmrEngine()](#OmrEngine) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [generateTemplate(String markupPath)](#generateTemplate-java.lang.String) | 基于文本标记创建模板（.omr）和模板图像 |
| [generateTemplate(String markupPath, GlobalPageSettings settings)](#generateTemplate-java.lang.String-com.aspose.omr.GlobalPageSettings) | 基于文本标记创建模板（.omr）和模板图像 |
| [generateTemplate(String markupPath, ImageCollection collection)](#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection) | 基于文本标记创建模板（.omr）和模板图像 |
| [generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings)](#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection-com.aspose.omr.GlobalPageSettings) | 基于文本标记创建模板（.omr）和模板图像 |
| [getClass()](#getClass) |  |
| [getTemplateProcessor(InputStream inputStream)](#getTemplateProcessor-java.io.InputStream) | 创建允许使用指定模板的 [TemplateProcessor](../../com.aspose.omr/templateprocessor/) 实例。 |
| [getTemplateProcessor(String templatePath)](#getTemplateProcessor-java.lang.String) | 创建允许使用指定模板的 [TemplateProcessor](../../com.aspose.omr/templateprocessor/) 实例。 |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateTemplate(String markupPath) {#generateTemplate-java.lang.String}
```
public final GenerationResult generateTemplate(String markupPath)
```


基于文本标记创建模板（.omr）和模板图像

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| markupPath | java.lang.String | 文本标记文件的路径 |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, GlobalPageSettings settings) {#generateTemplate-java.lang.String-com.aspose.omr.GlobalPageSettings}
```
public final GenerationResult generateTemplate(String markupPath, GlobalPageSettings settings)
```


基于文本标记创建模板（.omr）和模板图像

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| markupPath | java.lang.String | 文本标记文件的路径 |
| settings | [GlobalPageSettings](../../com.aspose.omr/globalpagesettings/) | 每页的全局设置 |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, ImageCollection collection) {#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection}
```
public final GenerationResult generateTemplate(String markupPath, ImageCollection collection)
```


基于文本标记创建模板（.omr）和模板图像

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| markupPath | java.lang.String | 文本标记文件的路径 |
| collection | [ImageCollection](../../com.aspose.omr/imagecollection/) | 在此模板生成中使用的图像集合 |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings) {#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection-com.aspose.omr.GlobalPageSettings}
```
public final GenerationResult generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings)
```


基于文本标记创建模板（.omr）和模板图像

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| markupPath | java.lang.String | 文本标记文件的路径 |
| collection | [ImageCollection](../../com.aspose.omr/imagecollection/) | 在此模板生成中使用的图像集合 |
| settings | [GlobalPageSettings](../../com.aspose.omr/globalpagesettings/) | 每页的全局设置 |

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


创建允许使用指定模板的 [TemplateProcessor](../../com.aspose.omr/templateprocessor/) 实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | OMR 模板文件的内容流 |

**Returns:**
[TemplateProcessor](../../com.aspose.omr/templateprocessor/) - The [TemplateProcessor](../../com.aspose.omr/templateprocessor/) instance
### getTemplateProcessor(String templatePath) {#getTemplateProcessor-java.lang.String}
```
public final TemplateProcessor getTemplateProcessor(String templatePath)
```


创建允许使用指定模板的 [TemplateProcessor](../../com.aspose.omr/templateprocessor/) 实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| templatePath | java.lang.String | OMR 模板文件的路径 |

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

