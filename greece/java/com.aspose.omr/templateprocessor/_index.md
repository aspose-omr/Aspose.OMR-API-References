---
title: "TemplateProcessor"
second_title: "Αναφορά API του Aspose.OMR for Java"
description: "Κλάση για επεξεργασία προτύπων και εικόνων"
type: docs
weight: 30
url: /el/java/com.aspose.omr/templateprocessor/
---

**Inheritance:**
java.lang.Object
```
public class TemplateProcessor
```

Κλάση για την επεξεργασία προτύπων και εικόνων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [recalculate(RecognitionResult result)](#recalculate-com.aspose.omr.RecognitionResult) | Ενημερώνει το αποτέλεσμα αναγνώρισης χρησιμοποιώντας λεπτομερείς παραμέτρους. |
| [recalculate(RecognitionResult result, int recognitionThreshold)](#recalculate-com.aspose.omr.RecognitionResult-int) | Ενημερώνει το αποτέλεσμα αναγνώρισης χρησιμοποιώντας λεπτομερείς παραμέτρους. |
| [recognizeImage(BufferedImage bufferedImage)](#recognizeImage-java.awt.image.BufferedImage) | Αναγνωρίζει εικόνα |
| [recognizeImage(BufferedImage bufferedImage, int recognitionThreshold)](#recognizeImage-java.awt.image.BufferedImage-int) | Αναγνωρίζει εικόνα |
| [recognizeImage(InputStream inputStream)](#recognizeImage-java.io.InputStream) | Αναγνωρίζει εικόνα |
| [recognizeImage(InputStream inputStream, int recognitionThreshold)](#recognizeImage-java.io.InputStream-int) | Αναγνωρίζει εικόνα |
| [recognizeImage(String imagePath)](#recognizeImage-java.lang.String) | Αναγνωρίζει εικόνα |
| [recognizeImage(String imagePath, int recognitionThreshold)](#recognizeImage-java.lang.String-int) | Αναγνωρίζει εικόνα |
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




### recalculate(RecognitionResult result) {#recalculate-com.aspose.omr.RecognitionResult}
```
public final void recalculate(RecognitionResult result)
```


Ενημερώνει το αποτέλεσμα αναγνώρισης χρησιμοποιώντας λεπτομερείς παραμέτρους.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| result | [RecognitionResult](../../com.aspose.omr/recognitionresult/) | Το αποτέλεσμα αναγνώρισης προς ενημέρωση. |

### recalculate(RecognitionResult result, int recognitionThreshold) {#recalculate-com.aspose.omr.RecognitionResult-int}
```
public final void recalculate(RecognitionResult result, int recognitionThreshold)
```


Ενημερώνει το αποτέλεσμα αναγνώρισης χρησιμοποιώντας λεπτομερείς παραμέτρους.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| result | [RecognitionResult](../../com.aspose.omr/recognitionresult/) | Το αποτέλεσμα αναγνώρισης προς ενημέρωση. |
| recognitionThreshold | int | (Προαιρετικό) Το όριο αναγνώρισης στο εύρος (0..100). Μόνο τα στοιχεία που είναι γεμάτα πάνω από το όριο θα λογίζονται ως γεμάτα. |

### recognizeImage(BufferedImage bufferedImage) {#recognizeImage-java.awt.image.BufferedImage}
```
public final RecognitionResult recognizeImage(BufferedImage bufferedImage)
```


Αναγνωρίζει εικόνα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bufferedImage | java.awt.image.BufferedImage | Εικόνα προς αναγνώριση |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(BufferedImage bufferedImage, int recognitionThreshold) {#recognizeImage-java.awt.image.BufferedImage-int}
```
public final RecognitionResult recognizeImage(BufferedImage bufferedImage, int recognitionThreshold)
```


Αναγνωρίζει εικόνα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bufferedImage | java.awt.image.BufferedImage | Εικόνα προς αναγνώριση |
| recognitionThreshold | int | (Προαιρετικό) Το όριο αναγνώρισης στο εύρος (0..100). Μόνο τα στοιχεία που είναι γεμάτα πάνω από το όριο θα λογίζονται ως γεμάτα. |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(InputStream inputStream) {#recognizeImage-java.io.InputStream}
```
public final RecognitionResult recognizeImage(InputStream inputStream)
```


Αναγνωρίζει εικόνα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| inputStream | java.io.InputStream | Ροή της εικόνας |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(InputStream inputStream, int recognitionThreshold) {#recognizeImage-java.io.InputStream-int}
```
public final RecognitionResult recognizeImage(InputStream inputStream, int recognitionThreshold)
```


Αναγνωρίζει εικόνα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| inputStream | java.io.InputStream | Ροή της εικόνας |
| recognitionThreshold | int | (Προαιρετικό) Το όριο αναγνώρισης στο εύρος (0..100). Μόνο τα στοιχεία που είναι γεμάτα πάνω από το όριο θα λογίζονται ως γεμάτα. |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(String imagePath) {#recognizeImage-java.lang.String}
```
public final RecognitionResult recognizeImage(String imagePath)
```


Αναγνωρίζει εικόνα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| imagePath | java.lang.String | Η διαδρομή προς την εικόνα προς αναγνώριση |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
### recognizeImage(String imagePath, int recognitionThreshold) {#recognizeImage-java.lang.String-int}
```
public final RecognitionResult recognizeImage(String imagePath, int recognitionThreshold)
```


Αναγνωρίζει εικόνα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| imagePath | java.lang.String | Η διαδρομή προς την εικόνα προς αναγνώριση |
| recognitionThreshold | int | (Προαιρετικό) Το όριο αναγνώρισης στο εύρος (0..100). Μόνο τα στοιχεία που είναι γεμάτα πάνω από το όριο θα λογίζονται ως γεμάτα. |

**Returns:**
[RecognitionResult](../../com.aspose.omr/recognitionresult/) - The recognition result
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

