---
description: Тег s (от англ. strikethrough — зачеркнутый) используется для содержимого, которое уже не является точным или актуальным
---

# &lt;s&gt;

Тег **`<s>`** _(от англ. **s**trikethrough — зачеркнутый)_ используется для содержимого, которое уже не является точным или актуальным.

Браузеры отображают такой текст как перечёркнутый. Элемент `<s>` не должен применяться для удалённого текста, для этой цели есть элемент [`<del>`](del.md).

## Синтаксис

```html
<s>Текст</s>
```

Закрывающий тег обязателен.

## Атрибуты

Нет.

## Спецификации

- [WHATWG HTML Living Standard](https://html.spec.whatwg.org/multipage/semantics.html#the-s-element)
- [HTML 5](http://www.w3.org/TR/html5/textlevel-semantics.html#the-s-element)

## Описание и примеры

```html
<!DOCTYPE html>
<html>
  <head>
    <title>S</title>
    <meta charset="utf-8" />
  </head>
  <body>
    <p><b>Список должников</b></p>
    <p><s>Чебурашка</s></p>
    <p><s>Крокодил Гена</s></p>
    <p>Шапокляк</p>
  </body>
</html>
```

## Ссылки

- Тег [`<s>`](https://developer.mozilla.org/ru/docs/Web/HTML/Element/s) <sup><small>MDN (рус.)</small></sup>
