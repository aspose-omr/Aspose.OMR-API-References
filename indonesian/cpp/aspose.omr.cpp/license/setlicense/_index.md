---
title: "SetLicense"
second_title: "Referensi API Aspose.OMR untuk .NET"
description: "Melisensikan komponen."
type: docs
weight: 30
url: /id/net/aspose.omr/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Melisensikan komponen.

```csharp
public void SetLicense(string licenseName)
```

### Catatan

Mencoba menemukan lisensi di lokasi berikut:

1. Jalur eksplisit.

2. Folder yang berisi assembly komponen Aspose.

3. Folder yang berisi assembly pemanggil klien.

4. Folder yang berisi assembly entry (startup).

5. Sumber daya tertanam dalam assembly pemanggil klien.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Jalur eksplisit.

2. Sumber daya tertanam dalam assembly pemanggil klien.

### Contoh

Dalam contoh ini, akan dilakukan upaya untuk menemukan file lisensi bernama MyLicense.lic di folder yang berisi komponen, di folder yang berisi assembly pemanggil, di folder assembly entri, dan kemudian di sumber daya tertanam dari assembly pemanggil.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
```

Dapat berupa nama file lengkap atau pendek atau nama sumber daya tertanam. Gunakan string kosong untuk beralih ke mode evaluasi.

### Lihat Juga

* class [License](../../license)
* namespace [Aspose.OMR](../../license)
* assembly [Aspose.OMR](../../../)

---

## SetLicense(Stream) {#setlicense}

Melisensikan komponen.

```csharp
public void SetLicense(Stream stream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | Stream | Aliran yang berisi lisensi. |

### Catatan

Gunakan metode ini untuk memuat lisensi dari stream.

### Contoh

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

### Lihat Juga

* class [License](../../license)
* namespace [Aspose.OMR](../../license)
* assembly [Aspose.OMR](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk Aspose.OMR.dll -->
