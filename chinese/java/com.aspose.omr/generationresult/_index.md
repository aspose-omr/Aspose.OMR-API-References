---
title: "GenerationResult"
second_title: "Aspose.OMR for Java API 参考"
description: "模板生成的结果"
type: docs
weight: 14
url: /zh/java/com.aspose.omr/generationresult/
---

**Inheritance:**
java.lang.Object
```
public class GenerationResult
```

模板生成的结果。包含模板图像和模板（描述图像上元素位置的 json）。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [getErrorCode()](#getErrorCode) | 获取或设置错误代码。 |
| [getErrorMessage()](#getErrorMessage) | 获取或设置描述错误的消息。 |
| [getTemplate()](#getTemplate) | 获取模板 JSON 字符串 |
| [getTemplateImage()](#getTemplateImage) | 获取或设置生成的模板图像 |
| [getWarnings()](#getWarnings) | 获取或设置警告消息列表，描述生成过程中出现的非关键故障 |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [save(String folder, String name)](#save-java.lang.String-java.lang.String) | 将模板图像和模板保存到指定文件夹 |
| [setErrorCode(int value)](#setErrorCode-int) | 获取或设置错误代码。 |
| [setErrorMessage(String value)](#setErrorMessage-java.lang.String) | 获取或设置描述错误的消息。 |
| [setTemplate(String value)](#setTemplate-java.lang.String) | 设置模板 JSON 字符串 |
| [setTemplateImage(BufferedImage value)](#setTemplateImage-java.awt.image.BufferedImage) | 获取或设置生成的模板图像 |
| [setWarnings(List<String> value)](#setWarnings-java.util.List-java.lang.String) | 获取或设置警告消息列表，描述生成过程中出现的非关键故障 |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
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


获取或设置错误代码。如果没有错误发生，则等于 0。

**Returns:**
int - 错误代码
### getErrorMessage() {#getErrorMessage}
```
public final String getErrorMessage()
```


获取或设置描述错误的消息。如果没有错误发生，则为空。

**Returns:**
java.lang.String - 描述错误的消息
### getTemplate() {#getTemplate}
```
public final String getTemplate()
```


获取模板 JSON 字符串

**Returns:**
java.lang.String - 模板 JSON 字符串
### getTemplateImage() {#getTemplateImage}
```
public final BufferedImage getTemplateImage()
```


获取或设置生成的模板图像

**Returns:**
java.awt.image.BufferedImage
### getWarnings() {#getWarnings}
```
public final List<String> getWarnings()
```


获取或设置警告消息列表，描述生成过程中出现的非关键故障

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


将模板图像和模板保存到指定文件夹

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件夹 | java.lang.String | 目标文件夹 |
| 名称 | java.lang.String | 模板名称 |

### setErrorCode(int value) {#setErrorCode-int}
```
public final void setErrorCode(int value)
```


获取或设置错误代码。如果没有错误发生，则等于 0。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 错误代码 |

### setErrorMessage(String value) {#setErrorMessage-java.lang.String}
```
public final void setErrorMessage(String value)
```


获取或设置描述错误的消息。如果没有错误发生，则为空。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 描述错误的消息 |

### setTemplate(String value) {#setTemplate-java.lang.String}
```
public final void setTemplate(String value)
```


设置模板 JSON 字符串

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 模板 JSON 字符串 |

### setTemplateImage(BufferedImage value) {#setTemplateImage-java.awt.image.BufferedImage}
```
public final void setTemplateImage(BufferedImage value)
```


获取或设置生成的模板图像

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.awt.image.BufferedImage |  |

### setWarnings(List<String> value) {#setWarnings-java.util.List-java.lang.String}
```
public final void setWarnings(List<String> value)
```


获取或设置警告消息列表，描述生成过程中出现的非关键故障

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.util.List<java.lang.String> |  |

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

