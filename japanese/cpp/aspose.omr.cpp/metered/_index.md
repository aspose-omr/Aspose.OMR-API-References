---
title: "メーター制"
second_title: ".NET 用 Aspose.OMR API リファレンス"
description: "メーターキーを設定するメソッドを提供します。"
type: docs
weight: 10
url: /ja/net/aspose.omr/metered/
---
## Metered class

メーターキーを設定するメソッドを提供します。

```csharp
public class Metered
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Metered](metered)() | このクラスの新しいインスタンスを初期化します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [SetMeteredKey](../../aspose.omr/metered/setmeteredkey)(string, string) | メーター制の公開キーとプライベートキーを設定します。 |
| static [GetConsumptionCredit](../../aspose.omr/metered/getconsumptioncredit)() | 消費クレジットを取得します。 |
| static [GetConsumptionQuantity](../../aspose.omr/metered/getconsumptionquantity)() | 消費ファイルサイズを取得します。 |

### 例

この例では、メーター制の公開キーとプライベートキーを設定しようとします。

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

コンポーネントの JAR ファイル:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### 参照

* namespace [Aspose.OMR](../../aspose.omr)
* assembly [Aspose.OMR](../../)

<!-- 編集しないでください: xmldocmd によって Aspose.OMR.dll 用に生成されました -->
