---
title: "`<optgroup>`"
description: "Группирует опции внутри раскрывающегося списка."
authors:
  - granondo
keywords:
  - группировка опций
related:
  - html/select
  - html/form
  - js/events
tags:
  - doka
---

## Кратко

Тег `<optgroup>` позволяет группировать опции внутри элемента [`<select>`](/html/select/). Внутри тега `<optgroup>` стандартно используется один или несколько тегов [`<option>`](/html/option/).


## Как пишется

Нельзя вкладывать один `<optgroup>` в другой.

Возможные атрибуты:

- `disabled` — находящиеся внутри группы опции станут недоступны для выбора.

```html
<select>
  <optgroup label="Необычные цветы" disabled>
    <option>Ангулоя одноцветковая</option>
    <option>Обезьяний дракула</option>
    <option>Пассифлора инкарнатная</option>
  </optgroup>
</select>
```

- `label` — обязательный атрибут. Имя группы будет отображено в выпадающем списке. Теоретически мы можем оставить атрибут пустым или не использовать его вообще, но в таком случае над списком будет пустое пространство.

Кроме того, можно применить любые [глобальные атрибуты](/html/global-attrs/).
