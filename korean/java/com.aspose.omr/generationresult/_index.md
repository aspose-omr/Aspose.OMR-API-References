---
title: "GenerationResult"
second_title: "Aspose.OMR for Java API 참조"
description: "템플릿 생성 결과"
type: docs
weight: 14
url: /ko/java/com.aspose.omr/generationresult/
---

**Inheritance:**
java.lang.Object
```
public class GenerationResult
```

템플릿 생성 결과. 템플릿 이미지와 템플릿(json으로 이미지상의 요소 위치를 설명함)을 포함합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [getErrorCode()](#getErrorCode) | 오류 코드를 가져오거나 설정합니다. |
| [getErrorMessage()](#getErrorMessage) | 오류를 설명하는 메시지를 가져오거나 설정합니다. |
| [getTemplate()](#getTemplate) | 템플릿 JSON 문자열을 가져옵니다 |
| [getTemplateImage()](#getTemplateImage) | 생성된 템플릿 이미지를 가져오거나 설정합니다 |
| [getWarnings()](#getWarnings) | 생성 중 발생한 비치명적 결함을 설명하는 경고 메시지 목록을 가져오거나 설정합니다 |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [save(String folder, String name)](#save-java.lang.String-java.lang.String) | 지정된 폴더에 템플릿 이미지와 템플릿을 저장합니다 |
| [setErrorCode(int value)](#setErrorCode-int) | 오류 코드를 가져오거나 설정합니다. |
| [setErrorMessage(String value)](#setErrorMessage-java.lang.String) | 오류를 설명하는 메시지를 가져오거나 설정합니다. |
| [setTemplate(String value)](#setTemplate-java.lang.String) | 템플릿 JSON 문자열을 설정합니다 |
| [setTemplateImage(BufferedImage value)](#setTemplateImage-java.awt.image.BufferedImage) | 생성된 템플릿 이미지를 가져오거나 설정합니다 |
| [setWarnings(List<String> value)](#setWarnings-java.util.List-java.lang.String) | 생성 중 발생한 비치명적 결함을 설명하는 경고 메시지 목록을 가져오거나 설정합니다 |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
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


오류 코드를 가져오거나 설정합니다. 오류가 없으면 0입니다.

**Returns:**
int - 오류 코드
### getErrorMessage() {#getErrorMessage}
```
public final String getErrorMessage()
```


오류를 설명하는 메시지를 가져오거나 설정합니다. 오류가 없으면 비어 있습니다.

**Returns:**
java.lang.String - 오류를 설명하는 메시지
### getTemplate() {#getTemplate}
```
public final String getTemplate()
```


템플릿 JSON 문자열을 가져옵니다

**Returns:**
java.lang.String - 템플릿 JSON 문자열
### getTemplateImage() {#getTemplateImage}
```
public final BufferedImage getTemplateImage()
```


생성된 템플릿 이미지를 가져오거나 설정합니다

**Returns:**
java.awt.image.BufferedImage
### getWarnings() {#getWarnings}
```
public final List<String> getWarnings()
```


생성 중 발생한 비치명적 결함을 설명하는 경고 메시지 목록을 가져오거나 설정합니다

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


지정된 폴더에 템플릿 이미지와 템플릿을 저장합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 폴더 | java.lang.String | 대상 폴더 |
| 이름 | java.lang.String | 템플릿 이름 |

### setErrorCode(int value) {#setErrorCode-int}
```
public final void setErrorCode(int value)
```


오류 코드를 가져오거나 설정합니다. 오류가 없으면 0입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int | 오류 코드 |

### setErrorMessage(String value) {#setErrorMessage-java.lang.String}
```
public final void setErrorMessage(String value)
```


오류를 설명하는 메시지를 가져오거나 설정합니다. 오류가 없으면 비어 있습니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 오류를 설명하는 메시지 |

### setTemplate(String value) {#setTemplate-java.lang.String}
```
public final void setTemplate(String value)
```


템플릿 JSON 문자열을 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 템플릿 JSON 문자열 |

### setTemplateImage(BufferedImage value) {#setTemplateImage-java.awt.image.BufferedImage}
```
public final void setTemplateImage(BufferedImage value)
```


생성된 템플릿 이미지를 가져오거나 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.awt.image.BufferedImage |  |

### setWarnings(List<String> value) {#setWarnings-java.util.List-java.lang.String}
```
public final void setWarnings(List<String> value)
```


생성 중 발생한 비치명적 결함을 설명하는 경고 메시지 목록을 가져오거나 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.util.List<java.lang.String> |  |

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

