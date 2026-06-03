---
title: "Измеряемый"
second_title: "Справочник API Aspose.OMR для .NET"
description: "Предоставляет методы установки ключа с учётом использования."
type: docs
weight: 10
url: /ru/net/aspose.omr/metered/
---
## Metered class

Предоставляет методы установки ключа с учётом использования.

```csharp
public class Metered
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Metered](metered)() | Инициализирует новый экземпляр этого класса. |

## Методы

| Имя | Описание |
| --- | --- |
| [SetMeteredKey](../../aspose.omr/metered/setmeteredkey)(string, string) | Устанавливает публичный и приватный ключ с учётом использования |
| static [GetConsumptionCredit](../../aspose.omr/metered/getconsumptioncredit)() | Получает кредит потребления |
| static [GetConsumptionQuantity](../../aspose.omr/metered/getconsumptionquantity)() | Получает размер файла потребления |

### Примеры

В этом примере будет предпринята попытка установить публичный и приватный ключ с учётом использования

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

файл jar компонента:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### См. также

* namespace [Aspose.OMR](../../aspose.omr)
* assembly [Aspose.OMR](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для Aspose.OMR.dll -->
