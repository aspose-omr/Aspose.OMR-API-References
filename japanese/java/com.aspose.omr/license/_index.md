---
title: "ライセンス"
second_title: "Aspose.OMR for Java API リファレンス"
description: "コンポーネントにライセンスを付与するためのメソッドを提供します"
type: docs
weight: 18
url: /ja/java/com.aspose.omr/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

コンポーネントをライセンスするためのメソッドを提供します。

この例では、コンポーネントが含まれるフォルダー、呼び出しアセンブリが含まれるフォルダー、エントリアセンブリのフォルダー、そして呼び出しアセンブリの埋め込みリソース内で、MyLicense.lic という名前のライセンスファイルを検索しようとします。

License license = new License();
license.setLicense("MyLicense.lic");
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [License()](#License) | このクラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream) | コンポーネントにライセンスを付与します。 |
| [setLicense(String licenseName)](#setLicense-java.lang.String) | コンポーネントにライセンスを付与します。 |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### License() {#License}
```
public License()
```


このクラスの新しいインスタンスを初期化します。

この例では、コンポーネントが含まれるフォルダー、呼び出しアセンブリが含まれるフォルダー、エントリアセンブリのフォルダー、そして呼び出しアセンブリの埋め込みリソース内で、MyLicense.lic という名前のライセンスファイルを検索しようとします。

License license = new License();
license.setLicense("MyLicense.lic");

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




### setLicense(InputStream stream) {#setLicense-java.io.InputStream}
```
public void setLicense(InputStream stream)
```


コンポーネントにライセンスを付与します。

ライセンスを含むストリーム。

このメソッドを使用して、ストリームからライセンスをロードします。

License license = new License();
license.setLicense(myStream);

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ストリーム | java.io.InputStream | license ストリーム |

### setLicense(String licenseName) {#setLicense-java.lang.String}
```
public void setLicense(String licenseName)
```


コンポーネントにライセンスを付与します。

次の場所でライセンスを検索しようとします：

1. 明示的なパス。

2. コンポーネント jar ファイルのフォルダー。

この例では、コンポーネントが含まれるフォルダー、呼び出しアセンブリが含まれるフォルダー、エントリアセンブリのフォルダー、そして呼び出しアセンブリの埋め込みリソース内で、MyLicense.lic という名前のライセンスファイルを検索しようとします。

License license = new License();
license.setLicense("MyLicense.lic");

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| licenseName | java.lang.String | 完全なファイル名または短いファイル名、あるいは埋め込みリソースの名前を指定できます。空文字列を使用すると評価モードに切り替わります。 |

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

