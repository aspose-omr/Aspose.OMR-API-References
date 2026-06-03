---
title: "Lisans"
second_title: "Aspose.OMR for .NET API Referansı"
description: "Bileşeni lisanslamak için yöntemler sağlar."
type: docs
weight: 20
url: /tr/net/aspose.omr/license/
---
## License class

Bileşeni lisanslamak için yöntemler sağlar.

```csharp
public class License
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [License](license)() | Bu sınıfın yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Embedded](../../aspose.omr/license/embedded) { get; set; } | Lisans numarası gömülü kaynak olarak eklendi. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [SetLicense](../../aspose.omr/license/setlicense#setlicense)(Stream) | Bileşeni lisanslar. |
| [SetLicense](../../aspose.omr/license/setlicense#setlicense_1)(string) | Bileşeni lisanslar. |

### Örnekler

Bu örnekte, bileşeni içeren klasörde, çağıran derlemeyi içeren klasörde, giriş derlemesinin klasöründe ve ardından çağıran derlemenin gömülü kaynaklarında MyLicense.lic adlı bir lisans dosyası bulmaya çalışılacaktır.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### Ayrıca Bakınız

* namespace [Aspose.OMR](../../aspose.omr)
* assembly [Aspose.OMR](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından Aspose.OMR.dll için oluşturuldu -->
