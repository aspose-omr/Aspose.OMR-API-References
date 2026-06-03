---
title: "A consumo"
second_title: "Riferimento API Aspose.OMR per .NET"
description: "Fornisce metodi per impostare la chiave a consumo."
type: docs
weight: 10
url: /it/net/aspose.omr/metered/
---
## Metered class

Fornisce metodi per impostare la chiave a consumo.

```csharp
public class Metered
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Metered](metered)() | Inizializza una nuova istanza di questa classe. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [SetMeteredKey](../../aspose.omr/metered/setmeteredkey)(string, string) | Imposta la chiave pubblica e privata a consumo |
| static [GetConsumptionCredit](../../aspose.omr/metered/getconsumptioncredit)() | Ottiene il credito di consumo |
| static [GetConsumptionQuantity](../../aspose.omr/metered/getconsumptionquantity)() | Ottiene la dimensione del file di consumo |

### Esempi

In questo esempio, verrà tentato di impostare la chiave pubblica e privata a consumo

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

il file jar del componente:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Vedi anche

* namespace [Aspose.OMR](../../aspose.omr)
* assembly [Aspose.OMR](../../)

<!-- NON MODIFICARE: generato da xmldocmd per Aspose.OMR.dll -->
