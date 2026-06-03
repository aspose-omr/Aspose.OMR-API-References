---
title: "TemplateProcessor"
second_title: "Aspose.OMR 适用于 .NET API 参考"
description: "用于处理模板和图像的类。该类的每个实例都与单个 OMR 模板一起工作。它能够识别构造函数中指定的模板图像。"
type: docs
weight: 50
url: /zh/net/aspose.omr.api/templateprocessor/
---
## TemplateProcessor class

用于处理模板和图像的类。该类的每个实例都与单个 OMR 模板一起工作。它能够识别构造函数中指定的模板图像。

```csharp
public class TemplateProcessor
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [Recalculate](../../aspose.omr.api/templateprocessor/recalculate)(RecognitionResult, int) | 使用微调参数更新识别结果。 |
| [Recognize](../../aspose.omr.api/templateprocessor/recognize#recognize)(Stream, int) | 从流中识别文件 |
| [Recognize](../../aspose.omr.api/templateprocessor/recognize#recognize_1)(Stream[], int) | 从流中识别文件集合 |
| [Recognize](../../aspose.omr.api/templateprocessor/recognize#recognize_2)(string, int) | 识别文件 |
| [Recognize](../../aspose.omr.api/templateprocessor/recognize#recognize_3)(string[], int) | 将多个文件识别为单个多页文件 |
| [RecognizeFolder](../../aspose.omr.api/templateprocessor/recognizefolder)(string, int) | 识别文件夹中的图像 |

## 字段

| 名称 | 描述 |
| --- | --- |
| [ApplyLightShadeProcessing](../../aspose.omr.api/templateprocessor/applylightshadeprocessing) | 可选的识别设置。设置为 true 时，所有 Recognize 方法将包含额外的预处理。此预处理有助于突出显示非常淡的标记。例如，淡淡的铅笔痕迹。 |

### 示例

```csharp
OmrEngine engine = new OmrEngine();
TemplateProcessor templateProcessor = engine.GetTemplateProcessor(templatePath);
RecognitionResult result = templateProcessor.Recognize(imagePath);
string csvResult = result.GetCsv();
```

### 另请参阅

* namespace [Aspose.OMR.Api](../../aspose.omr.api)
* assembly [Aspose.OMR](../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OMR.dll 生成 -->
