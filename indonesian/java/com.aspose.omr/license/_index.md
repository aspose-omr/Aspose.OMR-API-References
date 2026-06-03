---
title: "Lisensi"
second_title: "Referensi API Aspose.OMR for Java"
description: "Menyediakan metode untuk melisensikan komponen"
type: docs
weight: 18
url: /id/java/com.aspose.omr/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

Menyediakan metode untuk melisensikan komponen.

Dalam contoh ini, akan dicoba menemukan file lisensi bernama MyLicense.lic di folder yang berisi komponen, di folder yang berisi assembly pemanggil, di folder assembly entri, dan kemudian di sumber daya tersemat dari assembly pemanggil.

License license = new License();
license.setLicense("MyLicense.lic");
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [License()](#License) | Menginisialisasi sebuah instance baru dari kelas ini. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream) | Melisensikan komponen. |
| [setLicense(String licenseName)](#setLicense-java.lang.String) | Melisensikan komponen. |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### License() {#License}
```
public License()
```


Menginisialisasi sebuah instance baru dari kelas ini.

Dalam contoh ini, akan dicoba menemukan file lisensi bernama MyLicense.lic di folder yang berisi komponen, di folder yang berisi assembly pemanggil, di folder assembly entri, dan kemudian di sumber daya tersemat dari assembly pemanggil.

License license = new License();
license.setLicense("MyLicense.lic");

### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify}
```
public final native void notify()
```




### notifyAll() {#notifyAll}
```
public final native void notifyAll()
```




### setLicense(InputStream stream) {#setLicense-java.io.InputStream}
```
public void setLicense(InputStream stream)
```


Melisensikan komponen.

Aliran yang berisi lisensi.

Gunakan metode ini untuk memuat lisensi dari aliran.

License license = new License();
license.setLicense(myStream);

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | java.io.InputStream | Aliran lisensi |

### setLicense(String licenseName) {#setLicense-java.lang.String}
```
public void setLicense(String licenseName)
```


Melisensikan komponen.

Mencoba menemukan lisensi di lokasi berikut:

1. Jalur eksplisit.

2. Folder file jar komponen.

Dalam contoh ini, akan dicoba menemukan file lisensi bernama MyLicense.lic di folder yang berisi komponen, di folder yang berisi assembly pemanggil, di folder assembly entri, dan kemudian di sumber daya tersemat dari assembly pemanggil.

License license = new License();
license.setLicense("MyLicense.lic");

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| licenseName | java.lang.String | Bisa berupa nama file lengkap atau singkat atau nama sumber daya tersemat. Gunakan string kosong untuk beralih ke mode evaluasi. |

### toString() {#toString}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait}
```
public final void wait()
```




### wait(long arg0) {#wait-long}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

