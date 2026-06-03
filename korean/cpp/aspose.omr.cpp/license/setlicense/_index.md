---
title: "SetLicense"
second_title: "Aspose.OMR for .NET API 레퍼런스"
description: "구성 요소에 라이선스를 적용합니다."
type: docs
weight: 30
url: /ko/net/aspose.omr/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

구성 요소에 라이선스를 적용합니다.

```csharp
public void SetLicense(string licenseName)
```

### 비고

다음 위치에서 라이선스를 찾으려고 시도합니다:

1. 명시적 경로.

2. Aspose 구성 요소 어셈블리가 포함된 폴더.

3. 클라이언트의 호출 어셈블리가 포함된 폴더.

4. 항목(시작) 어셈블리를 포함하는 폴더.

5. 클라이언트의 호출 어셈블리에 포함된 임베디드 리소스.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. 명시적 경로.

2. 클라이언트의 호출 어셈블리에 포함된 임베디드 리소스.

### 예제

이 예제에서는 구성 요소가 포함된 폴더, 호출 어셈블리가 포함된 폴더, 진입 어셈블리의 폴더에서 MyLicense.lic 라는 라이선스 파일을 찾은 다음 호출 어셈블리의 포함된 리소스에서 찾으려고 시도합니다.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
```

전체 파일 이름이거나 짧은 파일 이름, 혹은 임베디드 리소스 이름일 수 있습니다. 빈 문자열을 사용하면 평가 모드로 전환됩니다.

### 참고

* class [License](../../license)
* namespace [Aspose.OMR](../../license)
* assembly [Aspose.OMR](../../../)

---

## SetLicense(Stream) {#setlicense}

구성 요소에 라이선스를 적용합니다.

```csharp
public void SetLicense(Stream stream)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | Stream | 라이선스를 포함하는 스트림. |

### 비고

스트림에서 라이선스를 로드하려면 이 메서드를 사용하십시오.

### 예제

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

### 참고

* class [License](../../license)
* namespace [Aspose.OMR](../../license)
* assembly [Aspose.OMR](../../../)

<!-- 편집 금지: xmldocmd에 의해 Aspose.OMR.dll용으로 생성됨 -->
