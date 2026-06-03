---
title: "Lizenz"
second_title: "Aspose.OMR für .NET API-Referenz"
description: "Stellt Methoden zur Lizenzierung der Komponente bereit."
type: docs
weight: 20
url: /de/net/aspose.omr/license/
---
## License class

Stellt Methoden zur Lizenzierung der Komponente bereit.

```csharp
public class License
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [License](license)() | Initialisiert eine neue Instanz dieser Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Embedded](../../aspose.omr/license/embedded) { get; set; } | Lizenznummer wurde als eingebettete Ressource hinzugefügt. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SetLicense](../../aspose.omr/license/setlicense#setlicense)(Stream) | Lizenziert die Komponente. |
| [SetLicense](../../aspose.omr/license/setlicense#setlicense_1)(string) | Lizenziert die Komponente. |

### Beispiele

In diesem Beispiel wird versucht, eine Lizenzdatei mit dem Namen MyLicense.lic im Ordner zu finden, der die Komponente enthält, im Ordner, der die aufrufende Assembly enthält, im Ordner der Einstieg‑Assembly und anschließend in den eingebetteten Ressourcen der aufrufenden Assembly.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### Siehe auch

* namespace [Aspose.OMR](../../aspose.omr)
* assembly [Aspose.OMR](../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für Aspose.OMR.dll -->
