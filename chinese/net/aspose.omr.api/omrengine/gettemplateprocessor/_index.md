---
title: "GetTemplateProcessor"
second_title: "Aspose.OMR 适用于 .NET API 参考"
description: "创建 TemplateProcessoraspose.omr.api/templateprocessor 实例，以便使用指定的模板。"
type: docs
weight: 50
url: /zh/net/aspose.omr.api/omrengine/gettemplateprocessor/
---
## GetTemplateProcessor(MemoryStream, Encoding, FormValidationLogic) {#gettemplateprocessor}

创建 [`TemplateProcessor`](../../templateprocessor) 实例，以便使用指定的模板。

```csharp
public TemplateProcessor GetTemplateProcessor(MemoryStream templateContent, Encoding textEncoding, 
    FormValidationLogic logic = FormValidationLogic.Ignore)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| templateContent | MemoryStream | 包含模板文本内容的内存流 |
| textEncoding | 编码 | 模板内容编码 |
| logic | FormValidationLogic | 枚举，用于在模板验证规则之一被破坏时控制行为 |

### 返回值

该 [`TemplateProcessor`](../../templateprocessor) 实例

### 另请参阅

* class [TemplateProcessor](../../templateprocessor)
* enum [FormValidationLogic](../../../aspose.omr.recognition.enums/formvalidationlogic)
* class [OmrEngine](../../omrengine)
* namespace [Aspose.OMR.Api](../../omrengine)
* assembly [Aspose.OMR](../../../)

---

## GetTemplateProcessor(string, FormValidationLogic) {#gettemplateprocessor_1}

创建 [`TemplateProcessor`](../../templateprocessor) 实例，以便使用指定的模板。

```csharp
public TemplateProcessor GetTemplateProcessor(string templatePath, 
    FormValidationLogic logic = FormValidationLogic.Ignore)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| templatePath | String | OMR 模板文件的路径 |
| logic | FormValidationLogic | 枚举，用于在模板验证规则之一被破坏时控制行为 |

### 返回值

该 [`TemplateProcessor`](../../templateprocessor) 实例

### 异常

| 异常 | 条件 |
| --- | --- |
| FileNotFoundException | 如果 templatePath 未指向现有文件 |

### 另请参阅

* class [TemplateProcessor](../../templateprocessor)
* enum [FormValidationLogic](../../../aspose.omr.recognition.enums/formvalidationlogic)
* class [OmrEngine](../../omrengine)
* namespace [Aspose.OMR.Api](../../omrengine)
* assembly [Aspose.OMR](../../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OMR.dll 生成 -->
