---
title: Generate
second_title: Aspose.OMR for .NET API Reference
description: Generate multiple templates using layout template and set of data entries
type: docs
weight: 30
url: /net/aspose.omr.batchprocessings/batchomrengine/generate/
---
## Generate(DataSet, Stream, GlobalPageSettings, ImageCollection) {#generate}

Generate multiple templates using layout template and set of data entries

```csharp
public BatchGenerationResult Generate(DataSet dataSet, Stream layoutStream, 
    GlobalPageSettings settings = null, ImageCollection collection = null)
```

| Parameter | Type | Description |
| --- | --- | --- |
| dataSet | DataSet | Collection of data sets used in template form generation |
| layoutStream | Stream | stream with template layout |
| settings | GlobalPageSettings | page settings used in every template form generation |
| collection | ImageCollection | collection of images used in every template form generation |

### Return Value

Result of a batch template generation

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | When processing a DataRecord with an empty Id |

### See Also

* class [BatchGenerationResult](../../batchgenerationresult)
* class [DataSet](../../dataset)
* class [GlobalPageSettings](../../../aspose.omr.generation/globalpagesettings)
* class [ImageCollection](../../../aspose.omr.api/imagecollection)
* class [BatchOmrEngine](../../batchomrengine)
* namespace [Aspose.OMR.BatchProcessings](../../batchomrengine)
* assembly [Aspose.OMR](../../../)

---

## Generate(DataSet, string, GlobalPageSettings, ImageCollection) {#generate_1}

Generate multiple templates using layout template and set of data entries

```csharp
public BatchGenerationResult Generate(DataSet dataSet, string layoutPath, 
    GlobalPageSettings settings = null, ImageCollection collection = null)
```

| Parameter | Type | Description |
| --- | --- | --- |
| dataSet | DataSet | Collection of data sets used in template form generation |
| layoutPath | String | path to a file with template layout |
| settings | GlobalPageSettings | page settings used in every template form generation |
| collection | ImageCollection | collection of images used in every template form generation |

### Return Value

Result of a batch template generation

### Exceptions

| exception | condition |
| --- | --- |
| FileNotFoundException | When layoutPath is not correct |
| ArgumentException | When processing a DataRecord with an empty Id |

### See Also

* class [BatchGenerationResult](../../batchgenerationresult)
* class [DataSet](../../dataset)
* class [GlobalPageSettings](../../../aspose.omr.generation/globalpagesettings)
* class [ImageCollection](../../../aspose.omr.api/imagecollection)
* class [BatchOmrEngine](../../batchomrengine)
* namespace [Aspose.OMR.BatchProcessings](../../batchomrengine)
* assembly [Aspose.OMR](../../../)

---

## Generate(DataSet, string[], GlobalPageSettings, ImageCollection) {#generate_2}

Generate multiple templates using layout template and set of data entries

```csharp
public BatchGenerationResult Generate(DataSet dataSet, string[] layoutLines, 
    GlobalPageSettings settings = null, ImageCollection collection = null)
```

| Parameter | Type | Description |
| --- | --- | --- |
| dataSet | DataSet | Collection of data sets used in template form generation |
| layoutLines | String[] | sorted array of lines representing template layour |
| settings | GlobalPageSettings | page settings used in every template form generation |
| collection | ImageCollection | collection of images used in every template form generation |

### Return Value

Result of a batch template generation

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | When processing a DataRecord with an empty Id |

### See Also

* class [BatchGenerationResult](../../batchgenerationresult)
* class [DataSet](../../dataset)
* class [GlobalPageSettings](../../../aspose.omr.generation/globalpagesettings)
* class [ImageCollection](../../../aspose.omr.api/imagecollection)
* class [BatchOmrEngine](../../batchomrengine)
* namespace [Aspose.OMR.BatchProcessings](../../batchomrengine)
* assembly [Aspose.OMR](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.OMR.dll -->
