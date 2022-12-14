🛠 Всегда используйте альтернативы циклу `while`, которые лучше подходят под задачу. Например, у массивов есть много удобных методов: [`forEach()`](/js/array-foreach/), [`filter()`](/js/array-filter/), [`map()`](/js/array-map/). Они лучше читаются и содержат меньше кода.

🛠 Следите, чтобы условие менялось с каждым выполнением тела цикла. Если этого не происходит, то, скорее всего, цикл будет бесконечным.

🛠 `while` более гибкий цикл чем [`for`](/js/for/), но при его написании легко совершить ошибку. Момент инициализации и изменения переменных в `for` (операция инициализации и шага) заранее определены. Их можно нарушить, но это не будет хорошо читаться. `while` предоставляет полную свободу организовывать цикл как угодно, это полностью ручное управление. Можно легко забыть написать что-либо — чаще всего забывают менять переменную из условия в теле цикла.
