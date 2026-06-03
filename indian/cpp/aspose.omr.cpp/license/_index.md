---
title: "लाइसेंस"
second_title: "Aspose.OMR के लिए .NET API संदर्भ"
description: "घटक को लाइसेंस करने के लिए मेथड्स प्रदान करता है।"
type: docs
weight: 20
url: /hi/net/aspose.omr/license/
---
## License class

घटक को लाइसेंस करने के लिए मेथड्स प्रदान करता है।

```csharp
public class License
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [License](license)() | इस वर्ग की नई इंस्टेंस को प्रारंभ करता है। |

## गुणधर्म

| नाम | विवरण |
| --- | --- |
| [Embedded](../../aspose.omr/license/embedded) { get; set; } | लाइसेंस संख्या को एम्बेडेड संसाधन के रूप में जोड़ा गया था। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [SetLicense](../../aspose.omr/license/setlicense#setlicense)(Stream) | घटक को लाइसेंस देता है। |
| [SetLicense](../../aspose.omr/license/setlicense#setlicense_1)(string) | घटक को लाइसेंस देता है। |

### उदाहरण

इस उदाहरण में, घटक वाली फ़ोल्डर में, कॉलिंग असेंबली वाली फ़ोल्डर में, एंट्री असेंबली वाली फ़ोल्डर में, और फिर कॉलिंग असेंबली के एम्बेडेड संसाधनों में MyLicense.lic नाम की लाइसेंस फ़ाइल खोजने का प्रयास किया जाएगा।

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### साथ में देखें

* namespace [Aspose.OMR](../../aspose.omr)
* assembly [Aspose.OMR](../../)

<!-- संपादन न करें: xmldocmd द्वारा Aspose.OMR.dll के लिए उत्पन्न -->
