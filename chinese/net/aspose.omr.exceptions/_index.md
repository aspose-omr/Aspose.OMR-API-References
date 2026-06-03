---
title: "Aspose.OMR.Exceptions"
second_title: "Aspose.OMR 适用于 .NET API 参考"
description: 
type: docs
weight: 70
url: /zh/net/aspose.omr.exceptions/
---


## 类

| 类 | 描述 |
| --- | --- |
| [ChildOverflowException](./childoverflowexception) | 在模板生成中使用的异常。当 [`LongWordHandling`](../aspose.omr.generation/globalpagesettings/longwordhandling) 设置为 ThrowException 且子元素超出父（容器）元素边界时触发； |
| [InvalidConfigurationException](./invalidconfigurationexception) | 在 OMR 输入验证期间出现了描述的问题。 |
| [MultiselectException](./multiselectexception) | 在模板识别中使用的异常。在调用 [`Recognize`](../aspose.omr.api/templateprocessor/recognize) 时抛出。由于每个问题有多个答案且元素的 multi-select 设置为 true 而触发。可以通过 [`Multiselect`](../aspose.omr.generation.config.elements/choiceboxconfig/multiselect) 进行控制。默认设置在 [`GetTemplateProcessor`](../aspose.omr.api/omrengine/gettemplateprocessor) 中使用异常进行设置。 |
| [OMRException](./omrexception) | 所有 OMR 异常的基类。封装所有应用程序逻辑违规。 |
| [RuntimeExceptionOMR](./runtimeexceptionomr) | OMR 逻辑内部未定义的通用异常 |

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OMR.dll 生成 -->
