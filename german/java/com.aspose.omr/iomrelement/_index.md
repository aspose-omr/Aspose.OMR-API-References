---
title: "IOmrElement"
second_title: "Aspose.OMR für Java API-Referenz"
description: "Die Schnittstelle für die OMR-Elemente"
type: docs
weight: 31
url: /de/java/com.aspose.omr/iomrelement/
---
```
public interface IOmrElement
```

Die Schnittstelle für die OMR-Elemente
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAnswer()](#getAnswer) | Erstellt einen String mit dem Erkennungsergebnis |
| [getCsv()](#getCsv) | Erstellt Antworten als kommagetrennten Werte-String |
| [getQuestionName()](#getQuestionName) | Liest den Fragenname |
| [setQuestionName(String value)](#setQuestionName-java.lang.String) | Setzt den Fragenname |
### getAnswer() {#getAnswer}
```
public abstract String getAnswer()
```


Erstellt einen String mit dem Erkennungsergebnis

**Returns:**
java.lang.String - String, der das Erkennungsergebnis enthält
### getCsv() {#getCsv}
```
public abstract String getCsv()
```


Erstellt Antworten als kommagetrennten Werte-String

**Returns:**
java.lang.String - Das Erkennungsergebnis als CSV-String
### getQuestionName() {#getQuestionName}
```
public abstract String getQuestionName()
```


Liest den Fragenname

**Returns:**
java.lang.String - der Fragenname
### setQuestionName(String value) {#setQuestionName-java.lang.String}
```
public abstract void setQuestionName(String value)
```


Setzt den Fragenname

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | der Fragenname |

