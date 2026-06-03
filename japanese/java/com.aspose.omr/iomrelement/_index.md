---
title: "IOmrElement"
second_title: "Aspose.OMR for Java API リファレンス"
description: "OMR要素のインターフェイス"
type: docs
weight: 31
url: /ja/java/com.aspose.omr/iomrelement/
---
```
public interface IOmrElement
```

OMR要素のインターフェイス
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAnswer()](#getAnswer) | 認識結果の文字列を作成します |
| [getCsv()](#getCsv) | 回答をカンマ区切りの文字列として作成します |
| [getQuestionName()](#getQuestionName) | 質問名を取得します |
| [setQuestionName(String value)](#setQuestionName-java.lang.String) | 質問名を設定します |
### getAnswer() {#getAnswer}
```
public abstract String getAnswer()
```


認識結果の文字列を作成します

**Returns:**
java.lang.String - 認識結果を含む文字列
### getCsv() {#getCsv}
```
public abstract String getCsv()
```


回答をカンマ区切りの文字列として作成します

**Returns:**
java.lang.String - 認識結果をCSV文字列として表したもの
### getQuestionName() {#getQuestionName}
```
public abstract String getQuestionName()
```


質問名を取得します

**Returns:**
java.lang.String - 質問名
### setQuestionName(String value) {#setQuestionName-java.lang.String}
```
public abstract void setQuestionName(String value)
```


質問名を設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 質問名 |

