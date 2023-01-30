---
title: License
second_title: Aspose.OMR for Java API Reference
description: Provides methods to license the component.
type: docs
weight: 19
url: /java/com.aspose.omr/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

Provides methods to license the component.

In this example, an attempt will be made to find a license file named MyLicense.lic in the folder that contains the component, in the folder that contains the calling assembly, in the folder of the entry assembly and then in the embedded resources of the calling assembly.

License license = new License();
license.setLicense("MyLicense.lic");
## Constructors

| Constructor | Description |
| --- | --- |
| [License()](#License--) | Initializes a new instance of this class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licenses the component. |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Licenses the component. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### License() {#License--}
```
public License()
```


Initializes a new instance of this class.

In this example, an attempt will be made to find a license file named MyLicense.lic in the folder that contains the component, in the folder that contains the calling assembly, in the folder of the entry assembly and then in the embedded resources of the calling assembly.

License license = new License();
license.setLicense("MyLicense.lic");

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public void setLicense(InputStream stream)
```


Licenses the component.

A stream that contains the license.

Use this method to load a license from a stream.

License license = new License();
license.setLicense(myStream);

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | license Stream |

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public void setLicense(String licenseName)
```


Licenses the component.

Tries to find the license in the following locations:

1. Explicit path.

2. The folder of the component jar file.

In this example, an attempt will be made to find a license file named MyLicense.lic in the folder that contains the component, in the folder that contains the calling assembly, in the folder of the entry assembly and then in the embedded resources of the calling assembly.

License license = new License();
license.setLicense("MyLicense.lic");

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| licenseName | java.lang.String | Can be a full or short file name or name of an embedded resource Use an empty string to switch to evaluation mode |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

