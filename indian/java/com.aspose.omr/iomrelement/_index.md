---
title: "IOmrElement"
second_title: "Aspose.OMR Java के लिए API रेफ़रेंस"
description: "OMR तत्वों के लिए इंटरफ़ेस"
type: docs
weight: 31
url: /hi/java/com.aspose.omr/iomrelement/
---
```
public interface IOmrElement
```

OMR तत्वों के लिए इंटरफ़ेस
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getAnswer()](#getAnswer) | पहचान परिणाम के साथ एक स्ट्रिंग बनाता है |
| [getCsv()](#getCsv) | जवाबों को कॉमा‑सेपरेटेड वैल्यूज़ स्ट्रिंग के रूप में बनाता है |
| [getQuestionName()](#getQuestionName) | प्रश्न का नाम प्राप्त करता है |
| [setQuestionName(String value)](#setQuestionName-java.lang.String) | प्रश्न का नाम सेट करता है |
### getAnswer() {#getAnswer}
```
public abstract String getAnswer()
```


पहचान परिणाम के साथ एक स्ट्रिंग बनाता है

**Returns:**
java.lang.String - पहचान परिणाम वाली स्ट्रिंग
### getCsv() {#getCsv}
```
public abstract String getCsv()
```


जवाबों को कॉमा‑सेपरेटेड वैल्यूज़ स्ट्रिंग के रूप में बनाता है

**Returns:**
java.lang.String - पहचान परिणाम CSV स्ट्रिंग के रूप में
### getQuestionName() {#getQuestionName}
```
public abstract String getQuestionName()
```


प्रश्न का नाम प्राप्त करता है

**Returns:**
java.lang.String - प्रश्न का नाम
### setQuestionName(String value) {#setQuestionName-java.lang.String}
```
public abstract void setQuestionName(String value)
```


प्रश्न का नाम सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String | प्रश्न का नाम |

