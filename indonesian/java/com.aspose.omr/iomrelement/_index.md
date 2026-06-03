---
title: "IOmrElement"
second_title: "Referensi API Aspose.OMR for Java"
description: "Antarmuka untuk elemen OMR"
type: docs
weight: 31
url: /id/java/com.aspose.omr/iomrelement/
---
```
public interface IOmrElement
```

Antarmuka untuk elemen OMR
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getAnswer()](#getAnswer) | Membentuk string dengan hasil pengenalan |
| [getCsv()](#getCsv) | Membentuk jawaban sebagai string nilai yang dipisahkan koma |
| [getQuestionName()](#getQuestionName) | Mendapatkan Nama Pertanyaan |
| [setQuestionName(String value)](#setQuestionName-java.lang.String) | Mengatur Nama Pertanyaan |
### getAnswer() {#getAnswer}
```
public abstract String getAnswer()
```


Membentuk string dengan hasil pengenalan

**Returns:**
java.lang.String - String yang berisi hasil pengenalan
### getCsv() {#getCsv}
```
public abstract String getCsv()
```


Membentuk jawaban sebagai string nilai yang dipisahkan koma

**Returns:**
java.lang.String - Hasil pengenalan sebagai string CSV
### getQuestionName() {#getQuestionName}
```
public abstract String getQuestionName()
```


Mendapatkan Nama Pertanyaan

**Returns:**
java.lang.String - Nama Pertanyaan
### setQuestionName(String value) {#setQuestionName-java.lang.String}
```
public abstract void setQuestionName(String value)
```


Mengatur Nama Pertanyaan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nama Pertanyaan |

