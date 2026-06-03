---
title: "Licentie"
second_title: "Aspose.OMR for .NET API-referentie"
description: "Biedt methoden om het component te licentiëren."
type: docs
weight: 20
url: /nl/net/aspose.omr/license/
---
## License class

Biedt methoden om het component te licentiëren.

```csharp
public class License
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [License](license)() | Initialiseert een nieuw exemplaar van deze klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Embedded](../../aspose.omr/license/embedded) { get; set; } | Licentienummer is toegevoegd als ingebedde resource. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [SetLicense](../../aspose.omr/license/setlicense#setlicense)(Stream) | Licentieert het component. |
| [SetLicense](../../aspose.omr/license/setlicense#setlicense_1)(string) | Licentieert het component. |

### Voorbeelden

In dit voorbeeld wordt geprobeerd een licentiebestand met de naam MyLicense.lic te vinden in de map die het component bevat, in de map die de aanroepende assembly bevat, in de map van de entry‑assembly en vervolgens in de ingebedde resources van de aanroepende assembly.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### Zie ook

* namespace [Aspose.OMR](../../aspose.omr)
* assembly [Aspose.OMR](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor Aspose.OMR.dll -->
