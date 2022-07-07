---
title: License
second_title: Aspose.OMR for .NET API 参考
description: 提供许可组件的方法
type: docs
weight: 610
url: /zh/net/aspose.omr/license/
---
## License class

提供许可组件的方法。

```csharp
public class License
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [License](license)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Embedded](../../aspose.omr/license/embedded) { get; set; } | 许可证号已添加为嵌入式资源。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [SetLicense](../../aspose.omr/license/setlicense#setlicense)(Stream) | 许可组件。 |
| [SetLicense](../../aspose.omr/license/setlicense#setlicense_1)(string) | 许可组件。 |

### 例子

在本例中，将尝试查找名为 MyLicense.lic 的许可证文件在包含 组件的文件夹中，在包含调用程序集的文件夹中， 在入口程序集的文件夹中，然后在的嵌入资源中调用程序集。

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### 也可以看看

* 命名空间 [Aspose.OMR](../../aspose.omr)
* 部件 [Aspose.OMR](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.OMR.dll -->