---
title: "Lisensi"
second_title: "Referensi API Aspose.OMR untuk .NET"
description: "Menyediakan metode untuk melisensikan komponen."
type: docs
weight: 20
url: /id/net/aspose.omr/license/
---
## License class

Menyediakan metode untuk melisensikan komponen.

```csharp
public class License
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [License](license)() | Menginisialisasi sebuah instance baru dari kelas ini. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Embedded](../../aspose.omr/license/embedded) { get; set; } | Nomor lisensi telah ditambahkan sebagai sumber daya tertanam. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [SetLicense](../../aspose.omr/license/setlicense#setlicense)(Stream) | Melisensikan komponen. |
| [SetLicense](../../aspose.omr/license/setlicense#setlicense_1)(string) | Melisensikan komponen. |

### Contoh

Dalam contoh ini, akan dilakukan upaya untuk menemukan file lisensi bernama MyLicense.lic di folder yang berisi komponen, di folder yang berisi assembly pemanggil, di folder assembly entri, dan kemudian di sumber daya tertanam dari assembly pemanggil.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### Lihat Juga

* namespace [Aspose.OMR](../../aspose.omr)
* assembly [Aspose.OMR](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk Aspose.OMR.dll -->
