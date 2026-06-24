---
title: "IOmrElement"
second_title: "Aspose.OMR for Java API 参考"
description: "OMR 元素的接口"
type: docs
weight: 31
url: /zh/java/com.aspose.omr/iomrelement/
---
```
public interface IOmrElement
```

OMR 元素的接口
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAnswer()](#getAnswer) | 生成包含识别结果的字符串 |
| [getCsv()](#getCsv) | 将答案形成逗号分隔值字符串 |
| [getQuestionName()](#getQuestionName) | 获取问题名称 |
| [setQuestionName(String value)](#setQuestionName-java.lang.String) | 设置问题名称 |
### getAnswer() {#getAnswer}
```
public abstract String getAnswer()
```


生成包含识别结果的字符串

**Returns:**
java.lang.String - 包含识别结果的字符串
### getCsv() {#getCsv}
```
public abstract String getCsv()
```


将答案形成逗号分隔值字符串

**Returns:**
java.lang.String - 以 CSV 字符串形式的识别结果
### getQuestionName() {#getQuestionName}
```
public abstract String getQuestionName()
```


获取问题名称

**Returns:**
java.lang.String - 问题名称
### setQuestionName(String value) {#setQuestionName-java.lang.String}
```
public abstract void setQuestionName(String value)
```


设置问题名称

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 问题名称 |

