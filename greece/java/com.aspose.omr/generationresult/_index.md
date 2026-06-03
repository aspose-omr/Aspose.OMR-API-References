---
title: "GenerationResult"
second_title: "Αναφορά API του Aspose.OMR for Java"
description: "Το αποτέλεσμα της δημιουργίας προτύπου"
type: docs
weight: 14
url: /el/java/com.aspose.omr/generationresult/
---

**Inheritance:**
java.lang.Object
```
public class GenerationResult
```

Το αποτέλεσμα της δημιουργίας προτύπου. Περιέχει την εικόνα του προτύπου και το πρότυπο (json που περιγράφει τη θέση των στοιχείων στην εικόνα).
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [getErrorCode()](#getErrorCode) | Λαμβάνει ή ορίζει τον κωδικό σφάλματος. |
| [getErrorMessage()](#getErrorMessage) | Λαμβάνει ή ορίζει το μήνυμα που περιγράφει το σφάλμα. |
| [getTemplate()](#getTemplate) | Λαμβάνει τη συμβολοσειρά JSON του προτύπου |
| [getTemplateImage()](#getTemplateImage) | Λαμβάνει ή ορίζει την παραγόμενη εικόνα προτύπου |
| [getWarnings()](#getWarnings) | Λαμβάνει ή ορίζει τη λίστα των προειδοποιητικών μηνυμάτων που περιγράφουν μη κρίσιμα σφάλματα που εμφανίστηκαν κατά τη δημιουργία |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [save(String folder, String name)](#save-java.lang.String-java.lang.String) | Αποθηκεύει την εικόνα προτύπου και το πρότυπο στον καθορισμένο φάκελο |
| [setErrorCode(int value)](#setErrorCode-int) | Λαμβάνει ή ορίζει τον κωδικό σφάλματος. |
| [setErrorMessage(String value)](#setErrorMessage-java.lang.String) | Λαμβάνει ή ορίζει το μήνυμα που περιγράφει το σφάλμα. |
| [setTemplate(String value)](#setTemplate-java.lang.String) | Ορίζει τη συμβολοσειρά JSON του προτύπου |
| [setTemplateImage(BufferedImage value)](#setTemplateImage-java.awt.image.BufferedImage) | Λαμβάνει ή ορίζει την παραγόμενη εικόνα προτύπου |
| [setWarnings(List<String> value)](#setWarnings-java.util.List-java.lang.String) | Λαμβάνει ή ορίζει τη λίστα των προειδοποιητικών μηνυμάτων που περιγράφουν μη κρίσιμα σφάλματα που εμφανίστηκαν κατά τη δημιουργία |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
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


Λαμβάνει ή ορίζει τον κωδικό σφάλματος. Ισούται με 0 εάν δεν προέκυψαν σφάλματα.

**Returns:**
int - ο κωδικός σφάλματος
### getErrorMessage() {#getErrorMessage}
```
public final String getErrorMessage()
```


Λαμβάνει ή ορίζει το μήνυμα που περιγράφει το σφάλμα. Κενό εάν δεν προέκυψαν σφάλματα.

**Returns:**
java.lang.String - το μήνυμα που περιγράφει το σφάλμα
### getTemplate() {#getTemplate}
```
public final String getTemplate()
```


Λαμβάνει τη συμβολοσειρά JSON του προτύπου

**Returns:**
java.lang.String - η συμβολοσειρά JSON του προτύπου
### getTemplateImage() {#getTemplateImage}
```
public final BufferedImage getTemplateImage()
```


Λαμβάνει ή ορίζει την παραγόμενη εικόνα προτύπου

**Returns:**
java.awt.image.BufferedImage
### getWarnings() {#getWarnings}
```
public final List<String> getWarnings()
```


Λαμβάνει ή ορίζει τη λίστα των προειδοποιητικών μηνυμάτων που περιγράφουν μη κρίσιμα σφάλματα που εμφανίστηκαν κατά τη δημιουργία

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


Αποθηκεύει την εικόνα προτύπου και το πρότυπο στον καθορισμένο φάκελο

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| φάκελος | java.lang.String | Φάκελος προορισμού |
| όνομα | java.lang.String | Όνομα του προτύπου |

### setErrorCode(int value) {#setErrorCode-int}
```
public final void setErrorCode(int value)
```


Λαμβάνει ή ορίζει τον κωδικό σφάλματος. Ισούται με 0 εάν δεν προέκυψαν σφάλματα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | ο κωδικός σφάλματος |

### setErrorMessage(String value) {#setErrorMessage-java.lang.String}
```
public final void setErrorMessage(String value)
```


Λαμβάνει ή ορίζει το μήνυμα που περιγράφει το σφάλμα. Κενό εάν δεν προέκυψαν σφάλματα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | το μήνυμα που περιγράφει το σφάλμα |

### setTemplate(String value) {#setTemplate-java.lang.String}
```
public final void setTemplate(String value)
```


Ορίζει τη συμβολοσειρά JSON του προτύπου

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | η συμβολοσειρά JSON του προτύπου |

### setTemplateImage(BufferedImage value) {#setTemplateImage-java.awt.image.BufferedImage}
```
public final void setTemplateImage(BufferedImage value)
```


Λαμβάνει ή ορίζει την παραγόμενη εικόνα προτύπου

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.awt.image.BufferedImage |  |

### setWarnings(List<String> value) {#setWarnings-java.util.List-java.lang.String}
```
public final void setWarnings(List<String> value)
```


Λαμβάνει ή ορίζει τη λίστα των προειδοποιητικών μηνυμάτων που περιγράφουν μη κρίσιμα σφάλματα που εμφανίστηκαν κατά τη δημιουργία

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.List<java.lang.String> |  |

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

