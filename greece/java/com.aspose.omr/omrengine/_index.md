---
title: "OmrEngine"
second_title: "Αναφορά API του Aspose.OMR for Java"
description: "Η μηχανή OMR"
type: docs
weight: 22
url: /el/java/com.aspose.omr/omrengine/
---

**Inheritance:**
java.lang.Object
```
public class OmrEngine
```

Η μηχανή OMR. Διαχειρίζεται τη δημιουργία του προτύπου και των κλάσεων επεξεργασίας εικόνας και των στοιχείων GUI.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [OmrEngine()](#OmrEngine) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [generateTemplate(String markupPath)](#generateTemplate-java.lang.String) | Δημιουργεί πρότυπο (.omr) και εικόνα προτύπου βάσει σήμανσης κειμένου |
| [generateTemplate(String markupPath, GlobalPageSettings settings)](#generateTemplate-java.lang.String-com.aspose.omr.GlobalPageSettings) | Δημιουργεί πρότυπο (.omr) και εικόνα προτύπου βάσει σήμανσης κειμένου |
| [generateTemplate(String markupPath, ImageCollection collection)](#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection) | Δημιουργεί πρότυπο (.omr) και εικόνα προτύπου βάσει σήμανσης κειμένου |
| [generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings)](#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection-com.aspose.omr.GlobalPageSettings) | Δημιουργεί πρότυπο (.omr) και εικόνα προτύπου βάσει σήμανσης κειμένου |
| [getClass()](#getClass) |  |
| [getTemplateProcessor(InputStream inputStream)](#getTemplateProcessor-java.io.InputStream) | Δημιουργεί το [TemplateProcessor](../../com.aspose.omr/templateprocessor/) αντικείμενο που επιτρέπει την εργασία με το καθορισμένο πρότυπο. |
| [getTemplateProcessor(String templatePath)](#getTemplateProcessor-java.lang.String) | Δημιουργεί το [TemplateProcessor](../../com.aspose.omr/templateprocessor/) αντικείμενο που επιτρέπει την εργασία με το καθορισμένο πρότυπο. |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### OmrEngine() {#OmrEngine}
```
public OmrEngine()
```


### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateTemplate(String markupPath) {#generateTemplate-java.lang.String}
```
public final GenerationResult generateTemplate(String markupPath)
```


Δημιουργεί πρότυπο (.omr) και εικόνα προτύπου βάσει σήμανσης κειμένου

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| markupPath | java.lang.String | Διαδρομή προς το αρχείο σήμανσης κειμένου |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, GlobalPageSettings settings) {#generateTemplate-java.lang.String-com.aspose.omr.GlobalPageSettings}
```
public final GenerationResult generateTemplate(String markupPath, GlobalPageSettings settings)
```


Δημιουργεί πρότυπο (.omr) και εικόνα προτύπου βάσει σήμανσης κειμένου

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| markupPath | java.lang.String | Διαδρομή προς το αρχείο σήμανσης κειμένου |
| settings | [GlobalPageSettings](../../com.aspose.omr/globalpagesettings/) | καθολικές ρυθμίσεις για κάθε σελίδα |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, ImageCollection collection) {#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection}
```
public final GenerationResult generateTemplate(String markupPath, ImageCollection collection)
```


Δημιουργεί πρότυπο (.omr) και εικόνα προτύπου βάσει σήμανσης κειμένου

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| markupPath | java.lang.String | Διαδρομή προς το αρχείο σήμανσης κειμένου |
| collection | [ImageCollection](../../com.aspose.omr/imagecollection/) | Συλλογή εικόνων που θα χρησιμοποιηθούν σε αυτή τη δημιουργία προτύπου |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings) {#generateTemplate-java.lang.String-com.aspose.omr.ImageCollection-com.aspose.omr.GlobalPageSettings}
```
public final GenerationResult generateTemplate(String markupPath, ImageCollection collection, GlobalPageSettings settings)
```


Δημιουργεί πρότυπο (.omr) και εικόνα προτύπου βάσει σήμανσης κειμένου

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| markupPath | java.lang.String | Διαδρομή προς το αρχείο σήμανσης κειμένου |
| collection | [ImageCollection](../../com.aspose.omr/imagecollection/) | Συλλογή εικόνων που θα χρησιμοποιηθούν σε αυτή τη δημιουργία προτύπου |
| settings | [GlobalPageSettings](../../com.aspose.omr/globalpagesettings/) | καθολικές ρυθμίσεις για κάθε σελίδα |

**Returns:**
[GenerationResult](../../com.aspose.omr/generationresult/) - Generation result
### getClass() {#getClass}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getTemplateProcessor(InputStream inputStream) {#getTemplateProcessor-java.io.InputStream}
```
public final TemplateProcessor getTemplateProcessor(InputStream inputStream)
```


Δημιουργεί το [TemplateProcessor](../../com.aspose.omr/templateprocessor/) αντικείμενο που επιτρέπει την εργασία με το καθορισμένο πρότυπο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| inputStream | java.io.InputStream | ροή περιεχομένου του αρχείου προτύπου OMR |

**Returns:**
[TemplateProcessor](../../com.aspose.omr/templateprocessor/) - The [TemplateProcessor](../../com.aspose.omr/templateprocessor/) instance
### getTemplateProcessor(String templatePath) {#getTemplateProcessor-java.lang.String}
```
public final TemplateProcessor getTemplateProcessor(String templatePath)
```


Δημιουργεί το [TemplateProcessor](../../com.aspose.omr/templateprocessor/) αντικείμενο που επιτρέπει την εργασία με το καθορισμένο πρότυπο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| templatePath | java.lang.String | Η διαδρομή προς το αρχείο προτύπου OMR |

**Returns:**
[TemplateProcessor](../../com.aspose.omr/templateprocessor/) - The [TemplateProcessor](../../com.aspose.omr/templateprocessor/) instance
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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

