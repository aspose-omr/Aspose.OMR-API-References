---
title: "ContainerConfig"
second_title: "Aspose.OMR 适用于 .NET API 参考"
description: "表示 Container 元素。"
type: docs
weight: 420
url: /zh/net/aspose.omr.generation.config.elements.parents/containerconfig/
---
## ContainerConfig class

表示 Container 元素。

```csharp
public class ContainerConfig : ParentConfig
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ContainerConfig](containerconfig)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BlockBottomMargin](../../aspose.omr.generation.config.elements.parents/containerconfig/blockbottommargin) { get; set; } | 块下方要放置的像素数量。 |
| [BlockRightMargin](../../aspose.omr.generation.config.elements.parents/containerconfig/blockrightmargin) { get; set; } | 块右侧之间要放置的像素数量 |
| [BlockTopPadding](../../aspose.omr.generation.config.elements.parents/containerconfig/blocktoppadding) { get; set; } | 块顶部边界之后要放置的像素数量。 |
| override [Children](../../aspose.omr.generation.config.elements.parents/containerconfig/children) { get; set; } | 子 OMR 元素。大多数情况下位于父元素内部或下方。 |
| [ColumnsCount](../../aspose.omr.generation.config.elements.parents/containerconfig/columnscount) { get; set; } | 容器内部的列数。均匀划分列。已废弃的 [`Proportions`](./proportions) 版本 |
| [ContainerType](../../aspose.omr.generation.config.elements.parents/containerconfig/containertype) { get; set; } | 容器的类型 |
| override [Name](../../aspose.omr.generation.config.elements.parents/containerconfig/name) { get; set; } | 容器元素的名称 |
| [Proportions](../../aspose.omr.generation.config.elements.parents/containerconfig/proportions) { get; set; } | 在内部按自定义比例划分每列，更新版的 [`ColumnsCount`](./columnscount) |
| [SyncBlockHeight](../../aspose.omr.generation.config.elements.parents/containerconfig/syncblockheight) { get; set; } | 设置为 true 时，同步子 [`BlockConfig`](../blockconfig) 的所有高度。底部边框对齐到最长的。 |
| override [Type](../../aspose.omr.generation.config.elements.parents/containerconfig/type) { get; set; } | OMR 元素的类型。JSON 序列化所需的字段。 |

### 另请参阅

* class [ParentConfig](../../aspose.omr.generation.config/parentconfig)
* namespace [Aspose.OMR.Generation.Config.Elements.Parents](../../aspose.omr.generation.config.elements.parents)
* assembly [Aspose.OMR](../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OMR.dll 生成 -->
