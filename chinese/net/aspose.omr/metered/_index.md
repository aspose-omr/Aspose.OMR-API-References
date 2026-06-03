---
title: "Metered"
second_title: "Aspose.OMR 适用于 .NET API 参考"
description: "提供设置计量密钥的方法。"
type: docs
weight: 1020
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
| [Metered](metered)() | 默认构造函数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetProductName](../../aspose.omr/metered/getproductname)() | 获取产品名称 |
| [SetMeteredKey](../../aspose.omr/metered/setmeteredkey)(string, string) | 设置计量版的公钥和私钥。如果您购买了计量许可证，在启动应用程序时应调用此 API，通常这就足够了。然而，如果始终无法上传消费数据且超过 24 小时，许可证将被设置为评估状态。为避免这种情况，您应定期检查许可证状态，如果是评估状态，请再次调用此 API。 |
| static [GetConsumptionCredit](../../aspose.omr/metered/getconsumptioncredit)() | 获取消费积分 |
| static [GetConsumptionQuantity](../../aspose.omr/metered/getconsumptionquantity)() | 获取消费文件大小 |
| static [IsMeteredLicensed](../../aspose.omr/metered/ismeteredlicensed)() | 检查计量版是否已授权 |

### 示例

在此示例中，将尝试设置计量版的公钥和私钥

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### 另请参阅

* namespace [Aspose.OMR](../../aspose.omr)
* assembly [Aspose.OMR](../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OMR.dll 生成 -->
