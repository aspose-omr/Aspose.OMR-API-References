---
title: "识别"
second_title: "Aspose.OMR 适用于 .NET API 参考"
description: "识别文件"
type: docs
weight: 30
url: /zh/net/aspose.omr.api/templateprocessor/recognize/
---
## Recognize(string, int) {#recognize_2}

识别文件

```csharp
public RecognitionResult Recognize(string filePath, int recognitionThreshold = -100)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| filePath | String | 待识别文件的路径 |
| recognitionThreshold | Int32 | （可选）识别阈值，范围为 (0..100)。仅阈值以上填充的元素会被计为已填充。 |

### 返回值

识别结果

### 另请参阅

* class [RecognitionResult](../../../aspose.omr.model/recognitionresult)
* class [TemplateProcessor](../../templateprocessor)
* namespace [Aspose.OMR.Api](../../templateprocessor)
* assembly [Aspose.OMR](../../../)

---

## Recognize(string[], int) {#recognize_3}

将多个文件识别为单个多页文件

```csharp
public RecognitionResult Recognize(string[] filePaths, int recognitionThreshold = -100)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| filePaths | String[] | 待识别文件的路径 |
| recognitionThreshold | Int32 | （可选）识别阈值，范围为 (0..100)。仅阈值以上填充的元素会被计为已填充。 |

### 返回值

识别结果

### 另请参阅

* class [RecognitionResult](../../../aspose.omr.model/recognitionresult)
* class [TemplateProcessor](../../templateprocessor)
* namespace [Aspose.OMR.Api](../../templateprocessor)
* assembly [Aspose.OMR](../../../)

---

## Recognize(Stream, int) {#recognize}

从流中识别文件

```csharp
public RecognitionResult Recognize(Stream stream, int recognitionThreshold = -100)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| 流 | Stream | 文件的流。 |
| recognitionThreshold | Int32 | （可选）识别阈值，范围为 (0..100)。仅阈值以上填充的元素会被计为已填充。 |

### 返回值

识别结果

### 另请参阅

* class [RecognitionResult](../../../aspose.omr.model/recognitionresult)
* class [TemplateProcessor](../../templateprocessor)
* namespace [Aspose.OMR.Api](../../templateprocessor)
* assembly [Aspose.OMR](../../../)

---

## Recognize(Stream[], int) {#recognize_1}

从流中识别文件集合

```csharp
public RecognitionResult Recognize(Stream[] streams, int recognitionThreshold = -100)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| streams | Stream[] | 文件流的集合。 |
| recognitionThreshold | Int32 | （可选）识别阈值，范围为 (0..100)。仅阈值以上填充的元素会被计为已填充。 |

### 返回值

识别结果

### 另请参阅

* class [RecognitionResult](../../../aspose.omr.model/recognitionresult)
* class [TemplateProcessor](../../templateprocessor)
* namespace [Aspose.OMR.Api](../../templateprocessor)
* assembly [Aspose.OMR](../../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OMR.dll 生成 -->
