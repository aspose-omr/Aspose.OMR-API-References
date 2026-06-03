---
title: "ライセンス"
second_title: ".NET 用 Aspose.OMR API リファレンス"
description: "コンポーネントにライセンスを付与するメソッドを提供します。"
type: docs
weight: 20
url: /ja/net/aspose.omr/license/
---
## License class

コンポーネントにライセンスを付与するメソッドを提供します。

```csharp
public class License
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [License](license)() | このクラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Embedded](../../aspose.omr/license/embedded) { get; set; } | ライセンス番号が埋め込みリソースとして追加されました。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [SetLicense](../../aspose.omr/license/setlicense#setlicense)(Stream) | コンポーネントにライセンスを付与します。 |
| [SetLicense](../../aspose.omr/license/setlicense#setlicense_1)(string) | コンポーネントにライセンスを付与します。 |

### 例

この例では、コンポーネントが含まれるフォルダー、呼び出しアセンブリが含まれるフォルダー、エントリ アセンブリのフォルダー、そして呼び出しアセンブリの埋め込みリソース内で、MyLicense.lic という名前のライセンス ファイルを検索しようとします。

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### 参照

* namespace [Aspose.OMR](../../aspose.omr)
* assembly [Aspose.OMR](../../)

<!-- 編集しないでください: xmldocmd によって Aspose.OMR.dll 用に生成されました -->
