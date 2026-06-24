---
title: "IOmrElement"
second_title: "Aspose.OMR for Java API Referansı"
description: "OMR öğeleri için arayüz"
type: docs
weight: 31
url: /tr/java/com.aspose.omr/iomrelement/
---
```
public interface IOmrElement
```

OMR öğeleri için arayüz
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getAnswer()](#getAnswer) | Tanıma sonucu ile bir dize oluşturur |
| [getCsv()](#getCsv) | Cevapları virgülle ayrılmış değerler dizesi olarak oluşturur |
| [getQuestionName()](#getQuestionName) | Soru Adını alır |
| [setQuestionName(String value)](#setQuestionName-java.lang.String) | Soru Adını ayarlar |
### getAnswer() {#getAnswer}
```
public abstract String getAnswer()
```


Tanıma sonucu ile bir dize oluşturur

**Returns:**
java.lang.String - Tanıma sonucunu içeren dize
### getCsv() {#getCsv}
```
public abstract String getCsv()
```


Cevapları virgülle ayrılmış değerler dizesi olarak oluşturur

**Returns:**
java.lang.String - Tanıma sonuçları CSV dizesi olarak
### getQuestionName() {#getQuestionName}
```
public abstract String getQuestionName()
```


Soru Adını alır

**Returns:**
java.lang.String - Soru Adı
### setQuestionName(String value) {#setQuestionName-java.lang.String}
```
public abstract void setQuestionName(String value)
```


Soru Adını ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Soru Adı |

