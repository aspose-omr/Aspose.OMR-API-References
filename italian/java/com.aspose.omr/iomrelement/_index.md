---
title: "IOmrElement"
second_title: "Riferimento API Aspose.OMR per Java"
description: "L'interfaccia per gli elementi OMR"
type: docs
weight: 31
url: /it/java/com.aspose.omr/iomrelement/
---
```
public interface IOmrElement
```

L'interfaccia per gli elementi OMR
## Metodi

| Metodo | Description |
| --- | --- |
| [getAnswer()](#getAnswer) | Crea una stringa con il risultato del riconoscimento |
| [getCsv()](#getCsv) | Crea le risposte come una stringa di valori separati da virgola |
| [getQuestionName()](#getQuestionName) | Ottiene il Nome della Domanda |
| [setQuestionName(String value)](#setQuestionName-java.lang.String) | Imposta il Nome della Domanda |
### getAnswer() {#getAnswer}
```
public abstract String getAnswer()
```


Crea una stringa con il risultato del riconoscimento

**Returns:**
java.lang.String - Stringa contenente il risultato del riconoscimento
### getCsv() {#getCsv}
```
public abstract String getCsv()
```


Crea le risposte come una stringa di valori separati da virgola

**Returns:**
java.lang.String - I risultati del riconoscimento come stringa CSV
### getQuestionName() {#getQuestionName}
```
public abstract String getQuestionName()
```


Ottiene il Nome della Domanda

**Returns:**
java.lang.String - il Nome della Domanda
### setQuestionName(String value) {#setQuestionName-java.lang.String}
```
public abstract void setQuestionName(String value)
```


Imposta il Nome della Domanda

**Parameters:**
| Parametro | Tipo | Description |
| --- | --- | --- |
| valore | java.lang.String | il Nome della Domanda |

