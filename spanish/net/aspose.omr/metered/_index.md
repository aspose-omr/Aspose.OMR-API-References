---
title: Metered
second_title: Referencia de API de Aspose.OMR para .NET
description: Proporciona métodos para configurar la clave medida.
type: docs
weight: 640
url: /es/net/aspose.omr/metered/
---
## Metered class

Proporciona métodos para configurar la clave medida.

```csharp
public class Metered
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Metered](metered)() | Constructor predeterminado |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [SetMeteredKey](../../aspose.omr/metered/setmeteredkey)(string, string) | Establece claves públicas y privadas medidas |
| static [GetConsumptionCredit](../../aspose.omr/metered/getconsumptioncredit)() | Obtiene crédito de consumo |
| static [GetConsumptionQuantity](../../aspose.omr/metered/getconsumptionquantity)() | Obtiene el tamaño del archivo de consumo |

### Ejemplos

En este ejemplo, se intentará establecer una clave pública y privada medidas

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### Ver también

* espacio de nombres [Aspose.OMR](../../aspose.omr)
* asamblea [Aspose.OMR](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.OMR.dll -->