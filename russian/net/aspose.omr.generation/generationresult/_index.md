---
title: GenerationResult
second_title: Справочник по Aspose.OMR для .NET API
description: Результат генерации шаблона. Содержит изображение шаблона и шаблон json описывающий расположение элементов на изображении.
type: docs
weight: 560
url: /ru/net/aspose.omr.generation/generationresult/
---
## GenerationResult class

Результат генерации шаблона. Содержит изображение шаблона и шаблон (json, описывающий расположение элементов на изображении).

```csharp
public class GenerationResult
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [ErrorCode](../../aspose.omr.generation/generationresult/errorcode) { get; set; } | Получает или задает код ошибки. Равно 0, если ошибок не было. |
| [ErrorMessage](../../aspose.omr.generation/generationresult/errormessage) { get; set; } | Получает или задает сообщение, описывающее ошибку. Пусто, если ошибок не было. |
| [Template](../../aspose.omr.generation/generationresult/template) { get; set; } | Получает или задает строку шаблона JSON |
| [TemplateImage](../../aspose.omr.generation/generationresult/templateimage) { get; set; } | Получает или задает сгенерированное изображение шаблона |
| [Warnings](../../aspose.omr.generation/generationresult/warnings) { get; set; } | Получает или задает список предупреждающих сообщений, описывающих некритические ошибки, возникшие при генерации |

## Методы

| Имя | Описание |
| --- | --- |
| [Save](../../aspose.omr.generation/generationresult/save)(string, string) | Сохранить шаблонные изображения и шаблон в указанную папку |
| [SaveAsPdf](../../aspose.omr.generation/generationresult/saveaspdf)(string, string) | Сохранить изображения шаблона и шаблон в указанную папку Изображение шаблона сохранено в формате pdf |

## Поля

| Имя | Описание |
| --- | --- |
| [MultipageTemplateImages](../../aspose.omr.generation/generationresult/multipagetemplateimages) | Получает или задает коллекцию сгенерированных изображений для многостраничного шаблона |

### Смотрите также

* пространство имен [Aspose.OMR.Generation](../../aspose.omr.generation)
* сборка [Aspose.OMR](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.OMR.dll -->