---
title: "Licence"
second_title: "Référence de l'API Aspose.OMR for .NET"
description: "Initialise une nouvelle instance de cette classe."
type: docs
weight: 10
url: /fr/net/aspose.omr/license/license/
---
## License constructor

Initialise une nouvelle instance de cette classe.

```csharp
public License()
```

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

* class [License](../../license)
* namespace [Aspose.OMR](../../license)
* assembly [Aspose.OMR](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour Aspose.OMR.dll -->
