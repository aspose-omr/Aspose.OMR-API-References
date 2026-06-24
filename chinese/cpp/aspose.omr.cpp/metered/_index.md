---
title: "计量的"
second_title: "Aspose.OMR 适用于 .NET 的 API 参考"
description: "提供设置计量密钥的方法。"
type: docs
weight: 10
url: /zh/net/aspose.omr/metered/
---
## Metered class

提供设置计量密钥的方法。

```csharp
public class Metered
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Metered](metered)() | 初始化此类的新实例。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [SetMeteredKey](../../aspose.omr/metered/setmeteredkey)(string, string) | 设置计量的公钥和私钥 |
| static [GetConsumptionCredit](../../aspose.omr/metered/getconsumptioncredit)() | 获取消耗信用 |
| static [GetConsumptionQuantity](../../aspose.omr/metered/getconsumptionquantity)() | 获取消耗文件大小 |

### 示例

在此示例中，将尝试设置计量的公钥和私钥

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

组件 jar 文件：

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### 另见

* namespace [Aspose.OMR](../../aspose.omr)
* assembly [Aspose.OMR](../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OMR.dll 生成 -->
