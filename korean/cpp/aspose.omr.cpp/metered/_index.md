---
title: "계량"
second_title: "Aspose.OMR for .NET API 레퍼런스"
description: "계량 키를 설정하는 메서드를 제공합니다."
type: docs
weight: 10
url: /ko/net/aspose.omr/metered/
---
## Metered class

계량 키를 설정하는 메서드를 제공합니다.

```csharp
public class Metered
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Metered](metered)() | 이 클래스의 새 인스턴스를 초기화합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [SetMeteredKey](../../aspose.omr/metered/setmeteredkey)(string, string) | 계량 공개 및 개인 키를 설정합니다 |
| static [GetConsumptionCredit](../../aspose.omr/metered/getconsumptioncredit)() | 소비 크레딧을 가져옵니다 |
| static [GetConsumptionQuantity](../../aspose.omr/metered/getconsumptionquantity)() | 소비 파일 크기를 가져옵니다 |

### 예제

이 예제에서는 계량 공개 및 개인 키를 설정하려고 시도합니다.

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

구성 요소 jar 파일:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### 참고

* namespace [Aspose.OMR](../../aspose.omr)
* assembly [Aspose.OMR](../../)

<!-- 편집 금지: xmldocmd에 의해 Aspose.OMR.dll용으로 생성됨 -->
