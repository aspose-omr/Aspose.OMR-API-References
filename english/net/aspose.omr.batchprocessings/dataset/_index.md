---
title: DataSet
second_title: Aspose.OMR for .NET API Reference
description: Collection of fields for each of the template instances. Used for batch Generation and batch Recognition BatchOmrEngine./batchomrengine
type: docs
weight: 910
url: /net/aspose.omr.batchprocessings/dataset/
---
## DataSet class

Collection of fields for each of the template instances. Used for batch Generation and batch Recognition [`BatchOmrEngine`](../batchomrengine)

```csharp
public class DataSet
```

## Constructors

| Name | Description |
| --- | --- |
| [DataSet](dataset)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Records](../../aspose.omr.batchprocessings/dataset/records) { get; set; } | Collection of the template instances Lazilly called during template generations |

## Methods

| Name | Description |
| --- | --- |
| static [LoadFromJsonFile](../../aspose.omr.batchprocessings/dataset/loadfromjsonfile)(string, Encoding) | Import dataset from .json file by path Suiatable for big and small datasets |
| static [LoadFromJsonStream](../../aspose.omr.batchprocessings/dataset/loadfromjsonstream)(Stream, Encoding) | Deserialize content of stream into DataSet object Suiatable for big datasets |
| static [LoadFromJsonString](../../aspose.omr.batchprocessings/dataset/loadfromjsonstring)(string) | Import dataset from .json file content Suiatable for small datasets |

### See Also

* namespace [Aspose.OMR.BatchProcessings](../../aspose.omr.batchprocessings)
* assembly [Aspose.OMR](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.OMR.dll -->