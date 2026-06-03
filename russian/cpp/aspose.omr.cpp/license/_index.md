---
title: "Лицензия"
second_title: "Справочник API Aspose.OMR для .NET"
description: "Предоставляет методы лицензирования компонента."
type: docs
weight: 20
url: /ru/net/aspose.omr/license/
---
## License class

Предоставляет методы лицензирования компонента.

```csharp
public class License
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [License](license)() | Инициализирует новый экземпляр этого класса. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Embedded](../../aspose.omr/license/embedded) { get; set; } | Номер лицензии был добавлен как встроенный ресурс. |

## Методы

| Имя | Описание |
| --- | --- |
| [SetLicense](../../aspose.omr/license/setlicense#setlicense)(Stream) | Лицензирует компонент. |
| [SetLicense](../../aspose.omr/license/setlicense#setlicense_1)(string) | Лицензирует компонент. |

### Примеры

В этом примере будет предпринята попытка найти файл лицензии с именем MyLicense.lic в папке, содержащей компонент, в папке, содержащей вызывающую сборку, в папке входной сборки, а затем во встроенных ресурсах вызывающей сборки.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### См. также

* namespace [Aspose.OMR](../../aspose.omr)
* assembly [Aspose.OMR](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для Aspose.OMR.dll -->
