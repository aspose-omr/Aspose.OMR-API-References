---
title: "识别"
second_title: "Aspose.OMR 适用于 .NET API 参考"
description: "识别文件夹或文件"
type: docs
weight: 20
url: /zh/net/aspose.omr.batchprocessings/batchtemplateprocessor/recognize/
---
## Recognize(string, int) {#recognize_2}

识别文件夹或文件

```csharp
public BatchRecognitionResult Recognize(string path, int recognitionThreshold = -100)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| 路径 | String | 文件夹或文件的路径 |
| recognitionThreshold | Int32 | （可选）识别阈值，范围为 (0..100)。仅阈值以上填充的元素会被计为已填充。 |

### 返回值

文件或文件夹内所有文件的批量识别结果

### 异常

| 异常 | 条件 |
| --- | --- |
| FileNotFoundException | 如果路径对文件夹和文件均无效 |

### 另请参阅

* class [BatchRecognitionResult](../../batchrecognitionresult)
* class [BatchTemplateProcessor](../../batchtemplateprocessor)
* namespace [Aspose.OMR.BatchProcessings](../../batchtemplateprocessor)
* assembly [Aspose.OMR](../../../)

---

## Recognize(Stream, int) {#recognize_1}

从流中识别单个模板

```csharp
public BatchRecognitionResult Recognize(Stream stream, int recognitionThreshold = -100)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| 流 | Stream | 带有单个模板的可读流 |
| recognitionThreshold | Int32 | （可选）识别阈值，范围为 (0..100)。仅阈值以上填充的元素会被计为已填充。 |

### 返回值

批量识别单个模板表单的结果

### 另请参阅

* class [BatchRecognitionResult](../../batchrecognitionresult)
* class [BatchTemplateProcessor](../../batchtemplateprocessor)
* namespace [Aspose.OMR.BatchProcessings](../../batchtemplateprocessor)
* assembly [Aspose.OMR](../../../)

---

## Recognize(IEnumerable&lt;string&gt;, int) {#recognize}

识别多个文件

```csharp
public BatchRecognitionResult Recognize(IEnumerable<string> files, int recognitionThreshold = -100)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| 文件 | IEnumerable`1 | 文件完整路径的集合 |
| recognitionThreshold | Int32 | （可选）识别阈值，范围为 (0..100)。仅阈值以上填充的元素会被计为已填充。 |

### 返回值

批量识别多个表单的结果

### 另请参阅

* class [BatchRecognitionResult](../../batchrecognitionresult)
* class [BatchTemplateProcessor](../../batchtemplateprocessor)
* namespace [Aspose.OMR.BatchProcessings](../../batchtemplateprocessor)
* assembly [Aspose.OMR](../../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OMR.dll 生成 -->
