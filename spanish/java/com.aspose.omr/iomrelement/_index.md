---
title: "IOmrElement"
second_title: "Referencia de API de Aspose.OMR for Java"
description: "La interfaz para los elementos OMR"
type: docs
weight: 31
url: /es/java/com.aspose.omr/iomrelement/
---
```
public interface IOmrElement
```

La interfaz para los elementos OMR
## Métodos

| Método | Descripción |
| --- | --- |
| [getAnswer()](#getAnswer) | Forma una cadena con el resultado del reconocimiento |
| [getCsv()](#getCsv) | Forma respuestas como una cadena de valores separados por comas |
| [getQuestionName()](#getQuestionName) | Obtiene el Nombre de la Pregunta |
| [setQuestionName(String value)](#setQuestionName-java.lang.String) | Establece el Nombre de la Pregunta |
### getAnswer() {#getAnswer}
```
public abstract String getAnswer()
```


Forma una cadena con el resultado del reconocimiento

**Returns:**
java.lang.String - Cadena que contiene el resultado del reconocimiento
### getCsv() {#getCsv}
```
public abstract String getCsv()
```


Forma respuestas como una cadena de valores separados por comas

**Returns:**
java.lang.String - Los resultados del reconocimiento como cadena CSV
### getQuestionName() {#getQuestionName}
```
public abstract String getQuestionName()
```


Obtiene el Nombre de la Pregunta

**Returns:**
java.lang.String - el Nombre de la Pregunta
### setQuestionName(String value) {#setQuestionName-java.lang.String}
```
public abstract void setQuestionName(String value)
```


Establece el Nombre de la Pregunta

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | el Nombre de la Pregunta |

