---
description: Тег bdo (от англ. bidirectional override - элемент двунаправленного переопределения) устанавливает направление вывода текста и преимущественно предназначен для использования с языками, где чтение происходит справа налево
---

# &lt;bdo&gt;

Тег **`<bdo>`** _(от англ. **b**i**d**irectional **o**verride - элемент двунаправленного переопределения)_ устанавливает направление вывода текста и преимущественно предназначен для использования с языками, где чтение происходит справа налево.

Например, к ним относится иврит.

## Синтаксис

```html
<bdo>Текст</bdo>
```

Закрывающий тег обязателен.

## Атрибуты

Для этого элемента доступны [универсальные атрибуты](uni-attr.md).

## Спецификации

- [WHATWG HTML Living Standard](https://html.spec.whatwg.org/multipage/semantics.html#the-bdo-element)
- [HTML5](http://www.w3.org/TR/html5/textlevel-semantics.html#the-bdo-element)
- [HTML 4.01 Specification](http://www.w3.org/TR/html401/dirlang.html#h-8.2.4)

## Описание и примеры

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>BDO</title>
  </head>
  <body>
    <p><bdo dir="rtl">А роза упала на лапу Азора</bdo></p>
  </body>
</html>
```

## Ссылки

- Тег [`<bdo>`](https://developer.mozilla.org/ru/docs/Web/HTML/Element/bdo) <sup><small>MDN (рус.)</small></sup>
