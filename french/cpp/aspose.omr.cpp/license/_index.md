---
title: "Licence"
second_title: "Référence de l'API Aspose.OMR for .NET"
description: "Fournit des méthodes pour licencier le composant."
type: docs
weight: 20
url: /fr/net/aspose.omr/license/
---
## License class

Fournit des méthodes pour licencier le composant.

```csharp
public class License
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [License](license)() | Initialise une nouvelle instance de cette classe. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Embedded](../../aspose.omr/license/embedded) { get; set; } | Le numéro de licence a été ajouté en tant que ressource intégrée. |

## Méthodes

| Nom | Description |
| --- | --- |
| [SetLicense](../../aspose.omr/license/setlicense#setlicense)(Stream) | Licence le composant. |
| [SetLicense](../../aspose.omr/license/setlicense#setlicense_1)(string) | Licence le composant. |

### Exemples

Dans cet exemple, une tentative sera faite pour trouver un fichier de licence nommé MyLicense.lic dans le dossier contenant le composant, dans le dossier contenant l'assembly appelant, dans le dossier de l'assembly d'entrée, puis dans les ressources intégrées de l'assembly appelant.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### Voir aussi

* namespace [Aspose.OMR](../../aspose.omr)
* assembly [Aspose.OMR](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour Aspose.OMR.dll -->
