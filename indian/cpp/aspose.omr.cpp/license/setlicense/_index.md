---
title: "SetLicense"
second_title: "Aspose.OMR के लिए .NET API संदर्भ"
description: "घटक को लाइसेंस देता है।"
type: docs
weight: 30
url: /hi/net/aspose.omr/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

घटक को लाइसेंस देता है।

```csharp
public void SetLicense(string licenseName)
```

### टिप्पणियाँ

निम्नलिखित स्थानों में लाइसेंस खोजने का प्रयास करता है:

1. स्पष्ट पथ।

2. Aspose घटक असेंबली वाली फ़ोल्डर।

3. क्लाइंट की कॉलिंग असेंबली वाली फ़ोल्डर।

4. एंट्री (स्टार्टअप) असेंबली को शामिल करने वाला फ़ोल्डर।

5. क्लाइंट की कॉलिंग असेंबली में एक एम्बेडेड रिसोर्स।

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. स्पष्ट पथ।

2. क्लाइंट की कॉलिंग असेंबली में एक एम्बेडेड रिसोर्स।

### उदाहरण

इस उदाहरण में, घटक वाली फ़ोल्डर में, कॉलिंग असेंबली वाली फ़ोल्डर में, एंट्री असेंबली वाली फ़ोल्डर में, और फिर कॉलिंग असेंबली के एम्बेडेड संसाधनों में MyLicense.lic नाम की लाइसेंस फ़ाइल खोजने का प्रयास किया जाएगा।

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
```

पूरा या छोटा फ़ाइल नाम या एम्बेडेड रिसोर्स का नाम हो सकता है। मूल्यांकन मोड में स्विच करने के लिए खाली स्ट्रिंग का उपयोग करें।

### साथ में देखें

* class [License](../../license)
* namespace [Aspose.OMR](../../license)
* assembly [Aspose.OMR](../../../)

---

## SetLicense(Stream) {#setlicense}

घटक को लाइसेंस देता है।

```csharp
public void SetLicense(Stream stream)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | एक स्ट्रीम जिसमें लाइसेंस शामिल है। |

### टिप्पणियाँ

इस मेथड का उपयोग करके स्ट्रीम से लाइसेंस लोड करें।

### उदाहरण

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

### साथ में देखें

* class [License](../../license)
* namespace [Aspose.OMR](../../license)
* assembly [Aspose.OMR](../../../)

<!-- संपादन न करें: xmldocmd द्वारा Aspose.OMR.dll के लिए उत्पन्न -->
