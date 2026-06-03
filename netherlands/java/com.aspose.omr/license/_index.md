---
title: "Licentie"
second_title: "Aspose.OMR for Java API-referentie"
description: "Biedt methoden om de component te licentiëren"
type: docs
weight: 18
url: /nl/java/com.aspose.omr/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

Biedt methoden om het component te licentiëren.

In dit voorbeeld wordt geprobeerd een licentiebestand met de naam MyLicense.lic te vinden in de map die het component bevat, in de map die de aanroepende assembly bevat, in de map van de entry-assembly en vervolgens in de ingebedde resources van de aanroepende assembly.

License license = new License();
license.setLicense("MyLicense.lic");
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [License()](#License) | Initialiseert een nieuw exemplaar van deze klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream) | Licentieert de component. |
| [setLicense(String licenseName)](#setLicense-java.lang.String) | Licentieert de component. |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### License() {#License}
```
public License()
```


Initialiseert een nieuw exemplaar van deze klasse.

In dit voorbeeld wordt geprobeerd een licentiebestand met de naam MyLicense.lic te vinden in de map die het component bevat, in de map die de aanroepende assembly bevat, in de map van de entry-assembly en vervolgens in de ingebedde resources van de aanroepende assembly.

License license = new License();
license.setLicense("MyLicense.lic");

### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Licentieert de component.

Een stream die de licentie bevat.

Gebruik deze methode om een licentie uit een stream te laden.

License license = new License();
license.setLicense(myStream);

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | java.io.InputStream | licentie Stream |

### setLicense(String licenseName) {#setLicense-java.lang.String}
```
public void setLicense(String licenseName)
```


Licentieert de component.

Probeert de licentie te vinden op de volgende locaties:

1. Expliciet pad.

2. De map van het component‑jar‑bestand.

In dit voorbeeld wordt geprobeerd een licentiebestand met de naam MyLicense.lic te vinden in de map die het component bevat, in de map die de aanroepende assembly bevat, in de map van de entry-assembly en vervolgens in de ingebedde resources van de aanroepende assembly.

License license = new License();
license.setLicense("MyLicense.lic");

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| licenseName | java.lang.String | Kan een volledige of korte bestandsnaam of de naam van een ingebedde resource zijn. Gebruik een lege string om over te schakelen naar evaluatiemodus. |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

