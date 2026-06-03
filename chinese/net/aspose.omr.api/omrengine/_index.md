---
title: "OmrEngine"
second_title: "Aspose.OMR 适用于 .NET API 参考"
description: "OMR 引擎。负责创建模板和图像处理类以及 GUI 组件。"
type: docs
weight: 20
url: /zh/net/aspose.omr.api/omrengine/
---
## OmrEngine class

OMR 引擎。负责创建模板和图像处理类以及 GUI 组件。

```csharp
public class OmrEngine
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [OmrEngine](omrengine)(PoolFactory) | 创建 OmrEngine 实例以实现内部存储的内存效率。复用同一工厂来创建多个 OmrEngine 实例以提升性能。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddPlugin](../../aspose.omr.api/omrengine/addplugin)(IPlugin) | 注册新插件 |
| [Generate](../../aspose.omr.api/omrengine/generate#generate_3)(string[], GlobalPageSettings, ImageCollection) | 创建一个 [`GenerationResult`](../../aspose.omr.generation/generationresult)，其中包含基于标记内容的模板 (.omr) 和模板图像。 |
| [Generate](../../aspose.omr.api/omrengine/generate#generate)(TemplateConfig, GlobalPageSettings, ImageCollection) | 创建一个 [`GenerationResult`](../../aspose.omr.generation/generationresult)，其中包含基于标记内容的模板 (.omr) 和模板图像。 |
| [Generate](../../aspose.omr.api/omrengine/generate#generate_1)(Stream, GlobalPageSettings, ImageCollection, Encoding) | 创建一个 [`GenerationResult`](../../aspose.omr.generation/generationresult)，其中包含基于标记流的模板 (.omr) 和模板图像。 |
| [Generate](../../aspose.omr.api/omrengine/generate#generate_2)(string, GlobalPageSettings, string[], Encoding) | 创建一个 [`GenerationResult`](../../aspose.omr.generation/generationresult)，其中包含基于指定路径存储的标记内容的模板 (.omr) 和模板图像。 |
| [GetCorrectionControl](../../aspose.omr.api/omrengine/getcorrectioncontrol)(TemplateProcessor) | 创建 [`CorrectionControl`](../../aspose.omr.correctionui/correctioncontrol) 实例，以通过 GUI 使用 OMR API。该实例接受 [`TemplateProcessor`](../templateprocessor) 作为参数，并且仅适用于使用指定模板创建的图像。 |
| [GetTemplateProcessor](../../aspose.omr.api/omrengine/gettemplateprocessor#gettemplateprocessor_1)(string, FormValidationLogic) | 创建 [`TemplateProcessor`](../templateprocessor) 实例，以便使用指定的模板进行操作。 |
| [GetTemplateProcessor](../../aspose.omr.api/omrengine/gettemplateprocessor#gettemplateprocessor)(MemoryStream, Encoding, FormValidationLogic) | 创建 [`TemplateProcessor`](../templateprocessor) 实例，以便使用指定的模板进行操作。 |

### 示例

```csharp
// 获取模板处理器
OmrEngine engine = new OmrEngine();
TemplateProcessor templateProcessor = engine.GetTemplateProcessor(templatePath);
```

```csharp
// 获取校正 GUI 控件
OmrEngine engine = new OmrEngine();
TemplateProcessor templateProcessor = engine.GetTemplateProcessor(templatePath);
CorrectionControl control = engine.GetCorrectionControl(templateProcessor);
```

```csharp
// 生成模板
OmrEngine engine = new OmrEngine();
GenerationResult result = engine.GenerateTemplate(markupPath);
if(result.ErrorCode == 0)
{
    result.Save(folderPath, templateName);
}
```

### 另请参阅

* namespace [Aspose.OMR.Api](../../aspose.omr.api)
* assembly [Aspose.OMR](../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OMR.dll 生成 -->
