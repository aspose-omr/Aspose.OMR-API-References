---
title: "SetLicense"
second_title: "Aspose.OMR for .NET API Referansı"
description: "Bileşeni lisanslar."
type: docs
weight: 30
url: /tr/net/aspose.omr/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Bileşeni lisanslar.

```csharp
public void SetLicense(string licenseName)
```

### Açıklamalar

Lisansı aşağıdaki konumlarda bulmaya çalışır:

1. Açık yol.

2. Aspose bileşen derlemesini içeren klasör.

3. İstemcinin çağıran derlemesini içeren klasör.

4. Giriş (başlangıç) derlemesini içeren klasör.

5. İstemcinin çağıran derlemesindeki gömülü kaynak.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Açık yol.

2. İstemcinin çağıran derlemesindeki gömülü kaynak.

### Örnekler

Bu örnekte, bileşeni içeren klasörde, çağıran derlemeyi içeren klasörde, giriş derlemesinin klasöründe ve ardından çağıran derlemenin gömülü kaynaklarında MyLicense.lic adlı bir lisans dosyası bulmaya çalışılacaktır.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
```

Tam veya kısa dosya adı ya da gömülü kaynağın adı olabilir. Değerlendirme moduna geçmek için boş bir dize kullanın.

### Ayrıca Bakınız

* class [License](../../license)
* namespace [Aspose.OMR](../../license)
* assembly [Aspose.OMR](../../../)

---

## SetLicense(Stream) {#setlicense}

Bileşeni lisanslar.

```csharp
public void SetLicense(Stream stream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | Akış | Lisansı içeren bir akış. |

### Açıklamalar

Bir akıştan lisans yüklemek için bu yöntemi kullanın.

### Örnekler

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

### Ayrıca Bakınız

* class [License](../../license)
* namespace [Aspose.OMR](../../license)
* assembly [Aspose.OMR](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından Aspose.OMR.dll için oluşturuldu -->
