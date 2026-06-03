---
title: "OmrEngine"
second_title: "Aspose.OMR for Java API 참조"
description: "OMR 엔진"
type: docs
weight: 22
url: /ko/java/com.aspose.omr/omrengine/
---

**Inheritance:**
java.lang.Object
```
public class OmrEngine
```

OMR 엔진. 템플릿 및 이미지 처리 클래스와 GUI 구성 요소의 생성을 처리합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [OmrEngine()](#OmrEngine) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [generateTemplate(String markupPath)](#generateTemplate-java.lang.String) | 텍스트 마크업을 기반으로 템플릿(.omr) 및 템플릿 이미지를 생성합니다 |
| [generateTemplate(String markupPath, GlobalPageSettings settings)](#generateTemplate-java.lang.String-com.aspose.omr.GlobalPageSettings) | 텍스트 마크업을 기반으로 템플릿(.omr) 및 템플릿 이미지를 생성합니다 |
| [generateTemplate(String markupPath, ImageCollection collection)](#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection) | 텍스트 마크업을 기반으로 템플릿(.omr) 및 템플릿 이미지를 생성합니다 |
| [generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings)](#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection-com.aspose.omr.GlobalPageSettings) | 텍스트 마크업을 기반으로 템플릿(.omr) 및 템플릿 이미지를 생성합니다 |
| [getClass()](#getClass) |  |
| [getTemplateProcessor(InputStream inputStream)](#getTemplateProcessor-java.io.InputStream) | 지정된 템플릿으로 작업할 수 있는 [TemplateProcessor](../../com.aspose.omr/templateprocessor/) 인스턴스를 생성합니다. |
| [getTemplateProcessor(String templatePath)](#getTemplateProcessor-java.lang.String) | 지정된 템플릿으로 작업할 수 있는 [TemplateProcessor](../../com.aspose.omr/templateprocessor/) 인스턴스를 생성합니다. |
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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateTemplate(String markupPath) {#generateTemplate-java.lang.String}
```
public final GenerationResult generateTemplate(String markupPath)
```


텍스트 마크업을 기반으로 템플릿(.omr) 및 템플릿 이미지를 생성합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| markupPath | java.lang.String | 텍스트 마크업 파일의 경로 |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, GlobalPageSettings settings) {#generateTemplate-java.lang.String-com.aspose.omr.GlobalPageSettings}
```
public final GenerationResult generateTemplate(String markupPath, GlobalPageSettings settings)
```


텍스트 마크업을 기반으로 템플릿(.omr) 및 템플릿 이미지를 생성합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| markupPath | java.lang.String | 텍스트 마크업 파일의 경로 |
| settings | [GlobalPageSettings](../../com.aspose.omr/globalpagesettings/) | 각 페이지에 대한 전역 설정 |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, ImageCollection collection) {#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection}
```
public final GenerationResult generateTemplate(String markupPath, ImageCollection collection)
```


텍스트 마크업을 기반으로 템플릿(.omr) 및 템플릿 이미지를 생성합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| markupPath | java.lang.String | 텍스트 마크업 파일의 경로 |
| collection | [ImageCollection](../../com.aspose.omr/imagecollection/) | 이 템플릿 생성에 사용될 이미지 컬렉션 |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings) {#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection-com.aspose.omr.GlobalPageSettings}
```
public final GenerationResult generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings)
```


텍스트 마크업을 기반으로 템플릿(.omr) 및 템플릿 이미지를 생성합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| markupPath | java.lang.String | 텍스트 마크업 파일의 경로 |
| collection | [ImageCollection](../../com.aspose.omr/imagecollection/) | 이 템플릿 생성에 사용될 이미지 컬렉션 |
| settings | [GlobalPageSettings](../../com.aspose.omr/globalpagesettings/) | 각 페이지에 대한 전역 설정 |

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


지정된 템플릿으로 작업할 수 있는 [TemplateProcessor](../../com.aspose.omr/templateprocessor/) 인스턴스를 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | java.io.InputStream | OMR 템플릿 파일의 콘텐츠 스트림 |

**Returns:**
[TemplateProcessor](../../com.aspose.omr/templateprocessor/) - The [TemplateProcessor](../../com.aspose.omr/templateprocessor/) instance
### getTemplateProcessor(String templatePath) {#getTemplateProcessor-java.lang.String}
```
public final TemplateProcessor getTemplateProcessor(String templatePath)
```


지정된 템플릿으로 작업할 수 있는 [TemplateProcessor](../../com.aspose.omr/templateprocessor/) 인스턴스를 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| templatePath | java.lang.String | OMR 템플릿 파일의 경로 |

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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

