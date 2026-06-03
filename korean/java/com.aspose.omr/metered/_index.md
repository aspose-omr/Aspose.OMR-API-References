---
title: "계량된"
second_title: "Aspose.OMR for Java API 참조"
description: "계량된 키를 설정하는 메서드를 제공합니다"
type: docs
weight: 19
url: /ko/java/com.aspose.omr/metered/
---

**Inheritance:**
java.lang.Object
```
public class Metered
```

계량 키를 설정하는 메서드를 제공합니다.

--------------------

이 예제에서는 계량된 공개 키와 개인 키를 설정하려고 시도합니다

```
The component jar file:
  
 	Metered matered = new Metered();
 	matered.setMeteredKey("PublicKey", "PrivateKey");
```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Metered()](#Metered) | 이 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [getConsumptionCredit()](#getConsumptionCredit) | 소비 크레딧을 가져옵니다 |
| [getConsumptionQuantity()](#getConsumptionQuantity) | 소비 파일 크기를 가져옵니다 |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String) | 계량된 공개 키와 개인 키를 설정합니다 |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### Metered() {#Metered}
```
public Metered()
```


이 클래스의 새 인스턴스를 초기화합니다.

### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
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


소비 크레딧을 가져옵니다

**Returns:**
java.math.BigDecimal - 소비 수량
### getConsumptionQuantity() {#getConsumptionQuantity}
```
public static BigDecimal getConsumptionQuantity()
```


소비 파일 크기를 가져옵니다

**Returns:**
java.math.BigDecimal - 소비 수량
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


계량된 공개 키와 개인 키를 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| publicKey | java.lang.String | 공개 키 |
| privateKey | java.lang.String | 개인 키 |

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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

