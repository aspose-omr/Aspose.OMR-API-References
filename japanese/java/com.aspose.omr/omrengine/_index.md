---
title: "OmrEngine"
second_title: "Aspose.OMR for Java API リファレンス"
description: "OMR エンジン"
type: docs
weight: 22
url: /ja/java/com.aspose.omr/omrengine/
---

**Inheritance:**
java.lang.Object
```
public class OmrEngine
```

OMR エンジン。テンプレートと画像処理クラスおよび GUI コンポーネントの作成を処理します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [OmrEngine()](#OmrEngine) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [generateTemplate(String markupPath)](#generateTemplate-java.lang.String) | テキストマークアップに基づいてテンプレート（.omr）とテンプレート画像を作成します |
| [generateTemplate(String markupPath, GlobalPageSettings settings)](#generateTemplate-java.lang.String-com.aspose.omr.GlobalPageSettings) | テキストマークアップに基づいてテンプレート（.omr）とテンプレート画像を作成します |
| [generateTemplate(String markupPath, ImageCollection collection)](#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection) | テキストマークアップに基づいてテンプレート（.omr）とテンプレート画像を作成します |
| [generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings)](#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection-com.aspose.omr.GlobalPageSettings) | テキストマークアップに基づいてテンプレート（.omr）とテンプレート画像を作成します |
| [getClass()](#getClass) |  |
| [getTemplateProcessor(InputStream inputStream)](#getTemplateProcessor-java.io.InputStream) | 指定されたテンプレートで作業できる [TemplateProcessor](../../com.aspose.omr/templateprocessor/) インスタンスを作成します。 |
| [getTemplateProcessor(String templatePath)](#getTemplateProcessor-java.lang.String) | 指定されたテンプレートで作業できる [TemplateProcessor](../../com.aspose.omr/templateprocessor/) インスタンスを作成します。 |
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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateTemplate(String markupPath) {#generateTemplate-java.lang.String}
```
public final GenerationResult generateTemplate(String markupPath)
```


テキストマークアップに基づいてテンプレート（.omr）とテンプレート画像を作成します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| markupPath | java.lang.String | テキストマークアップファイルへのパス |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, GlobalPageSettings settings) {#generateTemplate-java.lang.String-com.aspose.omr.GlobalPageSettings}
```
public final GenerationResult generateTemplate(String markupPath, GlobalPageSettings settings)
```


テキストマークアップに基づいてテンプレート（.omr）とテンプレート画像を作成します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| markupPath | java.lang.String | テキストマークアップファイルへのパス |
| settings | [GlobalPageSettings](../../com.aspose.omr/globalpagesettings/) | 各ページのグローバル設定 |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, ImageCollection collection) {#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection}
```
public final GenerationResult generateTemplate(String markupPath, ImageCollection collection)
```


テキストマークアップに基づいてテンプレート（.omr）とテンプレート画像を作成します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| markupPath | java.lang.String | テキストマークアップファイルへのパス |
| collection | [ImageCollection](../../com.aspose.omr/imagecollection/) | このテンプレート生成で使用される画像のコレクション |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings) {#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection-com.aspose.omr.GlobalPageSettings}
```
public final GenerationResult generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings)
```


テキストマークアップに基づいてテンプレート（.omr）とテンプレート画像を作成します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| markupPath | java.lang.String | テキストマークアップファイルへのパス |
| collection | [ImageCollection](../../com.aspose.omr/imagecollection/) | このテンプレート生成で使用される画像のコレクション |
| settings | [GlobalPageSettings](../../com.aspose.omr/globalpagesettings/) | 各ページのグローバル設定 |

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


指定されたテンプレートで作業できる [TemplateProcessor](../../com.aspose.omr/templateprocessor/) インスタンスを作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputStream | java.io.InputStream | OMRテンプレートファイルのコンテンツストリーム |

**Returns:**
[TemplateProcessor](../../com.aspose.omr/templateprocessor/) - The [TemplateProcessor](../../com.aspose.omr/templateprocessor/) instance
### getTemplateProcessor(String templatePath) {#getTemplateProcessor-java.lang.String}
```
public final TemplateProcessor getTemplateProcessor(String templatePath)
```


指定されたテンプレートで作業できる [TemplateProcessor](../../com.aspose.omr/templateprocessor/) インスタンスを作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| templatePath | java.lang.String | OMRテンプレートファイルへのパス |

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

