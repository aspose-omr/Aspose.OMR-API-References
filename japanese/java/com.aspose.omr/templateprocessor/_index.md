---
title: "TemplateProcessor"
second_title: "Aspose.OMR for Java API リファレンス"
description: "テンプレートと画像を処理するクラス"
type: docs
weight: 30
url: /ja/java/com.aspose.omr/templateprocessor/
---

**Inheritance:**
java.lang.Object
```
public class TemplateProcessor
```

テンプレートと画像を処理するクラス。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [recalculate(RecognitionResult result)](#recalculate-com.aspose.omr.RecognitionResult) | 微調整されたパラメータを使用して認識結果を更新します。 |
| [recalculate(RecognitionResult result, int recognitionThreshold)](#recalculate-com.aspose.omr.RecognitionResult-int) | 微調整されたパラメータを使用して認識結果を更新します。 |
| [recognizeImage(BufferedImage bufferedImage)](#recognizeImage-java.awt.image.BufferedImage) | 画像を認識します |
| [recognizeImage(BufferedImage bufferedImage, int recognitionThreshold)](#recognizeImage-java.awt.image.BufferedImage-int) | 画像を認識します |
| [recognizeImage(InputStream inputStream)](#recognizeImage-java.io.InputStream) | 画像を認識します |
| [recognizeImage(InputStream inputStream, int recognitionThreshold)](#recognizeImage-java.io.InputStream-int) | 画像を認識します |
| [recognizeImage(String imagePath)](#recognizeImage-java.lang.String) | 画像を認識します |
| [recognizeImage(String imagePath, int recognitionThreshold)](#recognizeImage-java.lang.String-int) | 画像を認識します |
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




### recalculate(RecognitionResult result) {#recalculate-com.aspose.omr.RecognitionResult}
```
public final void recalculate(RecognitionResult result)
```


微調整されたパラメータを使用して認識結果を更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| result | [RecognitionResult](../../com.aspose.omr/recognitionresult/) | 更新する認識結果です。 |

### recalculate(RecognitionResult result, int recognitionThreshold) {#recalculate-com.aspose.omr.RecognitionResult-int}
```
public final void recalculate(RecognitionResult result, int recognitionThreshold)
```


微調整されたパラメータを使用して認識結果を更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| result | [RecognitionResult](../../com.aspose.omr/recognitionresult/) | 更新する認識結果です。 |
| recognitionThreshold | int | （オプション）認識しきい値（0〜100）の範囲です。しきい値を超えて入力された要素のみが入力済みとしてカウントされます。 |

### recognizeImage(BufferedImage bufferedImage) {#recognizeImage-java.awt.image.BufferedImage}
```
public final RecognitionResult recognizeImage(BufferedImage bufferedImage)
```


画像を認識します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bufferedImage | java.awt.image.BufferedImage | 認識対象の画像 |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(BufferedImage bufferedImage, int recognitionThreshold) {#recognizeImage-java.awt.image.BufferedImage-int}
```
public final RecognitionResult recognizeImage(BufferedImage bufferedImage, int recognitionThreshold)
```


画像を認識します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bufferedImage | java.awt.image.BufferedImage | 認識対象の画像 |
| recognitionThreshold | int | （オプション）認識しきい値（0〜100）の範囲です。しきい値を超えて入力された要素のみが入力済みとしてカウントされます。 |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(InputStream inputStream) {#recognizeImage-java.io.InputStream}
```
public final RecognitionResult recognizeImage(InputStream inputStream)
```


画像を認識します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 画像のストリーム |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(InputStream inputStream, int recognitionThreshold) {#recognizeImage-java.io.InputStream-int}
```
public final RecognitionResult recognizeImage(InputStream inputStream, int recognitionThreshold)
```


画像を認識します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 画像のストリーム |
| recognitionThreshold | int | （オプション）認識しきい値（0〜100）の範囲です。しきい値を超えて入力された要素のみが入力済みとしてカウントされます。 |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(String imagePath) {#recognizeImage-java.lang.String}
```
public final RecognitionResult recognizeImage(String imagePath)
```


画像を認識します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| imagePath | java.lang.String | 認識対象画像へのパス |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(String imagePath, int recognitionThreshold) {#recognizeImage-java.lang.String-int}
```
public final RecognitionResult recognizeImage(String imagePath, int recognitionThreshold)
```


画像を認識します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| imagePath | java.lang.String | 認識対象画像へのパス |
| recognitionThreshold | int | （オプション）認識しきい値（0〜100）の範囲です。しきい値を超えて入力された要素のみが入力済みとしてカウントされます。 |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
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

