---
title: "IOmrElement"
second_title: "Aspose.OMR for Java API 참조"
description: "OMR 요소를 위한 인터페이스"
type: docs
weight: 31
url: /ko/java/com.aspose.omr/iomrelement/
---
```
public interface IOmrElement
```

OMR 요소를 위한 인터페이스
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getAnswer()](#getAnswer) | 인식 결과를 문자열로 형성합니다 |
| [getCsv()](#getCsv) | 답변을 쉼표로 구분된 문자열로 형성합니다 |
| [getQuestionName()](#getQuestionName) | 질문 이름을 가져옵니다 |
| [setQuestionName(String value)](#setQuestionName-java.lang.String) | 질문 이름을 설정합니다 |
### getAnswer() {#getAnswer}
```
public abstract String getAnswer()
```


인식 결과를 문자열로 형성합니다

**Returns:**
java.lang.String - 인식 결과를 포함하는 문자열
### getCsv() {#getCsv}
```
public abstract String getCsv()
```


답변을 쉼표로 구분된 문자열로 형성합니다

**Returns:**
java.lang.String - 인식 결과를 CSV 문자열로 표시
### getQuestionName() {#getQuestionName}
```
public abstract String getQuestionName()
```


질문 이름을 가져옵니다

**Returns:**
java.lang.String - 질문 이름
### setQuestionName(String value) {#setQuestionName-java.lang.String}
```
public abstract void setQuestionName(String value)
```


질문 이름을 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 질문 이름 |

