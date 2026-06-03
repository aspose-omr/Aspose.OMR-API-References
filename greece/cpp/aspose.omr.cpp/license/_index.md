---
title: "Άδεια"
second_title: "Aspose.OMR for .NET Αναφορά API"
description: "Παρέχει μεθόδους για την αδειοδότηση του στοιχείου."
type: docs
weight: 20
url: /el/net/aspose.omr/license/
---
## License class

Παρέχει μεθόδους για την αδειοδότηση του στοιχείου.

```csharp
public class License
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [License](license)() | Αρχικοποιεί μια νέα παρουσία αυτής της κλάσης. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Embedded](../../aspose.omr/license/embedded) { get; set; } | Ο αριθμός άδειας προστέθηκε ως ενσωματωμένος πόρος. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [SetLicense](../../aspose.omr/license/setlicense#setlicense)(Stream) | Αδειοδοτεί το στοιχείο. |
| [SetLicense](../../aspose.omr/license/setlicense#setlicense_1)(string) | Αδειοδοτεί το στοιχείο. |

### Παραδείγματα

Σε αυτό το παράδειγμα, θα γίνει προσπάθεια να βρεθεί ένα αρχείο άδειας με όνομα MyLicense.lic στον φάκελο που περιέχει το στοιχείο, στον φάκελο που περιέχει το assembly που καλεί, στον φάκελο του κύριου assembly και, στη συνέχεια, στους ενσωματωμένους πόρους του assembly που καλεί.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### Δείτε επίσης

* namespace [Aspose.OMR](../../aspose.omr)
* assembly [Aspose.OMR](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για Aspose.OMR.dll -->
