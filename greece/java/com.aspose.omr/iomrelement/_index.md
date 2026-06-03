---
title: "IOmrElement"
second_title: "Αναφορά API του Aspose.OMR for Java"
description: "Η διεπαφή για τα στοιχεία OMR"
type: docs
weight: 31
url: /el/java/com.aspose.omr/iomrelement/
---
```
public interface IOmrElement
```

Η διεπαφή για τα στοιχεία OMR
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getAnswer()](#getAnswer) | Δημιουργεί μια συμβολοσειρά με το αποτέλεσμα αναγνώρισης |
| [getCsv()](#getCsv) | Δημιουργεί απαντήσεις ως συμβολοσειρά τιμών διαχωρισμένων με κόμμα |
| [getQuestionName()](#getQuestionName) | Αποκτά το Όνομα Ερώτησης |
| [setQuestionName(String value)](#setQuestionName-java.lang.String) | Ορίζει το Όνομα Ερώτησης |
### getAnswer() {#getAnswer}
```
public abstract String getAnswer()
```


Δημιουργεί μια συμβολοσειρά με το αποτέλεσμα αναγνώρισης

**Returns:**
java.lang.String - Συμβολοσειρά που περιέχει το αποτέλεσμα αναγνώρισης
### getCsv() {#getCsv}
```
public abstract String getCsv()
```


Δημιουργεί απαντήσεις ως συμβολοσειρά τιμών διαχωρισμένων με κόμμα

**Returns:**
java.lang.String - Τα αποτελέσματα αναγνώρισης ως CSV συμβολοσειρά
### getQuestionName() {#getQuestionName}
```
public abstract String getQuestionName()
```


Αποκτά το Όνομα Ερώτησης

**Returns:**
java.lang.String - το Όνομα Ερώτησης
### setQuestionName(String value) {#setQuestionName-java.lang.String}
```
public abstract void setQuestionName(String value)
```


Ορίζει το Όνομα Ερώτησης

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | το Όνομα Ερώτησης |

