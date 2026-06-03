---
title: "GenerationResult"
second_title: "Aspose.OMR 适用于 .NET API 参考"
description: "模板生成的结果。包含模板图像以及描述图像上元素位置的模板 JSON。"
type: docs
weight: 810
url: /zh/net/aspose.omr.generation/generationresult/
---
## GenerationResult class

模板生成的结果。包含模板图像和模板（描述图像上元素位置的 json）。

```csharp
public class GenerationResult
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [ErrorCode](../../aspose.omr.generation/generationresult/errorcode) { get; set; } | 获取或设置错误代码。如果没有错误，则等于 0。 |
| [ErrorMessage](../../aspose.omr.generation/generationresult/errormessage) { get; set; } | 获取或设置描述错误的消息。如果没有错误，则为空。 |
| [Template](../../aspose.omr.generation/generationresult/template) { get; set; } | 获取或设置模板 JSON 字符串 |
| [TemplateImage](../../aspose.omr.generation/generationresult/templateimage) { get; set; } | 获取或设置生成的模板图像 |
| [Warnings](../../aspose.omr.generation/generationresult/warnings) { get; set; } | 获取或设置警告消息列表，描述生成过程中出现的非关键故障 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Save](../../aspose.omr.generation/generationresult/save)(string, string) | 将模板图像和模板保存为 .png 格式到指定文件夹 |
| [SaveAsInteractivePdf](../../aspose.omr.generation/generationresult/saveasinteractivepdf)(string, string) | 将表单保存为交互式 PDF，使用户能够直接在电脑或智能手机上填写字段并电子提交。 |
| [SaveAsPdf](../../aspose.omr.generation/generationresult/saveaspdf)(string, string) | 将模板图像保存为 .pdf 到指定文件夹。多页模板保存为单个包含多页的 .pdf 文件 |

## 字段

| 名称 | 描述 |
| --- | --- |
| [MultipageTemplateImages](../../aspose.omr.generation/generationresult/multipagetemplateimages) | 获取或设置多页模板生成的图像集合 |

### 另请参阅

* namespace [Aspose.OMR.Generation](../../aspose.omr.generation)
* assembly [Aspose.OMR](../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OMR.dll 生成 -->
