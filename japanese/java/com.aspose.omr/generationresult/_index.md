---
title: "GenerationResult"
second_title: "Aspose.OMR for Java API リファレンス"
description: "テンプレート生成の結果"
type: docs
weight: 14
url: /ja/java/com.aspose.omr/generationresult/
---

**Inheritance:**
java.lang.Object
```
public class GenerationResult
```

テンプレート生成の結果です。テンプレート画像とテンプレート（画像上の要素位置を記述した json）を含みます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [getErrorCode()](#getErrorCode) | エラーコードを取得または設定します。 |
| [getErrorMessage()](#getErrorMessage) | エラーを説明するメッセージを取得または設定します。 |
| [getTemplate()](#getTemplate) | テンプレート JSON 文字列を取得します |
| [getTemplateImage()](#getTemplateImage) | 生成されたテンプレート画像を取得または設定します |
| [getWarnings()](#getWarnings) | 生成中に発生した非致命的な障害を説明する警告メッセージのリストを取得または設定します |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [save(String folder, String name)](#save-java.lang.String-java.lang.String) | テンプレート画像とテンプレートを指定されたフォルダーに保存します |
| [setErrorCode(int value)](#setErrorCode-int) | エラーコードを取得または設定します。 |
| [setErrorMessage(String value)](#setErrorMessage-java.lang.String) | エラーを説明するメッセージを取得または設定します。 |
| [setTemplate(String value)](#setTemplate-java.lang.String) | テンプレート JSON 文字列を設定します |
| [setTemplateImage(BufferedImage value)](#setTemplateImage-java.awt.image.BufferedImage) | 生成されたテンプレート画像を取得または設定します |
| [setWarnings(List<String> value)](#setWarnings-java.util.List-java.lang.String) | 生成中に発生した非致命的な障害を説明する警告メッセージのリストを取得または設定します |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
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


エラーコードを取得または設定します。エラーが発生しなければ 0 です。

**Returns:**
int - エラーコード
### getErrorMessage() {#getErrorMessage}
```
public final String getErrorMessage()
```


エラーを説明するメッセージを取得または設定します。エラーが発生しなければ空です。

**Returns:**
java.lang.String - エラーを説明するメッセージ
### getTemplate() {#getTemplate}
```
public final String getTemplate()
```


テンプレート JSON 文字列を取得します

**Returns:**
java.lang.String - テンプレート JSON 文字列
### getTemplateImage() {#getTemplateImage}
```
public final BufferedImage getTemplateImage()
```


生成されたテンプレート画像を取得または設定します

**Returns:**
java.awt.image.BufferedImage
### getWarnings() {#getWarnings}
```
public final List<String> getWarnings()
```


生成中に発生した非致命的な障害を説明する警告メッセージのリストを取得または設定します

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


テンプレート画像とテンプレートを指定されたフォルダーに保存します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| フォルダー | java.lang.String | 保存先フォルダー |
| 名前 | java.lang.String | テンプレートの名前 |

### setErrorCode(int value) {#setErrorCode-int}
```
public final void setErrorCode(int value)
```


エラーコードを取得または設定します。エラーが発生しなければ 0 です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | エラーコード |

### setErrorMessage(String value) {#setErrorMessage-java.lang.String}
```
public final void setErrorMessage(String value)
```


エラーを説明するメッセージを取得または設定します。エラーが発生しなければ空です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | エラーを説明するメッセージ |

### setTemplate(String value) {#setTemplate-java.lang.String}
```
public final void setTemplate(String value)
```


テンプレート JSON 文字列を設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | テンプレート JSON 文字列 |

### setTemplateImage(BufferedImage value) {#setTemplateImage-java.awt.image.BufferedImage}
```
public final void setTemplateImage(BufferedImage value)
```


生成されたテンプレート画像を取得または設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.awt.image.BufferedImage |  |

### setWarnings(List<String> value) {#setWarnings-java.util.List-java.lang.String}
```
public final void setWarnings(List<String> value)
```


生成中に発生した非致命的な障害を説明する警告メッセージのリストを取得または設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.util.List<java.lang.String> |  |

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

