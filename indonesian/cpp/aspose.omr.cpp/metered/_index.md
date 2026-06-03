---
title: "Berukuran"
second_title: "Referensi API Aspose.OMR untuk .NET"
description: "Menyediakan metode untuk mengatur kunci berukuran."
type: docs
weight: 10
url: /id/net/aspose.omr/metered/
---
## Metered class

Menyediakan metode untuk mengatur kunci berukuran.

```csharp
public class Metered
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Metered](metered)() | Menginisialisasi sebuah instance baru dari kelas ini. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [SetMeteredKey](../../aspose.omr/metered/setmeteredkey)(string, string) | Mengatur kunci publik dan privat berukuran |
| static [GetConsumptionCredit](../../aspose.omr/metered/getconsumptioncredit)() | Mendapatkan kredit konsumsi |
| static [GetConsumptionQuantity](../../aspose.omr/metered/getconsumptionquantity)() | Mendapatkan ukuran file konsumsi |

### Contoh

Dalam contoh ini, akan dicoba mengatur kunci publik dan privat berukuran

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

file jar komponen:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Lihat Juga

* namespace [Aspose.OMR](../../aspose.omr)
* assembly [Aspose.OMR](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk Aspose.OMR.dll -->
