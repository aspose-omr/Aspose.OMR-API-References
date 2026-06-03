---
title: "Άδεια"
second_title: "Αναφορά API του Aspose.OMR for Java"
description: "Παρέχει μεθόδους για την αδειοδότηση του στοιχείου"
type: docs
weight: 18
url: /el/java/com.aspose.omr/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

Παρέχει μεθόδους για την ενεργοποίηση του στοιχείου.

Σε αυτό το παράδειγμα, θα γίνει προσπάθεια να βρεθεί ένα αρχείο άδειας με όνομα MyLicense.lic στον φάκελο που περιέχει το στοιχείο, στον φάκελο που περιέχει τη κλήση της συναρμολόγησης, στον φάκελο της κύριας συναρμολόγησης και, στη συνέχεια, στους ενσωματωμένους πόρους της κλήσης της συναρμολόγησης.

License license = new License();
license.setLicense("MyLicense.lic");
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [License()](#License) | Αρχικοποιεί μια νέα παρουσία αυτής της κλάσης. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream) | Αδειοδοτεί το στοιχείο. |
| [setLicense(String licenseName)](#setLicense-java.lang.String) | Αδειοδοτεί το στοιχείο. |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### License() {#License}
```
public License()
```


Αρχικοποιεί μια νέα παρουσία αυτής της κλάσης.

Σε αυτό το παράδειγμα, θα γίνει προσπάθεια να βρεθεί ένα αρχείο άδειας με όνομα MyLicense.lic στον φάκελο που περιέχει το στοιχείο, στον φάκελο που περιέχει τη κλήση της συναρμολόγησης, στον φάκελο της κύριας συναρμολόγησης και, στη συνέχεια, στους ενσωματωμένους πόρους της κλήσης της συναρμολόγησης.

License license = new License();
license.setLicense("MyLicense.lic");

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




### setLicense(InputStream stream) {#setLicense-java.io.InputStream}
```
public void setLicense(InputStream stream)
```


Αδειοδοτεί το στοιχείο.

Μία ροή που περιέχει την άδεια.

Χρησιμοποιήστε αυτή τη μέθοδο για να φορτώσετε μια άδεια από μια ροή.

License license = new License();
license.setLicense(myStream);

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή άδειας |

### setLicense(String licenseName) {#setLicense-java.lang.String}
```
public void setLicense(String licenseName)
```


Αδειοδοτεί το στοιχείο.

Προσπαθεί να βρει την άδεια στις ακόλουθες τοποθεσίες:

1. Ρητή διαδρομή.

2. Ο φάκελος του αρχείου jar του στοιχείου.

Σε αυτό το παράδειγμα, θα γίνει προσπάθεια να βρεθεί ένα αρχείο άδειας με όνομα MyLicense.lic στον φάκελο που περιέχει το στοιχείο, στον φάκελο που περιέχει τη κλήση της συναρμολόγησης, στον φάκελο της κύριας συναρμολόγησης και, στη συνέχεια, στους ενσωματωμένους πόρους της κλήσης της συναρμολόγησης.

License license = new License();
license.setLicense("MyLicense.lic");

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| licenseName | java.lang.String | Μπορεί να είναι πλήρες ή σύντομο όνομα αρχείου ή όνομα ενσωματωμένου πόρου. Χρησιμοποιήστε μια κενή συμβολοσειρά για να μεταβείτε σε λειτουργία αξιολόγησης |

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

