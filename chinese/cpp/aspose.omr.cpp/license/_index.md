---
title: "许可证"
second_title: "Aspose.OMR 适用于 .NET 的 API 参考"
description: "提供用于授权组件的方法。"
type: docs
weight: 20
url: /zh/net/aspose.omr/license/
---
## License class

提供用于授权组件的方法。

```csharp
public class License
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [License](license)() | 初始化此类的新实例。 |

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

在此示例中，将尝试在包含组件的文件夹、包含调用程序集的文件夹、入口程序集的文件夹中查找名为 MyLicense.lic 的许可证文件，随后在调用程序集的嵌入资源中查找。

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### 另见

* namespace [Aspose.OMR](../../aspose.omr)
* assembly [Aspose.OMR](../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OMR.dll 生成 -->
