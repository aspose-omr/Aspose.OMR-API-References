---
title: "GenerationResult"
second_title: "Referensi API Aspose.OMR for Java"
description: "Hasil dari pembuatan templat"
type: docs
weight: 14
url: /id/java/com.aspose.omr/generationresult/
---

**Inheritance:**
java.lang.Object
```
public class GenerationResult
```

Hasil dari pembuatan templat. Berisi gambar templat dan templat (json yang menggambarkan lokasi elemen pada gambar).
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [getErrorCode()](#getErrorCode) | Mendapatkan atau mengatur kode kesalahan. |
| [getErrorMessage()](#getErrorMessage) | Mendapatkan atau mengatur pesan yang menjelaskan kesalahan. |
| [getTemplate()](#getTemplate) | Mendapatkan string JSON Template |
| [getTemplateImage()](#getTemplateImage) | Mendapatkan atau mengatur Gambar Templat yang dihasilkan |
| [getWarnings()](#getWarnings) | Mendapatkan atau mengatur daftar pesan peringatan yang menjelaskan kesalahan non-kritis yang muncul selama pembuatan |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [save(String folder, String name)](#save-java.lang.String-java.lang.String) | Simpan gambar templat dan templat ke folder yang ditentukan |
| [setErrorCode(int value)](#setErrorCode-int) | Mendapatkan atau mengatur kode kesalahan. |
| [setErrorMessage(String value)](#setErrorMessage-java.lang.String) | Mendapatkan atau mengatur pesan yang menjelaskan kesalahan. |
| [setTemplate(String value)](#setTemplate-java.lang.String) | Mengatur string JSON Template |
| [setTemplateImage(BufferedImage value)](#setTemplateImage-java.awt.image.BufferedImage) | Mendapatkan atau mengatur Gambar Templat yang dihasilkan |
| [setWarnings(List<String> value)](#setWarnings-java.util.List-java.lang.String) | Mendapatkan atau mengatur daftar pesan peringatan yang menjelaskan kesalahan non-kritis yang muncul selama pembuatan |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
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
### getErrorCode() {#getErrorCode}
```
public final int getErrorCode()
```


Mendapatkan atau mengatur kode kesalahan. Sama dengan 0 jika tidak ada kesalahan yang terjadi.

**Returns:**
int - kode kesalahan
### getErrorMessage() {#getErrorMessage}
```
public final String getErrorMessage()
```


Mendapatkan atau mengatur pesan yang menjelaskan kesalahan. Kosong jika tidak ada kesalahan yang terjadi.

**Returns:**
java.lang.String - pesan yang menjelaskan kesalahan
### getTemplate() {#getTemplate}
```
public final String getTemplate()
```


Mendapatkan string JSON Template

**Returns:**
java.lang.String - string JSON Template
### getTemplateImage() {#getTemplateImage}
```
public final BufferedImage getTemplateImage()
```


Mendapatkan atau mengatur Gambar Templat yang dihasilkan

**Returns:**
java.awt.image.BufferedImage
### getWarnings() {#getWarnings}
```
public final List<String> getWarnings()
```


Mendapatkan atau mengatur daftar pesan peringatan yang menjelaskan kesalahan non-kritis yang muncul selama pembuatan

**Returns:**
java.util.List<java.lang.String>
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




### save(String folder, String name) {#save-java.lang.String-java.lang.String}
```
public final void save(String folder, String name)
```


Simpan gambar templat dan templat ke folder yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| folder | java.lang.String | Folder tujuan |
| nama | java.lang.String | Nama templat |

### setErrorCode(int value) {#setErrorCode-int}
```
public final void setErrorCode(int value)
```


Mendapatkan atau mengatur kode kesalahan. Sama dengan 0 jika tidak ada kesalahan yang terjadi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | kode kesalahan |

### setErrorMessage(String value) {#setErrorMessage-java.lang.String}
```
public final void setErrorMessage(String value)
```


Mendapatkan atau mengatur pesan yang menjelaskan kesalahan. Kosong jika tidak ada kesalahan yang terjadi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | pesan yang menjelaskan kesalahan |

### setTemplate(String value) {#setTemplate-java.lang.String}
```
public final void setTemplate(String value)
```


Mengatur string JSON Template

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | string JSON Template |

### setTemplateImage(BufferedImage value) {#setTemplateImage-java.awt.image.BufferedImage}
```
public final void setTemplateImage(BufferedImage value)
```


Mendapatkan atau mengatur Gambar Templat yang dihasilkan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.awt.image.BufferedImage |  |

### setWarnings(List<String> value) {#setWarnings-java.util.List-java.lang.String}
```
public final void setWarnings(List<String> value)
```


Mendapatkan atau mengatur daftar pesan peringatan yang menjelaskan kesalahan non-kritis yang muncul selama pembuatan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.List<java.lang.String> |  |

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

