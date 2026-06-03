---
title: "Измеряемый"
second_title: "Справочник API Aspose.OMR для Java"
description: "Предоставляет методы для установки измеряемого ключа"
type: docs
weight: 19
url: /ru/java/com.aspose.omr/metered/
---

**Inheritance:**
java.lang.Object
```
public class Metered
```

Предоставляет методы для установки измеряемого ключа.

--------------------

В этом примере будет предпринята попытка установить измеряемый публичный и приватный ключ

```
The component jar file:
  
 	Metered matered = new Metered();
 	matered.setMeteredKey("PublicKey", "PrivateKey");
```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Metered()](#Metered) | Инициализирует новый экземпляр этого класса. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [getConsumptionCredit()](#getConsumptionCredit) | Получает кредит потребления |
| [getConsumptionQuantity()](#getConsumptionQuantity) | Получает размер файла потребления |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String) | Устанавливает измеряемый публичный и приватный ключ |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### Metered() {#Metered}
```
public Metered()
```


Инициализирует новый экземпляр этого класса.

### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
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


Получает кредит потребления

**Returns:**
java.math.BigDecimal - количество потребления
### getConsumptionQuantity() {#getConsumptionQuantity}
```
public static BigDecimal getConsumptionQuantity()
```


Получает размер файла потребления

**Returns:**
java.math.BigDecimal - количество потребления
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


Устанавливает измеряемый публичный и приватный ключ

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| publicKey | java.lang.String | публичный ключ |
| privateKey | java.lang.String | приватный ключ |

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

