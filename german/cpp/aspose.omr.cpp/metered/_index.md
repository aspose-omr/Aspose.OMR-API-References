---
title: "Gemessen"
second_title: "Aspose.OMR für .NET API-Referenz"
description: "Stellt Methoden zum Festlegen des Metered-Schlüssels bereit."
type: docs
weight: 10
url: /de/net/aspose.omr/metered/
---
## Metered class

Stellt Methoden zum Festlegen des Metered-Schlüssels bereit.

```csharp
public class Metered
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Metered](metered)() | Initialisiert eine neue Instanz dieser Klasse. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SetMeteredKey](../../aspose.omr/metered/setmeteredkey)(string, string) | Setzt den Metered-öffentlichen und privaten Schlüssel |
| static [GetConsumptionCredit](../../aspose.omr/metered/getconsumptioncredit)() | Ermittelt das Verbrauchsguthaben |
| static [GetConsumptionQuantity](../../aspose.omr/metered/getconsumptionquantity)() | Ermittelt die Verbrauchsdateigröße |

### Beispiele

In diesem Beispiel wird versucht, den Metered-öffentlichen und privaten Schlüssel festzulegen.

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

die Komponenten‑Jar‑Datei:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Siehe auch

* namespace [Aspose.OMR](../../aspose.omr)
* assembly [Aspose.OMR](../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für Aspose.OMR.dll -->
