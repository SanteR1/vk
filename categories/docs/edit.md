---
layout: default
title: Метод Docs.Edit
permalink: docs/edit/
comments: true
---
# Метод Docs.Edit
Редактирует документ пользователя или группы.

Страница документации ВКонтакте [docs.edit](https://vk.com/dev/docs.edit).
## Синтаксис
``` csharp
public bool Edit(long ownerId, long docId, string title, IEnumerable<string> tags)
```

## Параметры
+ **ownerId** - Идентификатор пользователя или сообщества, которому принадлежит документ. 
Обратите внимание, идентификатор сообщества в параметре owner_id необходимо указывать со знаком "-" — например, owner_id=-1 соответствует идентификатору сообщества ВКонтакте API (club1)  целое число, по умолчанию идентификатор текущего пользователя, обязательный параметр
+ **docId** - Идентификатор документа. положительное число, обязательный параметр
+ **title** - Название документа. строка, максимальная длина 128
+ **tags** - Метки для поиска. список слов, разделенных через запятую

## Результат
После успешного выполнения возвращает **true**.

## Пример
``` csharp
// Пример кода
```

## Версия Вконтакте API v.5.44
Дата обновления: 29.01.2016 12:07:22