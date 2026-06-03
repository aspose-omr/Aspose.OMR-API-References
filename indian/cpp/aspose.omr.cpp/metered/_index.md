---
title: "मीटरड"
second_title: "Aspose.OMR के लिए .NET API संदर्भ"
description: "मीटरड कुंजी सेट करने के लिए मेथड्स प्रदान करता है।"
type: docs
weight: 10
url: /hi/net/aspose.omr/metered/
---
## Metered class

मीटरड कुंजी सेट करने के लिए मेथड्स प्रदान करता है।

```csharp
public class Metered
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [Metered](metered)() | इस वर्ग की नई इंस्टेंस को प्रारंभ करता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [SetMeteredKey](../../aspose.omr/metered/setmeteredkey)(string, string) | मीटरड सार्वजनिक और निजी कुंजी सेट करता है। |
| static [GetConsumptionCredit](../../aspose.omr/metered/getconsumptioncredit)() | उपभोग क्रेडिट प्राप्त करता है। |
| static [GetConsumptionQuantity](../../aspose.omr/metered/getconsumptionquantity)() | उपभोग फ़ाइल आकार प्राप्त करता है। |

### उदाहरण

इस उदाहरण में, मीटरड सार्वजनिक और निजी कुंजी सेट करने का प्रयास किया जाएगा।

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

घटक जार फ़ाइल:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### साथ में देखें

* namespace [Aspose.OMR](../../aspose.omr)
* assembly [Aspose.OMR](../../)

<!-- संपादन न करें: xmldocmd द्वारा Aspose.OMR.dll के लिए उत्पन्न -->
