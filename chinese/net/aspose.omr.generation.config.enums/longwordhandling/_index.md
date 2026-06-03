---
title: "LongWordHandling"
second_title: "Aspose.OMR 适用于 .NET API 参考"
description: "描述模板生成时遇到尺寸大于父容器的单词的行为。在这种情况下，单词无法在父容器内正确显示，也无法换行。"
type: docs
weight: 690
url: /zh/net/aspose.omr.generation.config.enums/longwordhandling/
---
## LongWordHandling enumeration

描述模板生成时遇到尺寸大于父容器的单词的行为。在这种情况下，单词无法在父容器内正确显示，也无法换行。

```csharp
public enum LongWordHandling
```

### Values

| 名称 | Value | 描述 |
| --- | --- | --- |
| undefined | `0` | 未设置 Settings。将使用默认值。 |
| DrawOver | `1` | 默认值。单词将按原样显示，超出父元素边界。 |
| ThrowException | `2` | 当单词被测量为超出父元素时 - 将抛出异常。 |
| Hyphenation | `3` | 按字母拆分长单词，并在新行显示其余字母。 |

### 另请参阅

* namespace [Aspose.OMR.Generation.Config.Enums](../../aspose.omr.generation.config.enums)
* assembly [Aspose.OMR](../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OMR.dll 生成 -->
