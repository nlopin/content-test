🛠 Если нужно сохранить в переменную одно, либо другое значение, в зависимости от условия, то можно это сделать двумя путями.

Простой:

```js
let value = 1 // значение по умолчанию
if (day === 'Tuesday') {
  value = 50
}
```

С использованием [тернарного оператора](/js/ternary-operator/) (короткая запись `if..else`):

```js
let value = day === 'Tuesday' ? 50 : 1 // во вторник значение 50, во всех остальных случаях 1
```

Тернарный оператор стоит использовать только если выражение короткое. В противном случае такой код будет плохо читаться.
