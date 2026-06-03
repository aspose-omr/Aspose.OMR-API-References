---
title: "GenerationResult"
second_title: "Referencia de API de Aspose.OMR for Java"
description: "El resultado de la generación de la plantilla"
type: docs
weight: 14
url: /es/java/com.aspose.omr/generationresult/
---

**Inheritance:**
java.lang.Object
```
public class GenerationResult
```

El resultado de la generación de la plantilla. Contiene la imagen de la plantilla y la plantilla (json que describe la ubicación de los elementos en la imagen).
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [getErrorCode()](#getErrorCode) | Obtiene o establece el código de error. |
| [getErrorMessage()](#getErrorMessage) | Obtiene o establece el mensaje que describe el error. |
| [getTemplate()](#getTemplate) | Obtiene la cadena JSON de la plantilla |
| [getTemplateImage()](#getTemplateImage) | Obtiene o establece la Imagen de la Plantilla generada |
| [getWarnings()](#getWarnings) | Obtiene o establece la lista de mensajes de advertencia que describen fallas no críticas que aparecieron durante la generación |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [save(String folder, String name)](#save-java.lang.String-java.lang.String) | Guarda la imagen de la plantilla y la plantilla en la carpeta especificada |
| [setErrorCode(int value)](#setErrorCode-int) | Obtiene o establece el código de error. |
| [setErrorMessage(String value)](#setErrorMessage-java.lang.String) | Obtiene o establece el mensaje que describe el error. |
| [setTemplate(String value)](#setTemplate-java.lang.String) | Establece la cadena JSON de la plantilla |
| [setTemplateImage(BufferedImage value)](#setTemplateImage-java.awt.image.BufferedImage) | Obtiene o establece la Imagen de la Plantilla generada |
| [setWarnings(List<String> value)](#setWarnings-java.util.List-java.lang.String) | Obtiene o establece la lista de mensajes de advertencia que describen fallas no críticas que aparecieron durante la generación |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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


Obtiene o establece el código de error. Es igual a 0 si no se produjeron errores.

**Returns:**
int - el código de error
### getErrorMessage() {#getErrorMessage}
```
public final String getErrorMessage()
```


Obtiene o establece el mensaje que describe el error. Vacío si no se produjeron errores.

**Returns:**
java.lang.String - el mensaje que describe el error
### getTemplate() {#getTemplate}
```
public final String getTemplate()
```


Obtiene la cadena JSON de la plantilla

**Returns:**
java.lang.String - la cadena JSON de la plantilla
### getTemplateImage() {#getTemplateImage}
```
public final BufferedImage getTemplateImage()
```


Obtiene o establece la Imagen de la Plantilla generada

**Returns:**
java.awt.image.BufferedImage
### getWarnings() {#getWarnings}
```
public final List<String> getWarnings()
```


Obtiene o establece la lista de mensajes de advertencia que describen fallas no críticas que aparecieron durante la generación

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


Guarda la imagen de la plantilla y la plantilla en la carpeta especificada

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| carpeta | java.lang.String | Carpeta de destino |
| nombre | java.lang.String | Nombre de la plantilla |

### setErrorCode(int value) {#setErrorCode-int}
```
public final void setErrorCode(int value)
```


Obtiene o establece el código de error. Es igual a 0 si no se produjeron errores.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | el código de error |

### setErrorMessage(String value) {#setErrorMessage-java.lang.String}
```
public final void setErrorMessage(String value)
```


Obtiene o establece el mensaje que describe el error. Vacío si no se produjeron errores.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | el mensaje que describe el error |

### setTemplate(String value) {#setTemplate-java.lang.String}
```
public final void setTemplate(String value)
```


Establece la cadena JSON de la plantilla

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | la cadena JSON de la plantilla |

### setTemplateImage(BufferedImage value) {#setTemplateImage-java.awt.image.BufferedImage}
```
public final void setTemplateImage(BufferedImage value)
```


Obtiene o establece la Imagen de la Plantilla generada

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.awt.image.BufferedImage |  |

### setWarnings(List<String> value) {#setWarnings-java.util.List-java.lang.String}
```
public final void setWarnings(List<String> value)
```


Obtiene o establece la lista de mensajes de advertencia que describen fallas no críticas que aparecieron durante la generación

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.List<java.lang.String> |  |

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

