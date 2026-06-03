---
title: "Tariffato"
second_title: "Riferimento API Aspose.OMR per Java"
description: "Fornisce metodi per impostare la chiave tariffata"
type: docs
weight: 19
url: /it/java/com.aspose.omr/metered/
---

**Inheritance:**
java.lang.Object
```
public class Metered
```

Fornisce metodi per impostare la chiave a consumo.

--------------------

In questo esempio, verrà tentato di impostare la chiave pubblica e privata tariffata

```
The component jar file:
  
 	Metered matered = new Metered();
 	matered.setMeteredKey("PublicKey", "PrivateKey");
```
## Costruttori

| Costruttore | Description |
| --- | --- |
| [Metered()](#Metered) | Inizializza una nuova istanza di questa classe. |
## Metodi

| Metodo | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [getConsumptionCredit()](#getConsumptionCredit) | Ottiene il credito di consumo |
| [getConsumptionQuantity()](#getConsumptionQuantity) | Ottiene la dimensione del file di consumo |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String) | Imposta la chiave pubblica e privata tariffata |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### Metered() {#Metered}
```
public Metered()
```


Inizializza una nuova istanza di questa classe.

### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Description |
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


Ottiene il credito di consumo

**Returns:**
java.math.BigDecimal - quantità di consumo
### getConsumptionQuantity() {#getConsumptionQuantity}
```
public static BigDecimal getConsumptionQuantity()
```


Ottiene la dimensione del file di consumo

**Returns:**
java.math.BigDecimal - quantità di consumo
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


Imposta la chiave pubblica e privata tariffata

**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| publicKey | java.lang.String | chiave pubblica |
| privateKey | java.lang.String | chiave privata |

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
| Parametro | Tipo | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

