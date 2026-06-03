---
title: "Berukuran"
second_title: "Referensi API Aspose.OMR for Java"
description: "Menyediakan metode untuk mengatur kunci berukuran"
type: docs
weight: 19
url: /id/java/com.aspose.omr/metered/
---

**Inheritance:**
java.lang.Object
```
public class Metered
```

Menyediakan metode untuk mengatur kunci bermeter.

--------------------

Dalam contoh ini, percobaan akan dilakukan untuk mengatur kunci publik dan privat berukuran

```
The component jar file:
  
 	Metered matered = new Metered();
 	matered.setMeteredKey("PublicKey", "PrivateKey");
```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Metered()](#Metered) | Menginisialisasi sebuah instance baru dari kelas ini. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [getConsumptionCredit()](#getConsumptionCredit) | Mendapatkan kredit konsumsi |
| [getConsumptionQuantity()](#getConsumptionQuantity) | Mendapatkan ukuran file konsumsi |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String) | Mengatur kunci publik dan privat berukuran |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### Metered() {#Metered}
```
public Metered()
```


Menginisialisasi sebuah instance baru dari kelas ini.

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
### getConsumptionCredit() {#getConsumptionCredit}
```
public static BigDecimal getConsumptionCredit()
```


Mendapatkan kredit konsumsi

**Returns:**
java.math.BigDecimal - jumlah konsumsi
### getConsumptionQuantity() {#getConsumptionQuantity}
```
public static BigDecimal getConsumptionQuantity()
```


Mendapatkan ukuran file konsumsi

**Returns:**
java.math.BigDecimal - jumlah konsumsi
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




### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Mengatur kunci publik dan privat berukuran

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| publicKey | java.lang.String | kunci publik |
| privateKey | java.lang.String | kunci privat |

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

