---
title: "GenerationResult"
second_title: "Aspose.OMR for Java API Referansı"
description: "Şablon oluşturmanın sonucu"
type: docs
weight: 14
url: /tr/java/com.aspose.omr/generationresult/
---

**Inheritance:**
java.lang.Object
```
public class GenerationResult
```

Şablon oluşturmanın sonucu. Şablon görüntüsünü ve şablonu (görüntü üzerindeki öğelerin konumunu tanımlayan json) içerir.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [getErrorCode()](#getErrorCode) | Hata kodunu alır veya ayarlar. |
| [getErrorMessage()](#getErrorMessage) | Hata açıklamasını içeren mesajı alır veya ayarlar. |
| [getTemplate()](#getTemplate) | Template JSON dizesini alır |
| [getTemplateImage()](#getTemplateImage) | Oluşturulan Template Image'ı alır veya ayarlar |
| [getWarnings()](#getWarnings) | Oluşturma sırasında ortaya çıkan kritik olmayan hataları açıklayan uyarı mesajları listesini alır veya ayarlar |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [save(String folder, String name)](#save-java.lang.String-java.lang.String) | Şablon görüntüsünü ve şablonu belirtilen klasöre kaydet |
| [setErrorCode(int value)](#setErrorCode-int) | Hata kodunu alır veya ayarlar. |
| [setErrorMessage(String value)](#setErrorMessage-java.lang.String) | Hata açıklamasını içeren mesajı alır veya ayarlar. |
| [setTemplate(String value)](#setTemplate-java.lang.String) | Template JSON dizesini ayarlar |
| [setTemplateImage(BufferedImage value)](#setTemplateImage-java.awt.image.BufferedImage) | Oluşturulan Template Image'ı alır veya ayarlar |
| [setWarnings(List<String> value)](#setWarnings-java.util.List-java.lang.String) | Oluşturma sırasında ortaya çıkan kritik olmayan hataları açıklayan uyarı mesajları listesini alır veya ayarlar |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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


Hata kodunu alır veya ayarlar. Hata yoksa 0'dır.

**Returns:**
int - hata kodu
### getErrorMessage() {#getErrorMessage}
```
public final String getErrorMessage()
```


Hata açıklamasını içeren mesajı alır veya ayarlar. Hata yoksa boş.

**Returns:**
java.lang.String - hata açıklamasını içeren mesaj
### getTemplate() {#getTemplate}
```
public final String getTemplate()
```


Template JSON dizesini alır

**Returns:**
java.lang.String - Template JSON dizesi
### getTemplateImage() {#getTemplateImage}
```
public final BufferedImage getTemplateImage()
```


Oluşturulan Template Image'ı alır veya ayarlar

**Returns:**
java.awt.image.BufferedImage
### getWarnings() {#getWarnings}
```
public final List<String> getWarnings()
```


Oluşturma sırasında ortaya çıkan kritik olmayan hataları açıklayan uyarı mesajları listesini alır veya ayarlar

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


Şablon görüntüsünü ve şablonu belirtilen klasöre kaydet

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| klasör | java.lang.String | Hedef klasör |
| ad | java.lang.String | Şablon adı |

### setErrorCode(int value) {#setErrorCode-int}
```
public final void setErrorCode(int value)
```


Hata kodunu alır veya ayarlar. Hata yoksa 0'dır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | hata kodu |

### setErrorMessage(String value) {#setErrorMessage-java.lang.String}
```
public final void setErrorMessage(String value)
```


Hata açıklamasını içeren mesajı alır veya ayarlar. Hata yoksa boş.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | hata açıklamasını içeren mesaj |

### setTemplate(String value) {#setTemplate-java.lang.String}
```
public final void setTemplate(String value)
```


Template JSON dizesini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Template JSON dizesi |

### setTemplateImage(BufferedImage value) {#setTemplateImage-java.awt.image.BufferedImage}
```
public final void setTemplateImage(BufferedImage value)
```


Oluşturulan Template Image'ı alır veya ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.awt.image.BufferedImage |  |

### setWarnings(List<String> value) {#setWarnings-java.util.List-java.lang.String}
```
public final void setWarnings(List<String> value)
```


Oluşturma sırasında ortaya çıkan kritik olmayan hataları açıklayan uyarı mesajları listesini alır veya ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.List<java.lang.String> |  |

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

