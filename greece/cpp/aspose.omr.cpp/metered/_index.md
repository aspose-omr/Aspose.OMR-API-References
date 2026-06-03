---
title: "Μετρημένο"
second_title: "Aspose.OMR for .NET Αναφορά API"
description: "Παρέχει μεθόδους για τον ορισμό του μετρημένου κλειδιού."
type: docs
weight: 10
url: /el/net/aspose.omr/metered/
---
## Metered class

Παρέχει μεθόδους για τον ορισμό του μετρημένου κλειδιού.

```csharp
public class Metered
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Metered](metered)() | Αρχικοποιεί μια νέα παρουσία αυτής της κλάσης. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [SetMeteredKey](../../aspose.omr/metered/setmeteredkey)(string, string) | Ορίζει το μετρημένο δημόσιο και ιδιωτικό κλειδί |
| static [GetConsumptionCredit](../../aspose.omr/metered/getconsumptioncredit)() | Λαμβάνει πίστωση κατανάλωσης |
| static [GetConsumptionQuantity](../../aspose.omr/metered/getconsumptionquantity)() | Λαμβάνει το μέγεθος αρχείου κατανάλωσης |

### Παραδείγματα

Σε αυτό το παράδειγμα, θα γίνει προσπάθεια να οριστεί το μετρημένο δημόσιο και ιδιωτικό κλειδί

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

το αρχείο jar του στοιχείου:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Δείτε επίσης

* namespace [Aspose.OMR](../../aspose.omr)
* assembly [Aspose.OMR](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για Aspose.OMR.dll -->
