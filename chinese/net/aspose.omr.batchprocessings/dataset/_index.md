---
title: "DataSet"
second_title: "Aspose.OMR 适用于 .NET API 参考"
description: "每个模板实例的字段集合。用于批量生成和批量识别 BatchOmrEngine./batchomrengine"
type: docs
weight: 110
url: /zh/net/aspose.omr.batchprocessings/dataset/
---
## DataSet class

每个模板实例的字段集合。用于批量生成和批量识别 [`BatchOmrEngine`](../batchomrengine)

```csharp
public class DataSet
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [DataSet](dataset)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Records](../../aspose.omr.batchprocessings/dataset/records) { get; set; } | 在模板生成期间惰性调用的模板实例集合 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [LoadFromJsonFile](../../aspose.omr.batchprocessings/dataset/loadfromjsonfile)(string, Encoding) | 通过路径导入 .json 文件中的数据集，适用于大数据集和小数据集 |
| static [LoadFromJsonStream](../../aspose.omr.batchprocessings/dataset/loadfromjsonstream)(Stream, Encoding) | 将流的内容反序列化为 DataSet 对象，适用于大数据集 |
| static [LoadFromJsonString](../../aspose.omr.batchprocessings/dataset/loadfromjsonstring)(string) | 从 .json 文件内容导入数据集，适用于小数据集 |

### 另请参阅

* namespace [Aspose.OMR.BatchProcessings](../../aspose.omr.batchprocessings)
* assembly [Aspose.OMR](../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OMR.dll 生成 -->
