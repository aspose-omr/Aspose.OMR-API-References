---
title: "SetLicense"
second_title: ".NET 用 Aspose.OMR API リファレンス"
description: "コンポーネントにライセンスを付与します。"
type: docs
weight: 30
url: /ja/net/aspose.omr/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

コンポーネントにライセンスを付与します。

```csharp
public void SetLicense(string licenseName)
```

### 備考

次の場所でライセンスを検索しようとします:

1. 明示的なパス。

2. Aspose コンポーネント アセンブリが含まれるフォルダー。

3. クライアントの呼び出しアセンブリが含まれるフォルダー。

4. エントリ（スタートアップ）アセンブリを含むフォルダーです。

5. クライアントの呼び出しアセンブリ内の埋め込みリソースです。

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. 明示的なパス。

2. クライアントの呼び出しアセンブリ内の埋め込みリソースです。

### 例

この例では、コンポーネントが含まれるフォルダー、呼び出しアセンブリが含まれるフォルダー、エントリ アセンブリのフォルダー、そして呼び出しアセンブリの埋め込みリソース内で、MyLicense.lic という名前のライセンス ファイルを検索しようとします。

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
```

完全または短いファイル名、または埋め込みリソースの名前を指定できます。空文字列を使用すると評価モードに切り替わります。

### 参照

* class [License](../../license)
* namespace [Aspose.OMR](../../license)
* assembly [Aspose.OMR](../../../)

---

## SetLicense(Stream) {#setlicense}

コンポーネントにライセンスを付与します。

```csharp
public void SetLicense(Stream stream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | ライセンスを含むストリームです。 |

### 備考

このメソッドを使用して、ストリームからライセンスをロードします。

### 例

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

### 参照

* class [License](../../license)
* namespace [Aspose.OMR](../../license)
* assembly [Aspose.OMR](../../../)

<!-- 編集しないでください: xmldocmd によって Aspose.OMR.dll 用に生成されました -->
