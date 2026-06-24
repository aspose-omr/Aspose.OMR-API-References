---
title: "许可证"
second_title: "Aspose.OMR 适用于 .NET 的 API 参考"
description: "初始化此类的新实例。"
type: docs
weight: 10
url: /zh/net/aspose.omr/license/license/
---
## License constructor

初始化此类的新实例。

```csharp
public License()
```

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

* class [License](../../license)
* namespace [Aspose.OMR](../../license)
* assembly [Aspose.OMR](../../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OMR.dll 生成 -->
