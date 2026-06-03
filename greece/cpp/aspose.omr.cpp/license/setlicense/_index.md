---
title: "SetLicense"
second_title: "Aspose.OMR for .NET Αναφορά API"
description: "Αδειοδοτεί το στοιχείο."
type: docs
weight: 30
url: /el/net/aspose.omr/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Αδειοδοτεί το στοιχείο.

```csharp
public void SetLicense(string licenseName)
```

### Σχόλια

Προσπαθεί να βρει την άδεια στις ακόλουθες τοποθεσίες:

1. Σαφής διαδρομή.

2. Ο φάκελος που περιέχει το assembly του στοιχείου Aspose.

3. Ο φάκελος που περιέχει το assembly που καλεί ο πελάτης.

4. Ο φάκελος που περιέχει το αρχικό (startup) assembly.

5. Ένας ενσωματωμένος πόρος στην assembly κλήσης του πελάτη.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Σαφής διαδρομή.

2. Ένας ενσωματωμένος πόρος στην assembly κλήσης του πελάτη.

### Παραδείγματα

Σε αυτό το παράδειγμα, θα γίνει προσπάθεια να βρεθεί ένα αρχείο άδειας με όνομα MyLicense.lic στον φάκελο που περιέχει το στοιχείο, στον φάκελο που περιέχει το assembly που καλεί, στον φάκελο του κύριου assembly και, στη συνέχεια, στους ενσωματωμένους πόρους του assembly που καλεί.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
```

Μπορεί να είναι πλήρες ή σύντομο όνομα αρχείου ή όνομα ενσωματωμένου πόρου. Χρησιμοποιήστε μια κενή συμβολοσειρά για να μεταβείτε σε λειτουργία αξιολόγησης.

### Δείτε επίσης

* class [License](../../license)
* namespace [Aspose.OMR](../../license)
* assembly [Aspose.OMR](../../../)

---

## SetLicense(Stream) {#setlicense}

Αδειοδοτεί το στοιχείο.

```csharp
public void SetLicense(Stream stream)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Ένα stream που περιέχει την άδεια. |

### Σχόλια

Χρησιμοποιήστε αυτή τη μέθοδο για να φορτώσετε μια άδεια από ένα stream.

### Παραδείγματα

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

### Δείτε επίσης

* class [License](../../license)
* namespace [Aspose.OMR](../../license)
* assembly [Aspose.OMR](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για Aspose.OMR.dll -->
