---
title: "生成"
second_title: "Aspose.OMR 适用于 .NET API 参考"
description: "使用布局模板和一组数据条目生成多个模板"
type: docs
weight: 30
url: /zh/net/aspose.omr.batchprocessings/batchomrengine/generate/
---
## Generate(DataSet, Stream, GlobalPageSettings, ImageCollection) {#generate}

使用布局模板和一组数据条目生成多个模板

```csharp
public BatchGenerationResult Generate(DataSet dataSet, Stream layoutStream, 
    GlobalPageSettings settings = null, ImageCollection collection = null)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| dataSet | DataSet | 用于模板表单生成的数据集集合 |
| layoutStream | Stream | 带有模板布局的流 |
| settings | 全局页面设置 | 在每个模板表单生成中使用的页面设置 |
| collection | ImageCollection | 在每个模板表单生成中使用的图像集合 |

### 返回值

批量模板生成的结果

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 当处理具有空 Id 的 DataRecord 时 |

### 另请参阅

* class [BatchGenerationResult](../../batchgenerationresult)
* class [DataSet](../../dataset)
* class [GlobalPageSettings](../../../aspose.omr.generation/globalpagesettings)
* class [ImageCollection](../../../aspose.omr.api/imagecollection)
* class [BatchOmrEngine](../../batchomrengine)
* namespace [Aspose.OMR.BatchProcessings](../../batchomrengine)
* assembly [Aspose.OMR](../../../)

---

## Generate(DataSet, string, GlobalPageSettings, ImageCollection) {#generate_1}

使用布局模板和一组数据条目生成多个模板

```csharp
public BatchGenerationResult Generate(DataSet dataSet, string layoutPath, 
    GlobalPageSettings settings = null, ImageCollection collection = null)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| dataSet | DataSet | 用于模板表单生成的数据集集合 |
| layoutPath | String | 指向包含模板布局的文件的路径 |
| settings | 全局页面设置 | 在每个模板表单生成中使用的页面设置 |
| collection | ImageCollection | 在每个模板表单生成中使用的图像集合 |

### 返回值

批量模板生成的结果

### 异常

| 异常 | 条件 |
| --- | --- |
| FileNotFoundException | 当 layoutPath 不正确时 |
| ArgumentException | 当处理具有空 Id 的 DataRecord 时 |

### 另请参阅

* class [BatchGenerationResult](../../batchgenerationresult)
* class [DataSet](../../dataset)
* class [GlobalPageSettings](../../../aspose.omr.generation/globalpagesettings)
* class [ImageCollection](../../../aspose.omr.api/imagecollection)
* class [BatchOmrEngine](../../batchomrengine)
* namespace [Aspose.OMR.BatchProcessings](../../batchomrengine)
* assembly [Aspose.OMR](../../../)

---

## Generate(DataSet, string[], GlobalPageSettings, ImageCollection) {#generate_2}

使用布局模板和一组数据条目生成多个模板

```csharp
public BatchGenerationResult Generate(DataSet dataSet, string[] layoutLines, 
    GlobalPageSettings settings = null, ImageCollection collection = null)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| dataSet | DataSet | 用于模板表单生成的数据集集合 |
| layoutLines | String[] | 表示模板布局的已排序行数组 |
| settings | 全局页面设置 | 在每个模板表单生成中使用的页面设置 |
| collection | ImageCollection | 在每个模板表单生成中使用的图像集合 |

### 返回值

批量模板生成的结果

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 当处理具有空 Id 的 DataRecord 时 |

### 另请参阅

* class [BatchGenerationResult](../../batchgenerationresult)
* class [DataSet](../../dataset)
* class [GlobalPageSettings](../../../aspose.omr.generation/globalpagesettings)
* class [ImageCollection](../../../aspose.omr.api/imagecollection)
* class [BatchOmrEngine](../../batchomrengine)
* namespace [Aspose.OMR.BatchProcessings](../../batchomrengine)
* assembly [Aspose.OMR](../../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OMR.dll 生成 -->
