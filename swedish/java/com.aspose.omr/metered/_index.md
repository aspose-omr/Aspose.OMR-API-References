---
title: "Måttbaserad"
second_title: "Aspose.OMR för Java API-referens"
description: "Tillhandahåller metoder för att ställa in den måttbaserade nyckeln"
type: docs
weight: 19
url: /sv/java/com.aspose.omr/metered/
---

**Inheritance:**
java.lang.Object
```
public class Metered
```

Tillhandahåller metoder för att ställa in mätad nyckel

--------------------

I det här exemplet kommer ett försök att ställa in den måttbaserade offentliga och privata nyckeln att göras

```
The component jar file:
  
 	Metered matered = new Metered();
 	matered.setMeteredKey("PublicKey", "PrivateKey");
```
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Metered()](#Metered) | Initierar en ny instans av denna klass. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [getConsumptionCredit()](#getConsumptionCredit) | Hämtar konsumtionskredit |
| [getConsumptionQuantity()](#getConsumptionQuantity) | Hämtar konsumtionsfilens storlek |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String) | Ställer in den måttbaserade offentliga och privata nyckeln |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### Metered() {#Metered}
```
public Metered()
```


Initierar en ny instans av denna klass.

### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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


Hämtar konsumtionskredit

**Returns:**
java.math.BigDecimal - konsumtionskvantitet
### getConsumptionQuantity() {#getConsumptionQuantity}
```
public static BigDecimal getConsumptionQuantity()
```


Hämtar konsumtionsfilens storlek

**Returns:**
java.math.BigDecimal - konsumtionskvantitet
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


Ställer in den måttbaserade offentliga och privata nyckeln

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| publicKey | java.lang.String | offentlig nyckel |
| privateKey | java.lang.String | privat nyckel |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

