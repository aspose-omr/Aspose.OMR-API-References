---
title: "Licenza"
second_title: "Riferimento API Aspose.OMR per .NET"
description: "Fornisce metodi per licenziare il componente."
type: docs
weight: 20
url: /it/net/aspose.omr/license/
---
## License class

Fornisce metodi per licenziare il componente.

```csharp
public class License
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [License](license)() | Inizializza una nuova istanza di questa classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Embedded](../../aspose.omr/license/embedded) { get; set; } | Il numero di licenza è stato aggiunto come risorsa incorporata. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [SetLicense](../../aspose.omr/license/setlicense#setlicense)(Stream) | Concede licenza al componente. |
| [SetLicense](../../aspose.omr/license/setlicense#setlicense_1)(string) | Concede licenza al componente. |

### Esempi

In questo esempio, si cercherà di trovare un file di licenza denominato MyLicense.lic nella cartella che contiene il componente, nella cartella che contiene l'assembly chiamante, nella cartella dell'assembly di ingresso e quindi nelle risorse incorporate dell'assembly chiamante.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### Vedi anche

* namespace [Aspose.OMR](../../aspose.omr)
* assembly [Aspose.OMR](../../)

<!-- NON MODIFICARE: generato da xmldocmd per Aspose.OMR.dll -->
