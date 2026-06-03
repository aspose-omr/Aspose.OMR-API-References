---
title: "IOmrElement"
second_title: "Справочник API Aspose.OMR для Java"
description: "Интерфейс для элементов OMR"
type: docs
weight: 31
url: /ru/java/com.aspose.omr/iomrelement/
---
```
public interface IOmrElement
```

Интерфейс для элементов OMR
## Методы

| Метод | Описание |
| --- | --- |
| [getAnswer()](#getAnswer) | Создаёт строку с результатом распознавания |
| [getCsv()](#getCsv) | Создаёт ответы в виде строки значений, разделённых запятыми |
| [getQuestionName()](#getQuestionName) | Получает имя вопроса |
| [setQuestionName(String value)](#setQuestionName-java.lang.String) | Устанавливает имя вопроса |
### getAnswer() {#getAnswer}
```
public abstract String getAnswer()
```


Создаёт строку с результатом распознавания

**Returns:**
java.lang.String - Строка, содержащая результат распознавания
### getCsv() {#getCsv}
```
public abstract String getCsv()
```


Создаёт ответы в виде строки значений, разделённых запятыми

**Returns:**
java.lang.String - Результаты распознавания в виде CSV-строки
### getQuestionName() {#getQuestionName}
```
public abstract String getQuestionName()
```


Получает имя вопроса

**Returns:**
java.lang.String - имя вопроса
### setQuestionName(String value) {#setQuestionName-java.lang.String}
```
public abstract void setQuestionName(String value)
```


Устанавливает имя вопроса

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | имя вопроса |

