---
title: "License"
second_title: "Aspose.OMR 适用于 .NET API 参考"
description: "提供对组件进行授权的方法。"
type: docs
weight: 1010
url: /zh/net/aspose.omr/license/
---
## License class

提供对组件进行授权的方法。

```csharp
public class License
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [License](license)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Embedded](../../aspose.omr/license/embedded) { get; set; } | 许可证号已作为嵌入资源添加。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [SetLicense](../../aspose.omr/license/setlicense#setlicense)(Stream) | 为组件授权。 |
| [SetLicense](../../aspose.omr/license/setlicense#setlicense_1)(string) | 为组件授权。 |

### 示例

在本例中，将尝试在以下位置查找名为 MyLicense.lic 的许可证文件：包含组件的文件夹、包含调用程序集的文件夹、入口程序集所在的文件夹，然后是调用程序集的嵌入资源。

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### 另请参阅

* namespace [Aspose.OMR](../../aspose.omr)
* assembly [Aspose.OMR](../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OMR.dll 生成 -->
