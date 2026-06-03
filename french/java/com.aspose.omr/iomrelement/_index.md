---
title: "IOmrElement"
second_title: "Référence API d'Aspose.OMR pour Java"
description: "L'interface pour les éléments OMR"
type: docs
weight: 31
url: /fr/java/com.aspose.omr/iomrelement/
---
```
public interface IOmrElement
```

L'interface pour les éléments OMR
## Méthodes

| Méthode | Description |
| --- | --- |
| [getAnswer()](#getAnswer) | Forme une chaîne avec le résultat de reconnaissance |
| [getCsv()](#getCsv) | Forme les réponses sous forme de chaîne de valeurs séparées par des virgules |
| [getQuestionName()](#getQuestionName) | Obtient le nom de la question |
| [setQuestionName(String value)](#setQuestionName-java.lang.String) | Définit le nom de la question |
### getAnswer() {#getAnswer}
```
public abstract String getAnswer()
```


Forme une chaîne avec le résultat de reconnaissance

**Returns:**
java.lang.String - Chaîne contenant le résultat de reconnaissance
### getCsv() {#getCsv}
```
public abstract String getCsv()
```


Forme les réponses sous forme de chaîne de valeurs séparées par des virgules

**Returns:**
java.lang.String - Le résultat de reconnaissance sous forme de chaîne CSV
### getQuestionName() {#getQuestionName}
```
public abstract String getQuestionName()
```


Obtient le nom de la question

**Returns:**
java.lang.String - le nom de la question
### setQuestionName(String value) {#setQuestionName-java.lang.String}
```
public abstract void setQuestionName(String value)
```


Définit le nom de la question

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | le nom de la question |

