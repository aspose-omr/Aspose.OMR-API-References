---
title: "生成"
second_title: "Aspose.OMR 适用于 .NET API 参考"
description: "创建一个 GenerationResultaspose.omr.generation/generationresult，其中包含基于标记流的 .omr 模板和模板图像。"
type: docs
weight: 30
url: /zh/net/aspose.omr.api/omrengine/generate/
---
## Generate(Stream, GlobalPageSettings, ImageCollection, Encoding) {#generate_1}

创建一个[`GenerationResult`](../../../aspose.omr.generation/generationresult)，其中包含基于标记流的模板 (.omr) 和模板图像。

```csharp
public GenerationResult Generate(Stream markupStream, GlobalPageSettings settings = null, 
    ImageCollection collection = null, Encoding encoding = null)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| markupStream | Stream | 可读取的流，包含用于模板配置（txt 或 json）的标记行 |
| settings | 全局页面设置 | 在所有页面的模板生成中使用的全局设置 |
| collection | ImageCollection | 可用于模板生成的图像集合。允许使用来自 MemoryStream 的图像，而不是文件系统中的图像。 |
| 编码 | 编码 | 标记行的编码，默认使用 UTF-8 |

### 返回值

生成结果

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | markupPath |
| [RuntimeExceptionOMR](../../../aspose.omr.exceptions/runtimeexceptionomr) | 模板生成 |

### 另请参阅

* class [GenerationResult](../../../aspose.omr.generation/generationresult)
* class [GlobalPageSettings](../../../aspose.omr.generation/globalpagesettings)
* class [ImageCollection](../../imagecollection)
* class [OmrEngine](../../omrengine)
* namespace [Aspose.OMR.Api](../../omrengine)
* assembly [Aspose.OMR](../../../)

---

## Generate(string, GlobalPageSettings, string[], Encoding) {#generate_2}

创建一个[`GenerationResult`](../../../aspose.omr.generation/generationresult)，其中包含基于指定路径存储的标记内容的模板 (.omr) 和模板图像。

```csharp
public GenerationResult Generate(string markupPath, GlobalPageSettings settings = null, 
    string[] imagesPaths = null, Encoding encoding = null)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| markupPath | String | 指向包含模板配置（txt 或 json）标记行的文件的路径 |
| settings | 全局页面设置 | 在所有页面的模板生成中使用的全局设置 |
| imagesPaths | String[] | 用于模板生成的图像路径 |
| 编码 | 编码 | 标记行的编码，默认使用 UTF-8 |

### 返回值

生成结果

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | markupPath |
| FileNotFoundException | markupPath |
| [RuntimeExceptionOMR](../../../aspose.omr.exceptions/runtimeexceptionomr) | 模板生成 |

### 另请参阅

* class [GenerationResult](../../../aspose.omr.generation/generationresult)
* class [GlobalPageSettings](../../../aspose.omr.generation/globalpagesettings)
* class [OmrEngine](../../omrengine)
* namespace [Aspose.OMR.Api](../../omrengine)
* assembly [Aspose.OMR](../../../)

---

## Generate(string[], GlobalPageSettings, ImageCollection) {#generate_3}

创建一个 [`GenerationResult`](../../../aspose.omr.generation/generationresult)，其中包含基于标记内容的模板（.omr）和模板图像

```csharp
public GenerationResult Generate(string[] markupContent, GlobalPageSettings settings = null, 
    ImageCollection collection = null)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| markupContent | String[] | 用于模板配置的标记行集合（txt 或 json） |
| settings | 全局页面设置 | 在所有页面的模板生成中使用的全局设置 |
| collection | ImageCollection | 可用于模板生成的图像集合。允许使用来自 MemoryStream 的图像，而不是文件系统中的图像。 |

### 返回值

生成结果

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException |  |
| [RuntimeExceptionOMR](../../../aspose.omr.exceptions/runtimeexceptionomr) | 模板生成 |

### 另请参阅

* class [GenerationResult](../../../aspose.omr.generation/generationresult)
* class [GlobalPageSettings](../../../aspose.omr.generation/globalpagesettings)
* class [ImageCollection](../../imagecollection)
* class [OmrEngine](../../omrengine)
* namespace [Aspose.OMR.Api](../../omrengine)
* assembly [Aspose.OMR](../../../)

---

## Generate(TemplateConfig, GlobalPageSettings, ImageCollection) {#generate}

创建一个 [`GenerationResult`](../../../aspose.omr.generation/generationresult)，其中包含基于标记内容的模板（.omr）和模板图像

```csharp
public GenerationResult Generate(TemplateConfig config, GlobalPageSettings settings = null, 
    ImageCollection collection = null)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| config | 模板配置 | 模板配置， |
| settings | 全局页面设置 | 在所有页面的模板生成中使用的全局设置 |
| collection | ImageCollection | 可用于模板生成的图像集合。允许使用来自 MemoryStream 的图像，而不是文件系统中的图像。 |

### 返回值

生成结果

### 异常

| 异常 | 条件 |
| --- | --- |
| [RuntimeExceptionOMR](../../../aspose.omr.exceptions/runtimeexceptionomr) | 模板生成 |

### 另请参阅

* class [GenerationResult](../../../aspose.omr.generation/generationresult)
* class [TemplateConfig](../../../aspose.omr.generation.config/templateconfig)
* class [GlobalPageSettings](../../../aspose.omr.generation/globalpagesettings)
* class [ImageCollection](../../imagecollection)
* class [OmrEngine](../../omrengine)
* namespace [Aspose.OMR.Api](../../omrengine)
* assembly [Aspose.OMR](../../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OMR.dll 生成 -->
