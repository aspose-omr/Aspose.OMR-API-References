---
title: "FormValidationLogic"
second_title: "Aspose.OMR 适用于 .NET API 参考"
description: "在识别过程中控制非标准错误情况行为的模式。"
type: docs
weight: 1050
url: /zh/net/aspose.omr.recognition.enums/formvalidationlogic/
---
## FormValidationLogic enumeration

在识别过程中控制非标准（错误）情况行为的模式。

```csharp
public enum FormValidationLogic
```

### Values

| 名称 | Value | 描述 |
| --- | --- | --- |
| undefined | `0` | 未指定逻辑 - 将使用默认值 (Ignore=1) |
| Ignore | `1` | 识别引擎将忽略所有由模板 markdown 设置的验证逻辑错误。每个问题标记了多个答案，尽管 multiselect 被设置为 false。在这种情况下，所有标记的值将原样返回。 |
| Exception | `2` | 识别引擎将抛出从 [`OMRException`](../../aspose.omr.exceptions/omrexception) 派生的异常。异常类型取决于违规规则。每个问题标记了多个答案，尽管 multiselect 被设置为 false。将抛出异常 [`MultiselectException`](../../aspose.omr.exceptions/multiselectexception)。 |

### 另请参阅

* namespace [Aspose.OMR.Recognition.Enums](../../aspose.omr.recognition.enums)
* assembly [Aspose.OMR](../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OMR.dll 生成 -->
