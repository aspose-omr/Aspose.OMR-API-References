---
title: "IOmrElement"
second_title: "Aspose.OMR för Java API-referens"
description: "Gränssnittet för OMR-elementen"
type: docs
weight: 31
url: /sv/java/com.aspose.omr/iomrelement/
---
```
public interface IOmrElement
```

Gränssnittet för OMR-elementen
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAnswer()](#getAnswer) | Skapar en sträng med igenkänningsresultatet |
| [getCsv()](#getCsv) | Skapar svar som en kommaseparerad värdesträng |
| [getQuestionName()](#getQuestionName) | Hämtar frågans namn |
| [setQuestionName(String value)](#setQuestionName-java.lang.String) | Sätter frågans namn |
### getAnswer() {#getAnswer}
```
public abstract String getAnswer()
```


Skapar en sträng med igenkänningsresultatet

**Returns:**
java.lang.String - Sträng som innehåller igenkänningsresultatet
### getCsv() {#getCsv}
```
public abstract String getCsv()
```


Skapar svar som en kommaseparerad värdesträng

**Returns:**
java.lang.String - Igenkänningsresultaten som CSV-sträng
### getQuestionName() {#getQuestionName}
```
public abstract String getQuestionName()
```


Hämtar frågans namn

**Returns:**
java.lang.String - frågans namn
### setQuestionName(String value) {#setQuestionName-java.lang.String}
```
public abstract void setQuestionName(String value)
```


Sätter frågans namn

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | frågans namn |

