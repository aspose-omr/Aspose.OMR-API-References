---
title: "Ölçülen"
second_title: "Aspose.OMR for .NET API Referansı"
description: "Ölçülen anahtarı ayarlamak için yöntemler sağlar."
type: docs
weight: 10
url: /tr/net/aspose.omr/metered/
---
## Metered class

Ölçülen anahtarı ayarlamak için yöntemler sağlar.

```csharp
public class Metered
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [Metered](metered)() | Bu sınıfın yeni bir örneğini başlatır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [SetMeteredKey](../../aspose.omr/metered/setmeteredkey)(string, string) | Ölçülen genel ve özel anahtarı ayarlar |
| static [GetConsumptionCredit](../../aspose.omr/metered/getconsumptioncredit)() | Tüketim kredisini alır |
| static [GetConsumptionQuantity](../../aspose.omr/metered/getconsumptionquantity)() | Tüketim dosya boyutunu alır |

### Örnekler

Bu örnekte, ölçülen genel ve özel anahtarı ayarlamaya çalışılacak

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

bileşen jar dosyası:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Ayrıca Bakınız

* namespace [Aspose.OMR](../../aspose.omr)
* assembly [Aspose.OMR](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından Aspose.OMR.dll için oluşturuldu -->
