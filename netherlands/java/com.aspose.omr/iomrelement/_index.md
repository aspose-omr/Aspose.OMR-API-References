---
title: "IOmrElement"
second_title: "Aspose.OMR for Java API-referentie"
description: "De interface voor de OMR‑elementen"
type: docs
weight: 31
url: /nl/java/com.aspose.omr/iomrelement/
---
```
public interface IOmrElement
```

De interface voor de OMR‑elementen
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getAnswer()](#getAnswer) | Maakt een tekenreeks met het herkenningsresultaat |
| [getCsv()](#getCsv) | Maakt antwoorden als een door komma's gescheiden waardenreeks |
| [getQuestionName()](#getQuestionName) | Haalt de Vraagnaam op |
| [setQuestionName(String value)](#setQuestionName-java.lang.String) | Stelt de Vraagnaam in |
### getAnswer() {#getAnswer}
```
public abstract String getAnswer()
```


Maakt een tekenreeks met het herkenningsresultaat

**Returns:**
java.lang.String - Tekenreeks die het herkenningsresultaat bevat
### getCsv() {#getCsv}
```
public abstract String getCsv()
```


Maakt antwoorden als een door komma's gescheiden waardenreeks

**Returns:**
java.lang.String - De herkenningsresultaten als CSV-tekenreeks
### getQuestionName() {#getQuestionName}
```
public abstract String getQuestionName()
```


Haalt de Vraagnaam op

**Returns:**
java.lang.String - de Vraagnaam
### setQuestionName(String value) {#setQuestionName-java.lang.String}
```
public abstract void setQuestionName(String value)
```


Stelt de Vraagnaam in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | de Vraagnaam |

