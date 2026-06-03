---
title: "라이선스"
second_title: "Aspose.OMR for .NET API 레퍼런스"
description: "구성 요소에 라이선스를 부여하는 메서드를 제공합니다."
type: docs
weight: 20
url: /ko/net/aspose.omr/license/
---
## License class

구성 요소에 라이선스를 부여하는 메서드를 제공합니다.

```csharp
public class License
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [License](license)() | 이 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Embedded](../../aspose.omr/license/embedded) { get; set; } | 라이선스 번호가 포함된 리소스로 추가되었습니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [SetLicense](../../aspose.omr/license/setlicense#setlicense)(Stream) | 구성 요소에 라이선스를 적용합니다. |
| [SetLicense](../../aspose.omr/license/setlicense#setlicense_1)(string) | 구성 요소에 라이선스를 적용합니다. |

### 예제

이 예제에서는 구성 요소가 포함된 폴더, 호출 어셈블리가 포함된 폴더, 진입 어셈블리의 폴더에서 MyLicense.lic 라는 라이선스 파일을 찾은 다음 호출 어셈블리의 포함된 리소스에서 찾으려고 시도합니다.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### 참고

* namespace [Aspose.OMR](../../aspose.omr)
* assembly [Aspose.OMR](../../)

<!-- 편집 금지: xmldocmd에 의해 Aspose.OMR.dll용으로 생성됨 -->
