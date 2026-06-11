### Содержание

| №   | Вопрос                                                                                                                                                                                                       |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 1   |[В чем разница между `null` и `undefined`?](#в-чем-разница-между-null-и-undefined)                                                                                                                            |
| 2   |[Является ли использование унарного плюса (оператор "+") самым быстрым способом преобразования строки в число?](#является-ли-использование-унарного-плюса-оператор--самым-быстрым-способом-преобразования-строки-в-число) |
| 3   | [Что такое DOM?](#что-такое-dom) |
| 4   | [Что такое распространение события (Event Propagation)?](#что-такое-распространение-события-event-propagation) |
| 5   | [Что такое всплытие события (Event Bubbling)?](#что-такое-всплытие-события-event-bubbling) |
| 6   | [Что такое погружение события (Event Capturing)?](#что-такое-погружение-события-event-capturing) |
| 7   | [В чем разница между методами event.preventDefault() и event.stopPropagation()?](#в-чем-разница-между-методами-eventpreventdefault-и-eventstoppropagation) |
| 8   | [Сравните методы объекта event: stopPropagation() и stopImmediatePropagation().](#сравните-методы-объекта-event-stoppropagation-и-stopimmediatepropagation) |
| 9   | [Как узнать об использовании метода event.preventDefault()?](#как-узнать-об-использовании-метода-eventpreventdefault) |
| 10  | [В чем разница между операторами == и ===?](#в-чем-разница-между-операторами--и-) |
| 11  | [Почему результатом сравнения двух похожих объектов является false?](#почему-результатом-сравнения-двух-похожих-объектов-является-false) |
| 12  | [Как записать несколько выражений в одну строку?](#как-записать-несколько-выражений-в-одну-строку) |
| 13  | [Что такое поднятие (Hoisting)?](#что-такое-поднятие-hoisting) |
| 14  | [Что такое область видимости (Scope)?](#что-такое-область-видимости-scope) |
| 15  | [Что такое замыкание (Closures)?](#что-такое-замыкание-closures) |
| 16  | [Для чего предназначены методы setTimeout и setInterval?](#для-чего-предназначены-методы-settimeout-и-setinterval) |
| 17  | [Расскажите назначение и принципы работы с коллекциями Map и Set.](#расскажите-назначение-и-принципы-работы-с-коллекциями-map-и-set) |
| 18  | [Расскажите о стрелочных функциях (Arrow Functions). В чем заключаются отличия стрелочных функций от обычных?](#расскажите-о-стрелочных-функциях-arrow-function-в-чем-заключаются-отличия-стрелочных-функций-от-обычных) |
| 19  | [Для чего используется директива "use strict"?](#для-чего-используется-директива-use-strict) |
| 20  | [Какое значение имеет this?](#какое-значение-имеет-this) |
| 21  | [Что такое прототип объекта?](#что-такое-прототип-объекта) |
| 22  | [Для чего используется метод apply()?](#для-чего-используется-метод-apply) |
| 23  | [Для чего используется метод call()?](#для-чего-используется-метод-call) |
| 24  | [В чем разница между методами call() и apply()?](#в-чем-разница-между-методами-call-и-apply) |
| 25  | [Для чего используется метод Function.prototype.bind()?](#для-чего-используется-метод-functionprototypebind) |
| 26  | [Что делает метод map()?](#метод-map) |
| 27  | [Что делает метод filter()?](#метод-filter) |
| 28  | [Что делает метод reduce()?](#метод-reduce) |
| 29  | [Что такое объект arguments?](#что-такое-объект-arguments) |
| 30  | [Что такое ECMAScript?](#что-такое-ecmascript) |
| 31  | [Что нового привнес в JS стандарт ES6 (ECMAScript 2015)?](#что-нового-привнес-в-js-стандарт-es6-ecmascript-2015) |
| 32  | [В чем разница между ключевыми словами var, let и const?](#в-чем-разница-между-ключевыми-словами-var-let-и-const) |
| 33  | [Что такое классы (Classes)?](#что-такое-классы-classes) |
| 34  | [Что такое деструктуризация объекта (Object Destructuring)?](#что-такое-деструктуризация-объекта-object-destructuring) |
| 35  | [Что такое функция обратного вызова (Callback Function)?](#что-такое-функция-обратного-вызова-callback-function) |
| 36  | [Что такое промисы (Promises)?](#что-такое-промисы-promises) |
| 37  | [Что такое async/await?](#что-такое-asyncawait) |
| 38  | [В чем разница между spread-оператором и rest-оператором?](#в-чем-разница-между-spread-оператором-и-rest-оператором) |
| 39  | [Что такое параметры по умолчанию (Default Parameters)?](#что-такое-параметры-по-умолчанию-default-parameters) |
| 40  | [Что такое объектная обертка (Wrapper Objects)?](#что-такое-объектная-обертка-wrapper-objects) |
| 41  | [В чем разница между явным и неявным преобразованием типов (Implicit и Explicit Coercion)?](#в-чем-разница-между-явным-и-неявным-преобразованием-типов-implicit-и-explicit-coercion) |
| 42  | [Что такое NaN? Как проверить, является ли значение NaN?](#что-такое-nan-как-проверить-является-ли-значение-nan) |
| 43  | [Как в JavaScript создать объект?](#как-в-js-создать-объект) |
| 44  | [Какие приемы работы с асинхронным кодом в JavaScript вы знаете?](#какие-приемы-работы-с-асинхронным-кодом-в-javascript-вы-знаете) |
| 45  | [Что такое мемоизация (Memoization)?](#что-такое-мемоизация-memoization) |
| 46  | [Почему typeof null возвращает object? Как проверить, является ли значение null?](#почему-typeof-null-возвращает-object-как-проверить-является-ли-значение-null) |
| 47  | [Для чего используется ключевое слово new?](#для-чего-используется-ключевое-слово-new) |
| 48  | [Что такое Event Loop и принцип его работы?](#что-такое-event-loop-и-принцип-его-работы) |
| 49  | [Что такое микро- и макротаски?](#что-такое-микро--и-макротаски) |
| 50  | [Чем отличается prototype от __proto__?](#чем-отличаются-prototype-и-__proto__) |
| 51  | [В каких случаях используются анонимные функции?](#в-каких-случаях-используются-анонимные-функции) |
| 52  | [Что такое функция высшего порядка (Higher-Order Function)?](#что-такое-функция-высшего-порядка-higher-order-function) |
| 53  | [Что такое WebGL?](#что-такое-webgl) |
| 54  | [Как работает boxing / unboxing в JavaScript?](#как-работает-boxing--unboxing-в-javascript) |
| 55  | [Опишите назначение и принципы работы с коллекциями WeakMap и WeakSet. Чем они отличаются от Map и Set?](#опишите-назначение-и-принципы-работы-с-коллекциями-weakmap-и-weakset-чем-они-отличаются-от-map-и-set) |
| 56  | [Расскажите о генераторах и итераторах.](#расскажите-о-генераторах-и-итераторах) |
| 57  | [Что такое чейнинг функций?](#что-такое-чейнинг-функций-function-chaining) |
| 58  | [Какие есть подходы оптимизации производительности веб-страницы?](#какие-есть-подходы-оптимизации-производительности-веб-страницы) |

### В чем разница между `null` и `undefined`?

`null` и `undefined` представляют отсутствие значения, однако используются в разных ситуациях.

#### `undefined`

Значение `undefined` автоматически присваивается JavaScript в следующих случаях:

* Переменная объявлена, но не инициализирована.
* Функция не возвращает значение явно.
* Обращение к несуществующему свойству объекта.
* Отсутствует переданный аргумент функции.

Примеры:

```javascript
let x;
console.log(x); // undefined

function test() {}
console.log(test()); // undefined

const obj = {};
console.log(obj.name); // undefined
```

#### `null`

`null` — это специальное значение, которое разработчик присваивает явно, чтобы показать отсутствие объекта или значения.

Пример:

```javascript
let user = null;
console.log(user); // null
```

#### Основные различия

| null                                            | undefined                                |
| ----------------------------------------------- | ---------------------------------------- |
| Присваивается явно разработчиком                | Присваивается автоматически JavaScript   |
| Тип данных — object (историческая ошибка языка) | Тип данных — undefined                   |
| Означает намеренное отсутствие значения         | Означает, что значение еще не определено |

Проверка:

```javascript
console.log(typeof null);      // object
console.log(typeof undefined); // undefined

console.log(null == undefined);  // true
console.log(null === undefined); // false
```

---

### Является ли использование унарного плюса (оператор "+") самым быстрым способом преобразования строки в число?

Унарный плюс (`+`) является одним из самых коротких и обычно очень быстрых способов преобразования строки в число.

Пример:

```javascript
const str = "123";

const num = +str;
console.log(num); // 123
```

Другие способы преобразования:

```javascript
Number("123");
parseInt("123", 10);
parseFloat("123.45");
```

Сравнение:

| Способ          | Назначение                              |
| --------------- | --------------------------------------- |
| `+value`        | Быстрое преобразование в число          |
| `Number(value)` | Явное преобразование                    |
| `parseInt()`    | Преобразование целого числа             |
| `parseFloat()`  | Преобразование числа с плавающей точкой |

На современных JavaScript-движках разница в производительности между `+value` и `Number(value)` минимальна и практически незаметна в реальных приложениях.

Поэтому при выборе следует руководствоваться читаемостью кода, а не микрооптимизациями.

Пример:

```javascript
+"42";          // 42
Number("42");   // 42

+"42px";        // NaN
parseInt("42px", 10); // 42
```

---

### Что такое DOM?

DOM (Document Object Model) — это объектное представление HTML-документа в виде дерева объектов, с которым JavaScript может взаимодействовать.

Браузер преобразует HTML в дерево DOM-узлов:

```html
<html>
  <body>
    <h1>Hello</h1>
  </body>
</html>
```

Представление в виде дерева:

```text
Document
 └── html
      └── body
           └── h1
                └── "Hello"
```

Через DOM можно:

* Читать содержимое страницы.
* Изменять элементы.
* Добавлять новые элементы.
* Удалять элементы.
* Навешивать обработчики событий.

Пример:

```javascript
const title = document.querySelector("h1");

title.textContent = "New Title";
```

Создание нового элемента:

```javascript
const div = document.createElement("div");
div.textContent = "Hello";

document.body.appendChild(div);
```

DOM является связующим звеном между HTML-страницей и JavaScript.

---

### Что такое распространение события (Event Propagation)?

Распространение события (Event Propagation) — это механизм, определяющий, как событие проходит через DOM-дерево после возникновения.

Например:

```html
<div id="parent">
  <button id="child">Click</button>
</div>
```

При клике на кнопку событие проходит через несколько фаз.

#### Фазы распространения события

1. Capturing Phase (погружение).
2. Target Phase (достижение целевого элемента).
3. Bubbling Phase (всплытие).

Схема:

```text
document
  ↓
html
  ↓
body
  ↓
parent
  ↓
button (target)
  ↑
parent
  ↑
body
  ↑
html
  ↑
document
```

По умолчанию большинство обработчиков работают на этапе всплытия.

Пример:

```javascript
element.addEventListener("click", handler);
```

Для обработки на этапе погружения используется третий параметр:

```javascript
element.addEventListener("click", handler, true);
```

---

### Что такое всплытие события (Event Bubbling)?

Всплытие события (Event Bubbling) — это фаза распространения события, при которой событие поднимается от целевого элемента вверх по DOM-дереву к его родителям.

Пример:

```html
<div id="parent">
  <button id="child">Click</button>
</div>
```

```javascript
document.getElementById("parent").addEventListener("click", () => {
  console.log("parent");
});

document.getElementById("child").addEventListener("click", () => {
  console.log("child");
});
```

При клике на кнопку вывод будет:

```text
child
parent
```

Сначала выполняется обработчик целевого элемента, затем обработчики его родителей.

#### Остановка всплытия

Для остановки всплытия используется метод:

```javascript
event.stopPropagation();
```

Пример:

```javascript
document.getElementById("child").addEventListener("click", (event) => {
  event.stopPropagation();
  console.log("child");
});
```

Теперь при клике будет выведено:

```text
child
```

Всплытие активно используется для делегирования событий.

Пример делегирования:

```javascript
document.getElementById("list").addEventListener("click", (event) => {
  if (event.target.tagName === "LI") {
    console.log(event.target.textContent);
  }
});
```

Так можно обрабатывать события множества дочерних элементов через один обработчик на родительском элементе, что улучшает производительность и упрощает код.

---

### Что такое погружение события (Event Capturing)?

Погружение события (Event Capturing, Event Trickling) — это первая фаза распространения события, при которой событие проходит от корня DOM-дерева к целевому элементу.

Рассмотрим структуру:

```html
<div id="parent">
  <button id="child">Click</button>
</div>
```

Путь события выглядит следующим образом:

```text
document
  ↓
html
  ↓
body
  ↓
parent
  ↓
child (target)
```

По умолчанию обработчики событий работают на этапе всплытия (Bubbling).

Чтобы обработчик срабатывал на этапе погружения, необходимо передать третий аргумент `true`:

```javascript
document.getElementById("parent").addEventListener(
  "click",
  () => {
    console.log("parent");
  },
  true
);
```

Пример:

```javascript
document.getElementById("parent").addEventListener(
  "click",
  () => {
    console.log("parent");
  },
  true
);

document.getElementById("child").addEventListener(
  "click",
  () => {
    console.log("child");
  },
  true
);
```

При клике на кнопку вывод будет:

```text
parent
child
```

#### Фазы распространения события

1. **Capturing Phase** — событие движется сверху вниз.
2. **Target Phase** — событие достигает целевого элемента.
3. **Bubbling Phase** — событие поднимается снизу вверх.

Capturing используется значительно реже, чем Bubbling, но может быть полезен для глобального перехвата событий до их обработки дочерними элементами.

---

### В чем разница между методами `event.preventDefault()` и `event.stopPropagation()`?

Эти методы решают разные задачи.

#### `event.preventDefault()`

Отменяет стандартное поведение браузера для события.

Примеры стандартного поведения:

* Переход по ссылке.
* Отправка формы.
* Открытие контекстного меню.
* Перетаскивание элементов.

Пример:

```html
<a href="https://google.com">Google</a>
```

```javascript
document.querySelector("a").addEventListener("click", (event) => {
  event.preventDefault();
});
```

После вызова метода переход по ссылке не произойдет.

---

#### `event.stopPropagation()`

Останавливает дальнейшее распространение события по DOM-дереву.

Пример:

```javascript
child.addEventListener("click", (event) => {
  event.stopPropagation();
});

parent.addEventListener("click", () => {
  console.log("parent");
});
```

При клике на дочерний элемент обработчик родителя вызван не будет.

---

#### Сравнение

| Метод               | Назначение                                   |
| ------------------- | -------------------------------------------- |
| `preventDefault()`  | Отменяет стандартное действие браузера       |
| `stopPropagation()` | Останавливает распространение события по DOM |

Часто используются вместе:

```javascript
form.addEventListener("submit", (event) => {
  event.preventDefault();
  event.stopPropagation();
});
```

---

### Сравните методы объекта event `stopPropagation()` и `stopImmediatePropagation()`

Оба метода останавливают распространение события, но работают по-разному.

#### `stopPropagation()`

Останавливает дальнейшее распространение события вверх или вниз по DOM-дереву.

Однако остальные обработчики текущего элемента продолжат выполняться.

Пример:

```javascript
button.addEventListener("click", () => {
  console.log("first");
});

button.addEventListener("click", (event) => {
  event.stopPropagation();
  console.log("second");
});

button.addEventListener("click", () => {
  console.log("third");
});
```

Результат:

```text
first
second
third
```

Событие не поднимется к родителям, но обработчики кнопки продолжат выполняться.

---

#### `stopImmediatePropagation()`

Останавливает:

* дальнейшее распространение события;
* выполнение остальных обработчиков текущего элемента.

Пример:

```javascript
button.addEventListener("click", () => {
  console.log("first");
});

button.addEventListener("click", (event) => {
  event.stopImmediatePropagation();
  console.log("second");
});

button.addEventListener("click", () => {
  console.log("third");
});
```

Результат:

```text
first
second
```

Обработчик `third` уже не выполнится.

---

#### Сравнение

| Метод                        | Останавливает всплытие | Останавливает остальные обработчики текущего элемента |
| ---------------------------- | ---------------------- | ----------------------------------------------------- |
| `stopPropagation()`          | Да                     | Нет                                                   |
| `stopImmediatePropagation()` | Да                     | Да                                                    |

---

### Как узнать об использовании метода `event.preventDefault()`?

Для проверки используется свойство `defaultPrevented`.

Оно показывает, был ли вызван метод `preventDefault()` для данного события.

Пример:

```javascript
document.addEventListener("click", (event) => {
  console.log(event.defaultPrevented);
});
```

Использование:

```javascript
button.addEventListener("click", (event) => {
  event.preventDefault();

  console.log(event.defaultPrevented);
});
```

Результат:

```text
true
```

Другой обработчик может проверить состояние:

```javascript
button.addEventListener("click", (event) => {
  if (event.defaultPrevented) {
    console.log("Действие уже отменено");
  }
});
```

Свойство `defaultPrevented` часто используется библиотеками и фреймворками для определения, было ли уже отменено стандартное действие браузера.

---

### В чем разница между операторами `==` и `===`?

Оба оператора используются для сравнения значений, но работают по-разному.

#### Оператор `==` (нестрогое сравнение)

Перед сравнением выполняет неявное приведение типов.

Примеры:

```javascript
console.log(5 == "5"); // true
console.log(true == 1); // true
console.log(false == 0); // true
```

JavaScript сначала приводит значения к одному типу, а затем сравнивает их.

---

#### Оператор `===` (строгое сравнение)

Не выполняет приведение типов.

Сравниваются:

1. Типы данных.
2. Значения.

Примеры:

```javascript
console.log(5 === "5"); // false
console.log(true === 1); // false
console.log(false === 0); // false
```

---

#### Примеры сравнения

```javascript
console.log(null == undefined); // true
console.log(null === undefined); // false

console.log("" == false); // true
console.log("" === false); // false

console.log(0 == false); // true
console.log(0 === false); // false
```

---

#### Рекомендации

В современном JavaScript почти всегда рекомендуется использовать оператор `===`, поскольку он делает поведение кода более предсказуемым и исключает ошибки, связанные с автоматическим приведением типов.

Пример:

```javascript
const age = "18";

if (age === 18) {
  console.log("Взрослый");
}
```

Этот код не выполнится, так как строка и число имеют разные типы.

---

#### Сравнение операторов

| Оператор | Проверяет значение | Проверяет тип |
| -------- | ------------------ | ------------- |
| `==`     | Да                 | Нет           |
| `===`    | Да                 | Да            |

Поэтому в большинстве случаев следует отдавать предпочтение оператору строгого сравнения `===`.

---

### Почему результатом сравнения двух похожих объектов является `false`?

В JavaScript объекты сравниваются по ссылке, а не по содержимому.

Даже если два объекта содержат одинаковые свойства и значения, они являются разными объектами в памяти.

Пример:

```javascript
const obj1 = { name: "John" };
const obj2 = { name: "John" };

console.log(obj1 === obj2); // false
console.log(obj1 == obj2);  // false
```

Несмотря на одинаковое содержимое, ссылки различаются:

```javascript
console.log(obj1); // ссылка A
console.log(obj2); // ссылка B
```

Если обе переменные указывают на один и тот же объект, сравнение вернет `true`:

```javascript
const obj1 = { name: "John" };
const obj2 = obj1;

console.log(obj1 === obj2); // true
```

То же самое относится к массивам и функциям:

```javascript
[] === []; // false

[1, 2] === [1, 2]; // false

(() => {}) === (() => {}); // false
```

Для сравнения содержимого объектов обычно используют:

```javascript
JSON.stringify(obj1) === JSON.stringify(obj2);
```

или специализированные функции глубокого сравнения (`lodash.isEqual`, `fast-deep-equal` и др.).

---

### Как записать несколько выражений в одну строку?

Для выполнения нескольких выражений в одном выражении можно использовать оператор запятая (`,`).

Он выполняет выражения слева направо и возвращает результат последнего выражения.

Пример:

```javascript
let x = (1 + 1, 2 + 2, 3 + 3);

console.log(x); // 6
```

Еще пример:

```javascript
let a = 1;

let result = (
  a++,
  a++,
  a
);

console.log(result); // 3
```

Оператор часто встречается в циклах:

```javascript
for (let i = 0, j = 10; i < j; i++, j--) {
  console.log(i, j);
}
```

Также несколько инструкций можно записывать через точку с запятой:

```javascript
let a = 1; let b = 2; let c = 3;
```

Однако такой стиль ухудшает читаемость и редко используется в современном коде.

---

### Что такое поднятие (Hoisting)?

Hoisting (поднятие) — это механизм JavaScript, при котором объявления переменных и функций мысленно перемещаются в начало своей области видимости до выполнения кода.

Важно понимать, что физического перемещения кода не происходит — это особенность работы движка JavaScript.

#### Поднятие функции

Функции, объявленные через Function Declaration, полностью доступны до места объявления.

```javascript
sayHello();

function sayHello() {
  console.log("Hello");
}
```

Результат:

```text
Hello
```

Интерпретатор воспринимает это примерно так:

```javascript
function sayHello() {
  console.log("Hello");
}

sayHello();
```

---

#### Поднятие переменных `var`

Переменная объявляется, но не инициализируется.

```javascript
console.log(name);

var name = "John";
```

Результат:

```text
undefined
```

Движок интерпретирует код следующим образом:

```javascript
var name;

console.log(name);

name = "John";
```

---

#### Поведение `let` и `const`

Для `let` и `const` поднятие также происходит, но до момента объявления переменная находится в состоянии Temporal Dead Zone (TDZ).

```javascript
console.log(name);

let name = "John";
```

Результат:

```text
ReferenceError
```

---

#### Итоги

| Конструкция          | Поднимается | Доступна до объявления |
| -------------------- | ----------- | ---------------------- |
| Function Declaration | Да          | Да                     |
| var                  | Да          | Да (`undefined`)       |
| let                  | Да          | Нет                    |
| const                | Да          | Нет                    |

---

### Что такое область видимости (Scope)?

Scope (область видимости) определяет, где переменная доступна в программе.

JavaScript использует лексическую область видимости (Lexical Scope).

---

#### Глобальная область видимости

Переменная доступна из любого места программы.

```javascript
const appName = "My App";

function test() {
  console.log(appName);
}
```

---

#### Локальная область видимости функции

Переменная существует только внутри функции.

```javascript
function test() {
  const message = "Hello";
}

console.log(message); // ReferenceError
```

---

#### Блочная область видимости

Переменные `let` и `const` ограничены блоком `{}`.

```javascript
if (true) {
  let name = "John";
}

console.log(name); // ReferenceError
```

---

#### Особенность `var`

`var` игнорирует блочную область видимости.

```javascript
if (true) {
  var name = "John";
}

console.log(name); // John
```

---

#### Цепочка областей видимости (Scope Chain)

Внутренняя функция имеет доступ к внешним переменным.

```javascript
const globalVar = "global";

function outer() {
  const outerVar = "outer";

  function inner() {
    console.log(globalVar);
    console.log(outerVar);
  }

  inner();
}
```

---

#### Виды области видимости

| Вид            | Описание           |
| -------------- | ------------------ |
| Global Scope   | Глобальная область |
| Function Scope | Область функции    |
| Block Scope    | Область блока `{}` |
| Module Scope   | Область ES-модуля  |

---

### Что такое замыкание (Closures)?

Замыкание (Closure) — это функция, которая запоминает переменные из своей внешней области видимости даже после завершения выполнения внешней функции.

Это одна из самых важных концепций JavaScript.

Пример:

```javascript
function createCounter() {
  let count = 0;

  return function () {
    count++;
    return count;
  };
}

const counter = createCounter();

console.log(counter()); // 1
console.log(counter()); // 2
console.log(counter()); // 3
```

После завершения `createCounter()` переменная `count` не удаляется, потому что на нее продолжает ссылаться внутренняя функция.

---

#### Как работает замыкание

```javascript
function outer() {
  const name = "John";

  function inner() {
    console.log(name);
  }

  return inner;
}

const fn = outer();

fn();
```

Результат:

```text
John
```

Хотя функция `outer()` уже завершилась, переменная `name` остается доступной.

---

#### Практическое применение

##### Инкапсуляция данных

```javascript
function createUser() {
  let password = "123456";

  return {
    checkPassword(value) {
      return value === password;
    }
  };
}

const user = createUser();

console.log(user.checkPassword("123456"));
```

Переменная `password` недоступна напрямую извне.

---

##### Фабрики функций

```javascript
function multiply(multiplier) {
  return function (value) {
    return value * multiplier;
  };
}

const double = multiply(2);
const triple = multiply(3);

console.log(double(5)); // 10
console.log(triple(5)); // 15
```

---

#### Преимущества замыканий

* Сокрытие внутренних данных.
* Создание приватных переменных.
* Реализация фабрик функций.
* Сохранение состояния между вызовами.
* Использование в колбэках и обработчиках событий.

Замыкания активно используются в React, Redux, Node.js, обработчиках событий и большинстве современных JavaScript-библиотек.

---

### Для чего предназначены методы `setTimeout` и `setInterval`?

Методы `setTimeout` и `setInterval` позволяют выполнять код с задержкой или через определенные промежутки времени.

---

#### `setTimeout()`

Выполняет функцию один раз через указанное количество миллисекунд.

Синтаксис:

```javascript
setTimeout(callback, delay);
```

Пример:

```javascript
setTimeout(() => {
  console.log("Прошло 2 секунды");
}, 2000);
```

Вывод:

```text
Прошло 2 секунды
```

Отмена выполнения:

```javascript
const timerId = setTimeout(() => {
  console.log("Hello");
}, 5000);

clearTimeout(timerId);
```

---

#### `setInterval()`

Выполняет функцию многократно через заданный интервал времени.

Синтаксис:

```javascript
setInterval(callback, delay);
```

Пример:

```javascript
setInterval(() => {
  console.log("Каждую секунду");
}, 1000);
```

Вывод:

```text
Каждую секунду
Каждую секунду
Каждую секунду
...
```

Остановка интервала:

```javascript
const intervalId = setInterval(() => {
  console.log("Tick");
}, 1000);

clearInterval(intervalId);
```

---

#### Особенности работы

Оба метода являются частью браузерного API (Web API) и Node.js API, а не самого языка JavaScript.

При срабатывании таймера функция помещается в очередь задач (Task Queue), после чего Event Loop передает ее в стек вызовов (Call Stack), когда он освобождается.

Поэтому задержка является минимальной гарантированной, а не абсолютно точной.

Пример:

```javascript
console.log("Start");

setTimeout(() => {
  console.log("Timeout");
}, 0);

console.log("End");
```

Результат:

```text
Start
End
Timeout
```

Даже при задержке `0` колбэк выполняется только после завершения текущего стека вызовов.

---

#### Сравнение

| Метод           | Выполняется                          |
| --------------- | ------------------------------------ |
| `setTimeout()`  | Один раз через указанную задержку    |
| `setInterval()` | Многократно через указанный интервал |

---

### Расскажите назначение и принципы работы с коллекциями `Map` и `Set`

`Map` и `Set` были добавлены в ES6 и предназначены для более удобной работы с коллекциями данных.

---

#### Коллекция `Map`

`Map` хранит пары ключ-значение.

В отличие от обычного объекта:

* Ключом может быть любой тип данных.
* Сохраняется порядок добавления элементов.
* Есть удобные методы для работы с коллекцией.

Создание:

```javascript
const map = new Map();
```

Добавление элементов:

```javascript
map.set("name", "John");
map.set("age", 25);
```

Получение значения:

```javascript
console.log(map.get("name"));
```

Результат:

```text
John
```

Проверка существования ключа:

```javascript
map.has("name");
```

Удаление:

```javascript
map.delete("age");
```

Размер коллекции:

```javascript
console.log(map.size);
```

Использование объекта как ключа:

```javascript
const user = { id: 1 };

const map = new Map();

map.set(user, "Admin");

console.log(map.get(user));
```

---

#### Коллекция `Set`

`Set` хранит только уникальные значения.

Создание:

```javascript
const set = new Set();
```

Добавление элементов:

```javascript
set.add(1);
set.add(2);
set.add(2);
set.add(3);
```

Результат:

```javascript
Set(3) {1, 2, 3}
```

Дубликаты автоматически удаляются.

Проверка наличия элемента:

```javascript
set.has(2);
```

Удаление:

```javascript
set.delete(2);
```

Размер:

```javascript
console.log(set.size);
```

---

#### Удаление дубликатов из массива

Очень популярное применение `Set`:

```javascript
const numbers = [1, 2, 2, 3, 3, 4];

const uniqueNumbers = [...new Set(numbers)];

console.log(uniqueNumbers);
```

Результат:

```javascript
[1, 2, 3, 4]
```

---

#### Сравнение

| Коллекция | Назначение                   |
| --------- | ---------------------------- |
| `Map`     | Хранение пар ключ-значение   |
| `Set`     | Хранение уникальных значений |

---

### Расскажите о стрелочных функциях (Arrow Function). В чем заключаются отличия стрелочных функций от обычных?

Стрелочные функции (Arrow Functions) появились в ES6 и предоставляют более короткий синтаксис для объявления функций.

Обычная функция:

```javascript
function sum(a, b) {
  return a + b;
}
```

Стрелочная функция:

```javascript
const sum = (a, b) => {
  return a + b;
};
```

Короткая запись:

```javascript
const sum = (a, b) => a + b;
```

---

#### Если параметр один

Скобки можно опустить:

```javascript
const square = x => x * x;
```

---

#### Если нет параметров

Скобки обязательны:

```javascript
const greet = () => {
  console.log("Hello");
};
```

---

#### Главное отличие — отсутствие собственного `this`

Обычная функция:

```javascript
const user = {
  name: "John",

  sayHello() {
    console.log(this.name);
  }
};

user.sayHello();
```

Результат:

```text
John
```

---

Стрелочная функция:

```javascript
const user = {
  name: "John",

  sayHello: () => {
    console.log(this.name);
  }
};

user.sayHello();
```

Результат:

```text
undefined
```

Стрелочная функция не создает собственный `this`, а берет его из внешней области видимости.

---

#### Другие отличия

##### Нет объекта `arguments`

```javascript
const test = () => {
  console.log(arguments);
};
```

Вызовет ошибку.

Для таких случаев используется оператор остаточных параметров:

```javascript
const test = (...args) => {
  console.log(args);
};
```

---

##### Нельзя использовать как конструктор

```javascript
const User = (name) => {
  this.name = name;
};

new User("John");
```

Результат:

```text
TypeError
```

---

#### Когда использовать

Стрелочные функции особенно удобны:

* В колбэках.
* В методах массивов (`map`, `filter`, `reduce`).
* В Promise.
* В React-компонентах и обработчиках.

Пример:

```javascript
const numbers = [1, 2, 3];

const doubled = numbers.map(x => x * 2);
```

---

### Для чего используется директива `"use strict"`?

`"use strict"` включает строгий режим выполнения JavaScript.

Он был добавлен в ECMAScript 5 для устранения некоторых ошибок и небезопасного поведения языка.

Пример:

```javascript
"use strict";
```

Обычно размещается в начале файла или функции.

---

#### Запрет создания глобальных переменных

Без строгого режима:

```javascript
name = "John";
```

Создается глобальная переменная.

Со строгим режимом:

```javascript
"use strict";

name = "John";
```

Результат:

```text
ReferenceError
```

---

#### Запрет дублирования параметров

Некорректно:

```javascript
"use strict";

function sum(a, a) {}
```

Результат:

```text
SyntaxError
```

---

#### Изменение поведения `this`

Без строгого режима:

```javascript
function test() {
  console.log(this);
}

test();
```

Результат:

```javascript
window
```

В браузере.

Со строгим режимом:

```javascript
"use strict";

function test() {
  console.log(this);
}

test();
```

Результат:

```javascript
undefined
```

---

#### Нужно ли использовать сегодня?

В современных проектах, использующих ES-модули:

```javascript
import ...
export ...
```

строгий режим включается автоматически.

Поэтому отдельное указание `"use strict"` обычно не требуется.

---

### Какое значение имеет `this`?

`this` — это специальное ключевое слово, которое указывает на объект, в контексте которого была вызвана функция.

Значение `this` определяется не местом объявления функции, а способом ее вызова.

---

#### Глобальный контекст

В браузере:

```javascript
console.log(this);
```

Результат:

```javascript
window
```

---

#### Внутри метода объекта

```javascript
const user = {
  name: "John",

  sayHello() {
    console.log(this.name);
  }
};

user.sayHello();
```

Результат:

```text
John
```

Здесь `this` указывает на объект `user`.

---

#### Обычная функция

```javascript
function test() {
  console.log(this);
}

test();
```

Без строгого режима:

```javascript
window
```

Со строгим режимом:

```javascript
undefined
```

---

#### Явное указание `this`

Метод `call()`:

```javascript
function greet() {
  console.log(this.name);
}

const user = {
  name: "John"
};

greet.call(user);
```

Результат:

```text
John
```

---

#### Метод `apply()`

Работает аналогично `call()`, но аргументы передаются массивом.

```javascript
function sum(a, b) {
  console.log(this.name, a + b);
}

sum.apply({ name: "Calc" }, [1, 2]);
```

---

#### Метод `bind()`

Создает новую функцию с привязанным контекстом.

```javascript
function greet() {
  console.log(this.name);
}

const user = {
  name: "John"
};

const boundGreet = greet.bind(user);

boundGreet();
```

Результат:

```text
John
```

---

#### Стрелочные функции и `this`

Стрелочные функции не имеют собственного `this`.

```javascript
const user = {
  name: "John",

  sayHello() {
    const print = () => {
      console.log(this.name);
    };

    print();
  }
};

user.sayHello();
```

Результат:

```text
John
```

Стрелочная функция наследует `this` от внешней функции.

---

#### Правила определения `this`

| Способ вызова        | Значение `this`                        |
| -------------------- | -------------------------------------- |
| Глобальный контекст  | `window` (браузер)                     |
| Метод объекта        | Объект перед точкой                    |
| Обычная функция      | `window` или `undefined` в strict mode |
| `call()` / `apply()` | Указанный объект                       |
| `bind()`             | Навсегда привязанный объект            |
| Стрелочная функция   | Наследует внешний `this`               |

---

### Что такое прототип объекта?

Прототип (Prototype) — это объект, от которого другие объекты могут наследовать свойства и методы.

Каждый объект в JavaScript имеет скрытую ссылку на свой прототип (`[[Prototype]]`).

Благодаря прототипам реализуется механизм наследования.

Пример:

```javascript
const user = {
  sayHello() {
    console.log("Hello");
  }
};

const admin = Object.create(user);

admin.sayHello();
```

Результат:

```text
Hello
```

Хотя у объекта `admin` нет собственного метода `sayHello`, JavaScript находит его в прототипе.

---

#### Цепочка прототипов (Prototype Chain)

Если свойство отсутствует в объекте, JavaScript ищет его:

1. В самом объекте.
2. В его прототипе.
3. В прототипе прототипа.
4. И так далее до `null`.

Пример:

```javascript
const animal = {
  eat() {
    console.log("Eating");
  }
};

const dog = Object.create(animal);

dog.eat();
```

Поиск свойства происходит по цепочке прототипов.

---

#### Свойство `prototype`

У функций-конструкторов есть свойство `prototype`.

```javascript
function User(name) {
  this.name = name;
}

User.prototype.sayHello = function () {
  console.log(`Hello ${this.name}`);
};

const user = new User("John");

user.sayHello();
```

Все экземпляры будут использовать один общий метод из прототипа.

---

#### Проверка прототипа

```javascript
const user = {};

console.log(Object.getPrototypeOf(user));
```

Или:

```javascript
console.log(user.__proto__);
```

Хотя использование `__proto__` считается устаревшим.

---

#### Почему используются прототипы?

Без прототипов каждый объект хранил бы собственные копии методов.

Прототипы позволяют:

* Экономить память.
* Реализовывать наследование.
* Разделять общую функциональность между объектами.

---

### Для чего используется метод `apply()`?

Метод `apply()` позволяет вызвать функцию с указанным значением `this` и передать аргументы в виде массива.

Синтаксис:

```javascript
func.apply(thisArg, [arg1, arg2, ...]);
```

Пример:

```javascript
function greet(city) {
  console.log(`${this.name} from ${city}`);
}

const user = {
  name: "John"
};

greet.apply(user, ["Paris"]);
```

Результат:

```text
John from Paris
```

---

#### Использование для работы с массивами

До появления оператора расширения (`...`) часто использовалось:

```javascript
const numbers = [1, 5, 10, 3];

const max = Math.max.apply(null, numbers);

console.log(max);
```

Сегодня обычно используют:

```javascript
const max = Math.max(...numbers);
```

---

#### Особенности

* Немедленно вызывает функцию.
* Позволяет явно установить значение `this`.
* Аргументы передаются массивом.

---

### Для чего используется метод `call()`?

Метод `call()` вызывает функцию с указанным значением `this`, передавая аргументы по отдельности.

Синтаксис:

```javascript
func.call(thisArg, arg1, arg2, arg3);
```

Пример:

```javascript
function greet(city) {
  console.log(`${this.name} from ${city}`);
}

const user = {
  name: "John"
};

greet.call(user, "Paris");
```

Результат:

```text
John from Paris
```

---

#### Заимствование методов

```javascript
const person1 = {
  name: "John"
};

const person2 = {
  name: "Kate"
};

function sayHello() {
  console.log(this.name);
}

sayHello.call(person1);
sayHello.call(person2);
```

Результат:

```text
John
Kate
```

---

#### Особенности

* Немедленно вызывает функцию.
* Позволяет явно установить `this`.
* Аргументы передаются по одному.

---

### В чем разница между методами `call()` и `apply()`?

Оба метода делают одно и то же:

* Вызывают функцию.
* Позволяют указать значение `this`.

Различие заключается только в способе передачи аргументов.

---

#### `call()`

Аргументы передаются по отдельности.

```javascript
function sum(a, b) {
  return a + b;
}

sum.call(null, 1, 2);
```

---

#### `apply()`

Аргументы передаются массивом.

```javascript
function sum(a, b) {
  return a + b;
}

sum.apply(null, [1, 2]);
```

---

#### Сравнение

```javascript
function greet(city, country) {
  console.log(`${this.name} ${city} ${country}`);
}

const user = {
  name: "John"
};

greet.call(user, "Paris", "France");

greet.apply(user, ["Paris", "France"]);
```

Результат одинаковый:

```text
John Paris France
```

---

#### Таблица различий

| Метод     | Устанавливает `this` | Вызывает функцию сразу | Передача аргументов |
| --------- | -------------------- | ---------------------- | ------------------- |
| `call()`  | Да                   | Да                     | Через запятую       |
| `apply()` | Да                   | Да                     | Массивом            |

В современном JavaScript `apply()` используется значительно реже благодаря оператору расширения (`...`).

---

### Для чего используется метод `Function.prototype.bind()`?

Метод `bind()` создает новую функцию с заранее привязанным значением `this`.

В отличие от `call()` и `apply()`, функция не вызывается сразу.

Синтаксис:

```javascript
const newFunc = func.bind(thisArg);
```

---

#### Пример

```javascript
function greet() {
  console.log(this.name);
}

const user = {
  name: "John"
};

const boundGreet = greet.bind(user);

boundGreet();
```

Результат:

```text
John
```

---

#### Отличие от `call()` и `apply()`

`call()`:

```javascript
greet.call(user);
```

Функция выполняется немедленно.

---

`bind()`:

```javascript
const fn = greet.bind(user);

fn();
```

Создается новая функция, которая будет вызвана позже.

---

#### Частичное применение аргументов

`bind()` позволяет заранее фиксировать аргументы.

```javascript
function multiply(a, b) {
  return a * b;
}

const double = multiply.bind(null, 2);

console.log(double(5));
```

Результат:

```text
10
```

Фактически получается:

```javascript
multiply(2, 5);
```

---

#### Частая проблема с потерей контекста

```javascript
const user = {
  name: "John",

  sayHello() {
    console.log(this.name);
  }
};

setTimeout(user.sayHello, 1000);
```

Результат:

```text
undefined
```

Контекст потерян.

Решение:

```javascript
setTimeout(user.sayHello.bind(user), 1000);
```

Результат:

```text
John
```

---

#### Сравнение `call`, `apply` и `bind`

| Метод     | Устанавливает `this` | Вызывает функцию сразу | Возвращает новую функцию |
| --------- | -------------------- | ---------------------- | ------------------------ |
| `call()`  | Да                   | Да                     | Нет                      |
| `apply()` | Да                   | Да                     | Нет                      |
| `bind()`  | Да                   | Нет                    | Да                       |

---

#### Когда использовать `bind()`

Метод `bind()` чаще всего применяется:

* Для сохранения контекста `this`.
* В обработчиках событий.
* В таймерах (`setTimeout`, `setInterval`).
* Для частичного применения аргументов.
* При передаче методов объекта как колбэков.

---

### Метод `map()`

Метод `map()` создает новый массив, применяя указанную функцию к каждому элементу исходного массива.

Синтаксис:

```javascript
array.map(callback);
```

Пример:

```javascript
const numbers = [1, 2, 3, 4];

const doubled = numbers.map(num => num * 2);

console.log(doubled);
```

Результат:

```javascript
[2, 4, 6, 8]
```

Исходный массив не изменяется:

```javascript
console.log(numbers);
```

Результат:

```javascript
[1, 2, 3, 4]
```

---

#### Преобразование объектов

```javascript
const users = [
  { name: "John" },
  { name: "Kate" },
  { name: "Mike" }
];

const names = users.map(user => user.name);

console.log(names);
```

Результат:

```javascript
["John", "Kate", "Mike"]
```

---

#### Параметры callback

```javascript
array.map((element, index, array) => {});
```

| Параметр | Описание        |
| -------- | --------------- |
| element  | Текущий элемент |
| index    | Индекс элемента |
| array    | Исходный массив |

Пример:

```javascript
const result = [10, 20, 30].map((item, index) => {
  return `${index}: ${item}`;
});

console.log(result);
```

---

#### Когда использовать `map()`

Используется, когда нужно преобразовать каждый элемент массива и получить новый массив той же длины.

---

### Метод `filter()`

Метод `filter()` создает новый массив только из тех элементов, которые удовлетворяют условию.

Синтаксис:

```javascript
array.filter(callback);
```

Пример:

```javascript
const numbers = [1, 2, 3, 4, 5, 6];

const evenNumbers = numbers.filter(num => num % 2 === 0);

console.log(evenNumbers);
```

Результат:

```javascript
[2, 4, 6]
```

---

#### Фильтрация объектов

```javascript
const users = [
  { name: "John", age: 25 },
  { name: "Kate", age: 17 },
  { name: "Mike", age: 30 }
];

const adults = users.filter(user => user.age >= 18);

console.log(adults);
```

Результат:

```javascript
[
  { name: "John", age: 25 },
  { name: "Mike", age: 30 }
]
```

---

#### Параметры callback

```javascript
array.filter((element, index, array) => {});
```

| Параметр | Описание        |
| -------- | --------------- |
| element  | Текущий элемент |
| index    | Индекс элемента |
| array    | Исходный массив |

---

#### Когда использовать `filter()`

Используется, когда нужно отобрать элементы массива по определенному условию.

---

### Метод `reduce()`

Метод `reduce()` позволяет свести массив к одному значению.

Это может быть:

* Число.
* Строка.
* Объект.
* Новый массив.
* Любая другая структура данных.

Синтаксис:

```javascript
array.reduce(callback, initialValue);
```

---

#### Сумма элементов массива

```javascript
const numbers = [1, 2, 3, 4];

const sum = numbers.reduce((accumulator, currentValue) => {
  return accumulator + currentValue;
}, 0);

console.log(sum);
```

Результат:

```javascript
10
```

---

#### Параметры callback

```javascript
array.reduce(
  (accumulator, currentValue, index, array) => {},
  initialValue
);
```

| Параметр     | Описание                 |
| ------------ | ------------------------ |
| accumulator  | Накопленное значение     |
| currentValue | Текущий элемент          |
| index        | Индекс текущего элемента |
| array        | Исходный массив          |

---

#### Группировка данных

```javascript
const users = [
  { name: "John", age: 25 },
  { name: "Kate", age: 25 },
  { name: "Mike", age: 30 }
];

const grouped = users.reduce((acc, user) => {
  if (!acc[user.age]) {
    acc[user.age] = [];
  }

  acc[user.age].push(user);

  return acc;
}, {});

console.log(grouped);
```

Результат:

```javascript
{
  25: [
    { name: "John", age: 25 },
    { name: "Kate", age: 25 }
  ],
  30: [
    { name: "Mike", age: 30 }
  ]
}
```

---

#### Когда использовать `reduce()`

Используется для:

* Подсчета суммы.
* Поиска максимума или минимума.
* Группировки данных.
* Преобразования массива в объект.
* Построения сложных вычислений над коллекциями.

---

#### Сравнение `map`, `filter`, `reduce`

| Метод      | Что делает                         | Возвращает                |
| ---------- | ---------------------------------- | ------------------------- |
| `map()`    | Преобразует каждый элемент         | Новый массив той же длины |
| `filter()` | Отбирает элементы по условию       | Новый массив              |
| `reduce()` | Сворачивает массив в одно значение | Любой тип данных          |

---

### Что такое объект `arguments`?

`arguments` — это специальный псевдомассив, доступный внутри обычных функций.

Он содержит все аргументы, переданные при вызове функции.

Пример:

```javascript
function showArguments() {
  console.log(arguments);
}

showArguments(1, 2, 3);
```

Результат:

```javascript
Arguments(3) [1, 2, 3]
```

---

#### Доступ по индексу

```javascript
function test() {
  console.log(arguments[0]);
  console.log(arguments[1]);
}

test("Hello", "World");
```

Результат:

```text
Hello
World
```

---

#### Подсчет количества аргументов

```javascript
function test() {
  console.log(arguments.length);
}

test(1, 2, 3, 4);
```

Результат:

```text
4
```

---

#### Почему это псевдомассив?

У объекта `arguments` есть:

* Индексы.
* Свойство `length`.

Но отсутствуют методы массива:

```javascript
arguments.map(...);
arguments.filter(...);
```

Вызовет ошибку.

---

#### Преобразование в массив

```javascript
function test() {
  const args = Array.from(arguments);

  console.log(args);
}
```

или:

```javascript
function test() {
  const args = [...arguments];

  console.log(args);
}
```

---

#### Современная альтернатива — Rest Parameters

Сегодня вместо `arguments` обычно используют оператор остаточных параметров.

```javascript
function test(...args) {
  console.log(args);
}

test(1, 2, 3);
```

Результат:

```javascript
[1, 2, 3]
```

Преимущества:

* Настоящий массив.
* Работает со стрелочными функциями.
* Более читаемый код.

---

#### Особенность стрелочных функций

У стрелочных функций собственного объекта `arguments` нет.

```javascript
const test = () => {
  console.log(arguments);
};
```

Результат:

```text
ReferenceError
```

Для стрелочных функций необходимо использовать `...args`.

---

### Что такое ECMAScript?

ECMAScript (ES) — это официальный стандарт языка JavaScript.

JavaScript является реализацией спецификации ECMAScript.

Стандарт определяет:

* Синтаксис языка.
* Типы данных.
* Объекты.
* Функции.
* Операторы.
* Поведение языка.

---

#### История появления

В середине 1990-х годов появились разные реализации JavaScript:

* JavaScript (Netscape)
* JScript (Microsoft)

Чтобы обеспечить совместимость, организация Ecma International разработала единый стандарт — ECMAScript.

---

#### Основные версии ECMAScript

| Версия       | Год   | Основные возможности                                    |
| ------------ | ----- | ------------------------------------------------------- |
| ES3          | 1999  | Базовая версия языка                                    |
| ES5          | 2009  | Strict Mode, JSON, Array Methods                        |
| ES6 (ES2015) | 2015  | let, const, classes, modules, arrow functions, promises |
| ES2016       | 2016  | Оператор `**`                                           |
| ES2017       | 2017  | async/await                                             |
| ES2018       | 2018  | Rest/Spread для объектов                                |
| ES2019       | 2019  | flat(), flatMap()                                       |
| ES2020       | 2020  | BigInt, Optional Chaining                               |
| ES2021+      | 2021+ | Регулярные ежегодные обновления                         |

---

#### Самые важные возможности ES6

##### `let` и `const`

```javascript
const name = "John";
let age = 25;
```

##### Стрелочные функции

```javascript
const sum = (a, b) => a + b;
```

##### Шаблонные строки

```javascript
const name = "John";

console.log(`Hello ${name}`);
```

##### Классы

```javascript
class User {
  constructor(name) {
    this.name = name;
  }
}
```

##### Модули

```javascript
export const name = "John";

import { name } from "./user.js";
```

---

#### ECMAScript и JavaScript

Часто говорят:

```text
JavaScript = язык программирования
ECMAScript = спецификация этого языка
```

Аналогия:

```text
ECMAScript — правила дорожного движения
JavaScript — автомобиль, который этим правилам следует
```

---

### Что нового привнес в JS стандарт ES6 (ECMAScript 2015)?

ES6 (ECMAScript 2015) — одно из самых крупных обновлений JavaScript. Оно значительно расширило возможности языка и сделало код более удобным, читаемым и безопасным.

Основные нововведения:

---

#### `let` и `const`

Появились новые способы объявления переменных.

```javascript
let count = 0;

const API_URL = "https://api.example.com";
```

Они имеют блочную область видимости и устраняют многие проблемы `var`.

---

#### Стрелочные функции (Arrow Functions)

Короткий синтаксис записи функций.

```javascript
const sum = (a, b) => a + b;
```

Особенность — отсутствие собственного `this`.

---

#### Шаблонные строки (Template Literals)

Позволяют удобно вставлять переменные в строку.

```javascript
const name = "John";

console.log(`Hello ${name}`);
```

Поддерживают многострочные строки:

```javascript
const text = `
Line 1
Line 2
`;
```

---

#### Деструктуризация

Извлечение значений из объектов и массивов.

```javascript
const user = {
  name: "John",
  age: 25
};

const { name, age } = user;
```

---

#### Параметры по умолчанию

```javascript
function greet(name = "Guest") {
  return `Hello ${name}`;
}
```

---

#### Rest и Spread операторы

Rest:

```javascript
function sum(...numbers) {
  return numbers.reduce((a, b) => a + b, 0);
}
```

Spread:

```javascript
const arr1 = [1, 2];
const arr2 = [...arr1, 3, 4];
```

---

#### Классы

Новый синтаксис для создания объектов и наследования.

```javascript
class User {
  constructor(name) {
    this.name = name;
  }

  sayHello() {
    console.log(this.name);
  }
}
```

---

#### Модули

Экспорт:

```javascript
export const PI = 3.14;
```

Импорт:

```javascript
import { PI } from "./math.js";
```

---

#### Promises

Удобный способ работы с асинхронным кодом.

```javascript
fetch("/api/users")
  .then(response => response.json())
  .then(data => console.log(data));
```

---

#### Map и Set

Новые встроенные коллекции.

```javascript
const map = new Map();

const set = new Set();
```

---

#### Символы (Symbol)

Новый примитивный тип данных.

```javascript
const id = Symbol("id");
```

---

#### Итоги ES6

Наиболее важные возможности:

* `let`, `const`
* Arrow Functions
* Classes
* Modules
* Template Literals
* Destructuring
* Rest/Spread
* Promises
* Map и Set
* Symbol

ES6 стал основой современного JavaScript.

---

### В чем разница между ключевыми словами `var`, `let` и `const`?

Все три используются для объявления переменных, но отличаются областью видимости, поднятием и возможностью изменения значения.

---

#### `var`

Использовался до появления ES6.

Особенности:

* Имеет функциональную область видимости.
* Подвержен hoisting.
* Можно переобъявлять.
* Можно изменять значение.

Пример:

```javascript
var name = "John";

var name = "Kate";

console.log(name);
```

Результат:

```text
Kate
```

---

#### Проблема `var`

```javascript
if (true) {
  var age = 25;
}

console.log(age);
```

Результат:

```text
25
```

Переменная доступна за пределами блока.

---

#### `let`

Появился в ES6.

Особенности:

* Блочная область видимости.
* Можно изменять значение.
* Нельзя переобъявлять в одной области видимости.

```javascript
let count = 1;

count = 2;
```

Корректно.

---

```javascript
let count = 1;
let count = 2;
```

Результат:

```text
SyntaxError
```

---

#### Блочная область видимости

```javascript
if (true) {
  let age = 25;
}

console.log(age);
```

Результат:

```text
ReferenceError
```

---

#### `const`

Также появился в ES6.

Особенности:

* Блочная область видимости.
* Нельзя переопределить переменную.
* Обязательно требует инициализации.

```javascript
const PI = 3.14;
```

---

Некорректно:

```javascript
const PI;
```

Результат:

```text
SyntaxError
```

---

#### Важно понимать

`const` запрещает изменение ссылки, но не объекта.

```javascript
const user = {
  name: "John"
};

user.name = "Kate";
```

Корректно.

---

Некорректно:

```javascript
user = {};
```

Результат:

```text
TypeError
```

---

#### Сравнение

| Свойство                   | var | let      | const    |
| -------------------------- | --- | -------- | -------- |
| Блочная область видимости  | Нет | Да       | Да       |
| Hoisting                   | Да  | Да (TDZ) | Да (TDZ) |
| Повторное объявление       | Да  | Нет      | Нет      |
| Изменение значения         | Да  | Да       | Нет      |
| Обязательная инициализация | Нет | Нет      | Да       |

---

#### Что использовать сегодня?

Современная практика:

* Использовать `const` по умолчанию.
* Использовать `let`, если значение будет изменяться.
* Не использовать `var`.

---

### Что такое стрелочные функции (Arrow Functions)?

Стрелочные функции — это сокращенный синтаксис объявления функций, появившийся в ES6.

Обычная функция:

```javascript
function sum(a, b) {
  return a + b;
}
```

Стрелочная функция:

```javascript
const sum = (a, b) => {
  return a + b;
};
```

Короткая запись:

```javascript
const sum = (a, b) => a + b;
```

---

#### Один параметр

```javascript
const square = x => x * x;
```

---

#### Без параметров

```javascript
const greet = () => {
  console.log("Hello");
};
```

---

#### Главное отличие — собственный `this`

Обычная функция:

```javascript
const user = {
  name: "John",

  sayHello() {
    console.log(this.name);
  }
};
```

---

Стрелочная функция:

```javascript
const user = {
  name: "John",

  sayHello: () => {
    console.log(this.name);
  }
};
```

Здесь `this` не указывает на объект `user`.

Стрелочная функция берет `this` из внешней области видимости.

---

#### Другие отличия

* Нет собственного `arguments`.
* Нельзя использовать с `new`.
* Нет собственного `prototype`.

---

#### Где применяются

Чаще всего используются:

```javascript
numbers.map(item => item * 2);

setTimeout(() => {
  console.log("Hello");
}, 1000);

promise.then(data => console.log(data));
```

---

### Что такое классы (Classes)?

Классы — это специальный синтаксис для создания объектов и организации наследования.

Фактически классы являются надстройкой над прототипным наследованием.

---

#### Создание класса

```javascript
class User {
  constructor(name) {
    this.name = name;
  }

  sayHello() {
    console.log(`Hello ${this.name}`);
  }
}
```

Создание экземпляра:

```javascript
const user = new User("John");

user.sayHello();
```

Результат:

```text
Hello John
```

---

#### Конструктор

Метод `constructor()` вызывается автоматически при создании объекта.

```javascript
class User {
  constructor(name, age) {
    this.name = name;
    this.age = age;
  }
}
```

---

#### Наследование

```javascript
class Animal {
  eat() {
    console.log("Eating");
  }
}

class Dog extends Animal {
  bark() {
    console.log("Woof");
  }
}
```

Использование:

```javascript
const dog = new Dog();

dog.eat();
dog.bark();
```

---

#### Вызов родительского конструктора

```javascript
class Animal {
  constructor(name) {
    this.name = name;
  }
}

class Dog extends Animal {
  constructor(name, breed) {
    super(name);

    this.breed = breed;
  }
}
```

---

#### Важно

Под капотом:

```javascript
class User {}
```

эквивалентен примерно:

```javascript
function User() {}
```

с использованием прототипов.

---

### Что такое деструктуризация объекта (Object Destructuring)?

Деструктуризация — это механизм извлечения свойств объекта в отдельные переменные.

---

#### Базовый пример

```javascript
const user = {
  name: "John",
  age: 25
};

const { name, age } = user;

console.log(name);
console.log(age);
```

Результат:

```text
John
25
```

---

#### Переименование переменных

```javascript
const user = {
  name: "John"
};

const { name: userName } = user;

console.log(userName);
```

Результат:

```text
John
```

---

#### Значения по умолчанию

```javascript
const user = {
  name: "John"
};

const {
  name,
  age = 18
} = user;

console.log(age);
```

Результат:

```text
18
```

---

#### Вложенная деструктуризация

```javascript
const user = {
  name: "John",
  address: {
    city: "Paris"
  }
};

const {
  address: { city }
} = user;

console.log(city);
```

Результат:

```text
Paris
```

---

#### Деструктуризация параметров функции

```javascript
function printUser({ name, age }) {
  console.log(name, age);
}
```

Использование:

```javascript
printUser({
  name: "John",
  age: 25
});
```

---

#### Практическое применение

Очень часто используется в:

* React-компонентах.
* Работе с API.
* Параметрах функций.
* Извлечении данных из объектов.

Пример:

```javascript
const response = {
  data: {
    users: []
  }
};

const { data } = response;
```

Деструктуризация делает код короче, понятнее и уменьшает количество обращений к объектам.

---

### Что такое функция обратного вызова (Callback Function)?

Функция обратного вызова (Callback Function) — это функция, которая передается в другую функцию в качестве аргумента и вызывается позже.

Callback-функции широко используются для обработки событий, работы с асинхронным кодом и методами массивов.

Пример:

```javascript
function greet(name, callback) {
  console.log(`Hello, ${name}`);

  callback();
}

function sayBye() {
  console.log("Goodbye");
}

greet("John", sayBye);
```

Результат:

```text
Hello, John
Goodbye
```

---

#### Анонимная callback-функция

Часто callback передается непосредственно при вызове функции:

```javascript
greet("John", () => {
  console.log("Goodbye");
});
```

---

#### Callback в методах массива

```javascript
const numbers = [1, 2, 3];

numbers.forEach(number => {
  console.log(number);
});
```

Функция внутри `forEach()` является callback-функцией.

---

#### Callback и асинхронность

```javascript
setTimeout(() => {
  console.log("Прошла 1 секунда");
}, 1000);
```

Функция будет вызвана через секунду после запуска таймера.

---

#### Недостаток Callback Hell

При большом количестве вложенных асинхронных операций код становится трудно читаемым.

Пример:

```javascript
getUser(id, user => {
  getOrders(user.id, orders => {
    getProducts(orders, products => {
      console.log(products);
    });
  });
});
```

Такую проблему называют **Callback Hell** или **Pyramid of Doom**.

Для решения были созданы Promises и async/await.

---

### Что такое промисы (Promises)?

Promise (Промис) — это объект, представляющий результат асинхронной операции, который может быть доступен сейчас, позже или никогда.

Promise позволяет избавиться от глубокой вложенности callback-функций.

---

#### Создание Promise

```javascript
const promise = new Promise((resolve, reject) => {
  const success = true;

  if (success) {
    resolve("Операция успешна");
  } else {
    reject("Произошла ошибка");
  }
});
```

---

#### Состояния Promise

Промис может находиться в одном из трех состояний:

| Состояние | Описание            |
| --------- | ------------------- |
| Pending   | Ожидание выполнения |
| Fulfilled | Выполнен успешно    |
| Rejected  | Выполнен с ошибкой  |

Схема:

```text
Pending
   |
   +--> Fulfilled
   |
   +--> Rejected
```

---

#### Метод `.then()`

Обработка успешного результата:

```javascript
promise.then(result => {
  console.log(result);
});
```

---

#### Метод `.catch()`

Обработка ошибок:

```javascript
promise
  .then(result => {
    console.log(result);
  })
  .catch(error => {
    console.log(error);
  });
```

---

#### Метод `.finally()`

Выполняется независимо от результата.

```javascript
promise
  .finally(() => {
    console.log("Завершено");
  });
```

---

#### Пример с таймером

```javascript
const delay = ms => {
  return new Promise(resolve => {
    setTimeout(resolve, ms);
  });
};

delay(1000).then(() => {
  console.log("Прошла секунда");
});
```

---

#### Promise-методы

##### Promise.all()

Ожидает завершения всех промисов.

```javascript
Promise.all([
  fetch("/users"),
  fetch("/posts")
]);
```

---

##### Promise.race()

Возвращает результат первого завершившегося промиса.

```javascript
Promise.race([
  promise1,
  promise2
]);
```

---

##### Promise.allSettled()

Дожидается завершения всех промисов независимо от результата.

```javascript
Promise.allSettled([
  promise1,
  promise2
]);
```

---

### Что такое async/await?

`async/await` — это синтаксический сахар над Promise, появившийся в ES2017.

Он позволяет писать асинхронный код так, как будто он выполняется синхронно.

---

#### Ключевое слово `async`

Функция, объявленная через `async`, всегда возвращает Promise.

```javascript
async function getData() {
  return "Hello";
}
```

Фактически:

```javascript
Promise.resolve("Hello");
```

---

#### Ключевое слово `await`

`await` приостанавливает выполнение функции до завершения Promise.

Пример:

```javascript
async function getData() {
  const response = await fetch("/api/users");

  const data = await response.json();

  console.log(data);
}
```

---

#### Пример через Promise

```javascript
fetch("/api/users")
  .then(response => response.json())
  .then(data => console.log(data));
```

---

#### Аналогичный код через async/await

```javascript
async function getUsers() {
  const response = await fetch("/api/users");

  const data = await response.json();

  console.log(data);
}
```

Такой код обычно проще читать.

---

#### Обработка ошибок

Используется конструкция `try/catch`.

```javascript
async function getUsers() {
  try {
    const response = await fetch("/api/users");

    const data = await response.json();

    console.log(data);
  } catch (error) {
    console.error(error);
  }
}
```

---

#### Особенности

* `await` работает только внутри `async` функций.
* `async` всегда возвращает Promise.
* Упрощает работу с асинхронным кодом.
* Не заменяет Promise, а использует их.

---

### В чем разница между spread-оператором и rest-оператором?

Оба используют одинаковый синтаксис (`...`), но выполняют разные задачи.

---

#### Spread-оператор

Spread ("развернуть") распаковывает элементы массива или свойства объекта.

Пример с массивом:

```javascript
const numbers = [1, 2, 3];

console.log(...numbers);
```

Результат:

```text
1 2 3
```

---

Копирование массива:

```javascript
const arr1 = [1, 2, 3];

const arr2 = [...arr1];
```

---

Объединение массивов:

```javascript
const arr1 = [1, 2];
const arr2 = [3, 4];

const result = [...arr1, ...arr2];
```

Результат:

```javascript
[1, 2, 3, 4]
```

---

Копирование объекта:

```javascript
const user = {
  name: "John"
};

const copy = {
  ...user
};
```

---

#### Rest-оператор

Rest ("собрать остаток") собирает множество значений в массив.

Пример:

```javascript
function sum(...numbers) {
  console.log(numbers);
}

sum(1, 2, 3, 4);
```

Результат:

```javascript
[1, 2, 3, 4]
```

---

В деструктуризации:

```javascript
const [first, ...rest] = [1, 2, 3, 4];

console.log(rest);
```

Результат:

```javascript
[2, 3, 4]
```

---

#### Сравнение

##### Spread — распаковывает

```javascript
const arr = [1, 2, 3];

console.log(...arr);
```

---

##### Rest — собирает

```javascript
function test(...args) {
  console.log(args);
}
```

---

#### Главное правило

| Оператор       | Назначение           |
| -------------- | -------------------- |
| Spread (`...`) | Разворачивает данные |
| Rest (`...`)   | Собирает данные      |

---

### Что такое параметры по умолчанию (Default Parameters)?

Параметры по умолчанию позволяют задавать значение аргументу функции, если он не был передан при вызове.

Появились в ES6.

---

#### Пример

```javascript
function greet(name = "Guest") {
  console.log(`Hello, ${name}`);
}

greet();
```

Результат:

```text
Hello, Guest
```

---

При передаче значения используется переданный аргумент:

```javascript
greet("John");
```

Результат:

```text
Hello, John
```

---

#### Несколько параметров

```javascript
function createUser(
  name = "Guest",
  age = 18
) {
  return {
    name,
    age
  };
}
```

---

#### Выражения как значения по умолчанию

```javascript
function getDate(date = new Date()) {
  return date;
}
```

---

#### Использование предыдущих параметров

```javascript
function multiply(a, b = a * 2) {
  return b;
}

console.log(multiply(5));
```

Результат:

```text
10
```

---

#### Старый способ до ES6

Раньше использовали:

```javascript
function greet(name) {
  name = name || "Guest";

  console.log(name);
}
```

Проблема:

```javascript
greet("");
```

Результат:

```text
Guest
```

Хотя пустая строка была передана явно.

---

#### Современный способ

```javascript
function greet(name = "Guest") {
  console.log(name);
}

greet("");
```

Результат:

```text
```

Пустая строка сохраняется корректно.

---

#### Когда используется значение по умолчанию?

Только если аргумент равен `undefined`.

```javascript
function test(value = 10) {
  console.log(value);
}

test(undefined);
```

Результат:

```text
10
```

---

```javascript
test(null);
```

Результат:

```text
null
```

Поскольку `null` считается переданным значением, значение по умолчанию не используется.

---

### Что такое параметры по умолчанию (Default Parameters)?

Параметры по умолчанию позволяют задавать значения аргументам функции, которые будут использоваться, если при вызове функции соответствующий аргумент не был передан или имеет значение `undefined`.

Данная возможность появилась в ES6 и позволяет сделать код более читаемым и безопасным.

---

#### Синтаксис

```javascript
function greet(name = "Guest") {
  console.log(`Hello, ${name}`);
}
```

---

#### Пример использования

```javascript
function greet(name = "Guest") {
  console.log(`Hello, ${name}`);
}

greet();
greet("John");
```

Результат:

```text
Hello, Guest
Hello, John
```

---

#### Несколько параметров по умолчанию

```javascript
function createUser(name = "Guest", age = 18) {
  return {
    name,
    age
  };
}
```

---

#### Использование выражений

В качестве значения по умолчанию можно использовать любое выражение.

```javascript
function createDate(date = new Date()) {
  return date;
}
```

---

#### Использование других параметров

```javascript
function multiply(a, b = a * 2) {
  return b;
}

console.log(multiply(5));
```

Результат:

```text
10
```

---

#### Когда используется значение по умолчанию?

Только если аргумент равен `undefined`.

```javascript
function test(value = 100) {
  console.log(value);
}

test(undefined);
```

Результат:

```text
100
```

---

```javascript
test(null);
```

Результат:

```text
null
```

Поскольку `null` считается переданным значением.

---

#### Старый способ до ES6

Раньше часто использовали:

```javascript
function greet(name) {
  name = name || "Guest";

  console.log(name);
}
```

Проблема такого подхода:

```javascript
greet("");
```

Результат:

```text
Guest
```

Хотя пустая строка была передана явно.

---

#### Преимущества Default Parameters

* Более читаемый код.
* Отсутствие дополнительных проверок.
* Поддержка сложных выражений.
* Корректная работа с ложными значениями (`0`, `false`, `""`).

---

### Что такое объектная обертка (Wrapper Objects)?

Объектная обертка (Wrapper Object) — это специальный объект, который JavaScript автоматически создает для примитивного значения, когда требуется доступ к его методам или свойствам.

Благодаря объектам-оберткам примитивы могут вести себя как объекты.

---

#### Пример

```javascript
const str = "hello";

console.log(str.toUpperCase());
```

Результат:

```text
HELLO
```

Хотя строка является примитивом, метод `toUpperCase()` успешно работает.

---

#### Что происходит под капотом?

JavaScript временно создает объект:

```javascript
const temp = new String("hello");

temp.toUpperCase();
```

После выполнения операции временный объект удаляется.

---

#### Основные объекты-обертки

| Примитив | Объект-обертка |
| -------- | -------------- |
| string   | String         |
| number   | Number         |
| boolean  | Boolean        |
| bigint   | BigInt         |
| symbol   | Symbol         |

---

#### Пример со строкой

```javascript
const text = "JavaScript";

console.log(text.length);
```

Несмотря на то что строка является примитивом, свойство `length` доступно через объект-обертку.

---

#### Почему не стоит использовать обертки вручную?

```javascript
const name = new String("John");
```

Теперь это объект:

```javascript
console.log(typeof name);
```

Результат:

```text
object
```

---

Сравнение:

```javascript
console.log("John" === new String("John"));
```

Результат:

```text
false
```

Потому что сравниваются примитив и объект.

---

#### Итог

Объекты-обертки позволяют использовать методы и свойства примитивных типов данных. Обычно они создаются автоматически и редко используются напрямую.

---

### В чем разница между явным и неявным преобразованием типов (Implicit и Explicit Coercion)?

JavaScript автоматически или вручную может преобразовывать значения из одного типа в другой.

Этот процесс называется приведением типов (Type Coercion).

---

### Неявное преобразование (Implicit Coercion)

JavaScript самостоятельно выполняет преобразование типов.

Пример:

```javascript
console.log("5" + 2);
```

Результат:

```text
52
```

Число автоматически преобразуется в строку.

---

Другой пример:

```javascript
console.log("5" - 2);
```

Результат:

```text
3
```

Строка автоматически преобразуется в число.

---

Логические значения:

```javascript
console.log(true + 1);
```

Результат:

```text
2
```

Поскольку:

```javascript
Number(true) === 1
```

---

#### Опасность неявного преобразования

```javascript
console.log([] == false);
```

Результат:

```text
true
```

Подобное поведение часто становится причиной ошибок.

---

### Явное преобразование (Explicit Coercion)

Разработчик самостоятельно указывает преобразование.

---

#### В число

```javascript
Number("123");
```

или:

```javascript
+"123";
```

---

#### В строку

```javascript
String(123);
```

---

#### В логический тип

```javascript
Boolean(1);
```

---

#### Пример

```javascript
const result = Number("5") + 2;

console.log(result);
```

Результат:

```text
7
```

---

### Сравнение

Неявное:

```javascript
"5" * 2;
```

Явное:

```javascript
Number("5") * 2;
```

---

### Рекомендации

В большинстве случаев рекомендуется использовать явное преобразование типов, так как такой код легче читать и поддерживать.

---

### Что такое `NaN`? Как проверить, является ли значение `NaN`?

`NaN` (Not-a-Number) — специальное значение типа `number`, обозначающее некорректный результат числовой операции.

---

#### Примеры получения NaN

```javascript
Number("abc");
```

Результат:

```javascript
NaN
```

---

```javascript
0 / 0;
```

Результат:

```javascript
NaN
```

---

#### Тип NaN

```javascript
console.log(typeof NaN);
```

Результат:

```text
number
```

Это особенность JavaScript.

---

#### Особенность NaN

```javascript
console.log(NaN === NaN);
```

Результат:

```text
false
```

`NaN` — единственное значение в JavaScript, которое не равно самому себе.

---

#### Проверка через isNaN()

```javascript
console.log(isNaN(NaN));
```

Результат:

```text
true
```

Но:

```javascript
console.log(isNaN("hello"));
```

Результат:

```text
true
```

Потому что выполняется неявное преобразование типов.

---

#### Правильный способ — Number.isNaN()

```javascript
console.log(Number.isNaN(NaN));
```

Результат:

```text
true
```

---

```javascript
console.log(Number.isNaN("hello"));
```

Результат:

```text
false
```

---

#### Альтернативный способ

Используя уникальное свойство NaN:

```javascript
function isActualNaN(value) {
  return value !== value;
}
```

Поскольку только `NaN` не равен самому себе.

---

#### Итог

Для проверки значения на `NaN` рекомендуется использовать:

```javascript
Number.isNaN(value);
```

---

### Как в JS создать объект?

JavaScript предоставляет несколько способов создания объектов.

---

### 1. Литерал объекта

Самый распространенный способ.

```javascript
const user = {
  name: "John",
  age: 25
};
```

---

### 2. Конструктор Object

```javascript
const user = new Object();

user.name = "John";
user.age = 25;
```

---

### 3. Функция-конструктор

```javascript
function User(name, age) {
  this.name = name;
  this.age = age;
}

const user = new User("John", 25);
```

---

### 4. Классы

Современный способ создания объектов.

```javascript
class User {
  constructor(name, age) {
    this.name = name;
    this.age = age;
  }
}

const user = new User("John", 25);
```

---

### 5. Object.create()

Позволяет создать объект с указанным прототипом.

```javascript
const person = {
  greet() {
    console.log("Hello");
  }
};

const user = Object.create(person);
```

---

### 6. Фабричная функция (Factory Function)

```javascript
function createUser(name, age) {
  return {
    name,
    age
  };
}

const user = createUser("John", 25);
```

---

### Сравнение способов

| Способ            | Когда используется          |
| ----------------- | --------------------------- |
| Литерал `{}`      | Большинство случаев         |
| `new Object()`    | Практически не используется |
| Конструктор       | Старый подход               |
| `class`           | Современная разработка      |
| `Object.create()` | Работа с прототипами        |
| Factory Function  | Простое создание объектов   |

---

### Какие приемы работы с асинхронным кодом в JavaScript Вы знаете?

JavaScript является однопоточным языком программирования. Для выполнения длительных операций (сетевые запросы, работа с файлами, таймеры и т.д.) используются механизмы асинхронного программирования.

Основные подходы работы с асинхронным кодом:

* Callback Functions
* Promises
* Async/Await
* Методы Promise API
* Событийная модель (Event-Driven Programming)
* Web Workers (в браузере)
* Worker Threads (в Node.js)

---

### Callback Functions

Callback (функция обратного вызова) — функция, передаваемая в другую функцию и вызываемая после завершения операции.

Пример:

```javascript
setTimeout(() => {
  console.log("Прошла 1 секунда");
}, 1000);
```

---

#### Недостаток Callback Hell

При большом количестве вложенных асинхронных операций код становится сложно поддерживать.

```javascript
getUser(userId, user => {
  getOrders(user.id, orders => {
    getProducts(orders, products => {
      getReviews(products, reviews => {
        console.log(reviews);
      });
    });
  });
});
```

Такую ситуацию называют **Callback Hell** или **Pyramid of Doom**.

---

### Promises

Promise (Промис) — объект, представляющий результат асинхронной операции, который станет доступен в будущем.

---

#### Создание Promise

```javascript
const promise = new Promise((resolve, reject) => {
  const success = true;

  if (success) {
    resolve("Успех");
  } else {
    reject("Ошибка");
  }
});
```

---

#### Состояния Promise

| Состояние | Описание           |
| --------- | ------------------ |
| Pending   | Ожидание           |
| Fulfilled | Успешно выполнен   |
| Rejected  | Завершен с ошибкой |

---

#### Обработка результата

```javascript
promise
  .then(result => {
    console.log(result);
  })
  .catch(error => {
    console.error(error);
  })
  .finally(() => {
    console.log("Завершено");
  });
```

---

#### Пример с fetch

```javascript
fetch("/api/users")
  .then(response => response.json())
  .then(data => {
    console.log(data);
  })
  .catch(error => {
    console.error(error);
  });
```

---

### Async/Await

`async/await` — синтаксический сахар над Promise, позволяющий писать асинхронный код в синхронном стиле.

---

#### Async-функция

```javascript
async function getData() {
  return "Hello";
}
```

Фактически:

```javascript
Promise.resolve("Hello");
```

---

#### Await

```javascript
async function getUsers() {
  const response = await fetch("/api/users");

  const users = await response.json();

  console.log(users);
}
```

---

#### Обработка ошибок

```javascript
async function getUsers() {
  try {
    const response = await fetch("/api/users");

    const users = await response.json();

    return users;
  } catch (error) {
    console.error(error);
  }
}
```

---

#### Преимущества async/await

* Более читаемый код.
* Удобная обработка ошибок через `try/catch`.
* Отсутствие длинных цепочек `.then()`.

---

### Promise API

JavaScript предоставляет набор методов для работы с несколькими промисами одновременно.

---

#### Promise.all()

Ожидает успешного завершения всех промисов.

```javascript
const [users, posts] = await Promise.all([
  fetch("/users"),
  fetch("/posts")
]);
```

Если хотя бы один промис завершится ошибкой, весь `Promise.all()` будет отклонен.

---

#### Promise.allSettled()

Ожидает завершения всех промисов независимо от результата.

```javascript
const results = await Promise.allSettled([
  promise1,
  promise2
]);
```

Результат:

```javascript
[
  { status: "fulfilled", value: ... },
  { status: "rejected", reason: ... }
]
```

---

#### Promise.race()

Возвращает результат первого завершившегося промиса.

```javascript
const result = await Promise.race([
  promise1,
  promise2
]);
```

---

#### Promise.any()

Возвращает результат первого успешно выполненного промиса.

```javascript
const result = await Promise.any([
  promise1,
  promise2
]);
```

Игнорирует отклоненные промисы до тех пор, пока не завершатся все.

---

### Событийная модель (Event-Driven Programming)

Асинхронность часто реализуется через события.

Пример:

```javascript
button.addEventListener("click", () => {
  console.log("Кнопка нажата");
});
```

Другие примеры:

```javascript
window.addEventListener("resize", handler);

socket.addEventListener("message", handler);

document.addEventListener("keydown", handler);
```

---

### Web Workers

Web Worker позволяет выполнять тяжелые вычисления в отдельном потоке и не блокировать главный UI-поток браузера.

Создание Worker:

```javascript
const worker = new Worker("worker.js");
```

Отправка данных:

```javascript
worker.postMessage(data);
```

Получение ответа:

```javascript
worker.onmessage = event => {
  console.log(event.data);
};
```

---

### Worker Threads (Node.js)

Аналог Web Workers для Node.js.

```javascript
const { Worker } = require("worker_threads");

const worker = new Worker("./worker.js");
```

Используется для CPU-intensive задач:

* Шифрование.
* Обработка изображений.
* Сложные вычисления.
* Анализ больших объемов данных.

---

### Event Loop и асинхронность

Все перечисленные механизмы работают благодаря Event Loop.

Упрощенная схема:

```text
Call Stack
     ↓
Web APIs / Node APIs
     ↓
Task Queue
     ↓
Event Loop
```

Алгоритм работы:

1. Выполняется синхронный код.
2. После очистки стека выполняются все микротаски.
3. Затем выполняется одна макротаска.
4. Процесс повторяется.

---

### Пример порядка выполнения

```javascript
console.log("1");

setTimeout(() => {
  console.log("2");
}, 0);

Promise.resolve().then(() => {
  console.log("3");
});

console.log("4");
```

Результат:

```text
1
4
3
2
```

Потому что:

1. Выполняется синхронный код.
2. Выполняются все микротаски (`Promise.then`).
3. Выполняется макротаска (`setTimeout`).

---

### Сравнение подходов

| Подход          | Актуальность                | Применение             |
| --------------- | --------------------------- | ---------------------- |
| Callback        | Устаревающий                | Старый код, события    |
| Promise         | Актуальный                  | Основа асинхронности   |
| Async/Await     | Основной современный подход | Большинство приложений |
| Promise API     | Актуальный                  | Параллельные операции  |
| Event Listeners | Актуальный                  | Работа с событиями     |
| Web Workers     | Специализированный          | Тяжелые вычисления     |
| Worker Threads  | Node.js                     | CPU-intensive задачи   |


---

### Что такое мемоизация (Memoization)?

Мемоизация (Memoization) — это техника оптимизации, при которой результаты выполнения функции сохраняются в кэше и повторно используются при вызове функции с теми же аргументами.

Это позволяет избежать повторных вычислений и повысить производительность приложения.

---

#### Без мемоизации

```javascript
function square(n) {
  console.log("Вычисление...");

  return n * n;
}

square(5);
square(5);
square(5);
```

Результат:

```text
Вычисление...
Вычисление...
Вычисление...
```

Функция выполняется каждый раз.

---

#### С мемоизацией

```javascript
function memoizedSquare() {
  const cache = {};

  return function (n) {
    if (cache[n]) {
      return cache[n];
    }

    console.log("Вычисление...");

    const result = n * n;

    cache[n] = result;

    return result;
  };
}

const square = memoizedSquare();

console.log(square(5));
console.log(square(5));
console.log(square(5));
```

Результат:

```text
Вычисление...
25
25
25
```

Вычисление произошло только один раз.

---

#### Где используется

* Рекурсивные алгоритмы.
* Тяжелые вычисления.
* React (`React.memo`, `useMemo`, `useCallback`).
* Кэширование API-запросов.
* Оптимизация производительности.

---

#### Пример с числами Фибоначчи

Без мемоизации:

```javascript
function fib(n) {
  if (n < 2) return n;

  return fib(n - 1) + fib(n - 2);
}
```

Сложность:

```text
O(2ⁿ)
```

С мемоизацией:

```javascript
function fib(n, cache = {}) {
  if (n in cache) {
    return cache[n];
  }

  if (n < 2) {
    return n;
  }

  cache[n] = fib(n - 1, cache) + fib(n - 2, cache);

  return cache[n];
}
```

Сложность:

```text
O(n)
```

---

### Почему `typeof null` возвращает `object`? Как проверить, является ли значение `null`?

Это одна из самых известных исторических ошибок JavaScript.

Пример:

```javascript
console.log(typeof null);
```

Результат:

```text
object
```

Хотя `null` объектом не является.

---

#### Почему так произошло?

В первых версиях JavaScript значения хранились в памяти в специальном формате.

Для объектов использовался идентификатор типа:

```text
000
```

Значение `null` также было представлено как нулевой указатель:

```text
00000000
```

Из-за этого движок ошибочно определял `null` как объект.

Ошибка была обнаружена слишком поздно и сохранена ради обратной совместимости.

---

#### Как правильно проверить `null`?

Использовать строгое сравнение:

```javascript
if (value === null) {
  console.log("Это null");
}
```

---

Некорректный способ:

```javascript
typeof value === "object";
```

Потому что:

```javascript
typeof {};
```

и

```javascript
typeof null;
```

оба возвращают:

```text
object
```

---

#### Проверка одновременно на `null` и `undefined`

```javascript
if (value == null) {
  console.log("null или undefined");
}
```

Поскольку:

```javascript
null == undefined; // true
```

---

#### Рекомендуемый способ

Для проверки именно `null` всегда используйте:

```javascript
value === null
```

---

### Для чего используется ключевое слово `new`?

Ключевое слово `new` используется для создания нового экземпляра объекта на основе функции-конструктора или класса.

---

#### Пример с конструктором

```javascript
function User(name) {
  this.name = name;
}

const user = new User("John");
```

---

#### Что делает `new`?

При вызове:

```javascript
new User("John");
```

JavaScript выполняет следующие шаги:

##### 1. Создает новый объект

```javascript
const obj = {};
```

##### 2. Связывает объект с прототипом

```javascript
obj.__proto__ = User.prototype;
```

##### 3. Передает объект как `this`

```javascript
User.call(obj, "John");
```

##### 4. Возвращает созданный объект

```javascript
return obj;
```

---

Фактически:

```javascript
const user = new User("John");
```

примерно эквивалентно:

```javascript
const user = {};

user.__proto__ = User.prototype;

User.call(user, "John");
```

---

#### Использование с классами

```javascript
class User {
  constructor(name) {
    this.name = name;
  }
}

const user = new User("John");
```

Без `new`:

```javascript
User("John");
```

Результат:

```text
TypeError
```

---

#### Проверка экземпляра

```javascript
console.log(user instanceof User);
```

Результат:

```text
true
```

---

### Что такое Event Loop и принцип его работы?

Event Loop (цикл событий) — это механизм JavaScript, который позволяет выполнять асинхронный код в однопоточном окружении.

JavaScript имеет только один Call Stack (стек вызовов), но благодаря Event Loop может работать с таймерами, сетевыми запросами и событиями.

---

#### Основные компоненты

```text
Call Stack
     ↓
Web APIs
     ↓
Task Queue
     ↓
Event Loop
```

---

#### Call Stack

Стек выполняемых функций.

```javascript
function a() {
  b();
}

function b() {
  console.log("Hello");
}

a();
```

Стек:

```text
a()
b()
console.log()
```

---

#### Web APIs

Предоставляются браузером или Node.js:

* setTimeout
* fetch
* DOM Events
* AJAX
* WebSocket

---

#### Пример работы

```javascript
console.log("1");

setTimeout(() => {
  console.log("2");
}, 0);

console.log("3");
```

Результат:

```text
1
3
2
```

---

#### Почему так происходит?

1. Выполняется `console.log("1")`.
2. `setTimeout` передается в Web API.
3. Выполняется `console.log("3")`.
4. Стек становится пустым.
5. Callback попадает в очередь задач.
6. Event Loop помещает callback в стек.
7. Выполняется `console.log("2")`.

---

#### Алгоритм Event Loop

```text
while (true) {
    выполнить стек вызовов;

    если стек пуст:
        выполнить все микротаски;

    если микротасок нет:
        выполнить одну макротаску;
}
```

---

### Что такое микро- и макротаски?

Event Loop использует две основные очереди задач:

* Microtask Queue (очередь микротасок)
* Macrotask Queue (очередь макротасок)

---

#### Макротаски (Macrotasks)

Попадают в обычную очередь задач.

Примеры:

```javascript
setTimeout()
setInterval()
setImmediate() // Node.js
MessageChannel
I/O операции
```

Пример:

```javascript
setTimeout(() => {
  console.log("timeout");
}, 0);
```

---

#### Микротаски (Microtasks)

Имеют более высокий приоритет.

Примеры:

```javascript
Promise.then()
Promise.catch()
Promise.finally()
queueMicrotask()
MutationObserver
```

Пример:

```javascript
Promise.resolve().then(() => {
  console.log("promise");
});
```

---

#### Порядок выполнения

```javascript
console.log("1");

setTimeout(() => {
  console.log("2");
}, 0);

Promise.resolve().then(() => {
  console.log("3");
});

console.log("4");
```

Результат:

```text
1
4
3
2
```

---

#### Что произошло?

1. Выполнился синхронный код:

```text
1
4
```

2. Выполнились все микротаски:

```text
3
```

3. Выполнилась первая макротаска:

```text
2
```

---

#### Важное правило Event Loop

После завершения текущего стека вызовов:

```text
1. Выполнить ВСЕ микротаски.
2. Выполнить ОДНУ макротаску.
3. Снова выполнить ВСЕ микротаски.
4. Выполнить следующую макротаску.
```

---

#### Сравнение

| Тип задачи | Примеры                                      | Приоритет |
| ---------- | -------------------------------------------- | --------- |
| Microtask  | Promise.then, catch, finally, queueMicrotask | Высокий   |
| Macrotask  | setTimeout, setInterval, I/O, DOM Events     | Ниже      |

Поэтому на собеседованиях важно помнить правило:

> **Сначала выполняется синхронный код, затем все микротаски, и только после этого выполняется следующая макротаска.**

---

### Чем отличаются `prototype` и `__proto__`?

`prototype` и `__proto__` связаны с прототипным наследованием, но выполняют разные задачи.

---

#### `prototype`

Свойство `prototype` существует только у функций-конструкторов и классов.

Оно определяет объект-прототип, который будут наследовать создаваемые экземпляры.

Пример:

```javascript
function User(name) {
  this.name = name;
}

User.prototype.sayHello = function () {
  console.log(`Hello ${this.name}`);
};
```

Здесь:

```javascript
User.prototype
```

содержит метод `sayHello`, который будет доступен всем экземплярам.

---

#### `__proto__`

`__proto__` — это ссылка конкретного объекта на его прототип.

Пример:

```javascript
const user = new User("John");

console.log(user.__proto__ === User.prototype);
```

Результат:

```text
true
```

---

#### Визуально

```text
User
  │
  └── prototype
          │
          ▼
     {
       sayHello()
     }
          ▲
          │
user.__proto__
```

---

#### Что происходит при `new`

```javascript
const user = new User("John");
```

JavaScript делает примерно следующее:

```javascript
const user = {};

user.__proto__ = User.prototype;
```

---

#### Современный способ работы

Использование `__proto__` считается устаревшим.

Рекомендуется:

```javascript
Object.getPrototypeOf(user);
```

и

```javascript
Object.setPrototypeOf(user, prototype);
```

---

#### Главное различие

| Свойство    | Где находится | Назначение                             |
| ----------- | ------------- | -------------------------------------- |
| `prototype` | У функций     | Определяет прототип будущих объектов   |
| `__proto__` | У объектов    | Ссылка на фактический прототип объекта |

---

### В каких случаях используются анонимные функции?

Анонимная функция — это функция без имени.

Пример:

```javascript
function () {
  console.log("Hello");
}
```

Такая запись сама по себе вызовет ошибку, поскольку функция должна быть частью выражения.

---

#### Передача в качестве callback

Самое распространенное применение.

```javascript
setTimeout(function () {
  console.log("Hello");
}, 1000);
```

---

#### Методы массивов

```javascript
const numbers = [1, 2, 3];

numbers.map(function (item) {
  return item * 2;
});
```

---

#### Обработчики событий

```javascript
button.addEventListener("click", function () {
  console.log("Clicked");
});
```

---

#### IIFE (Immediately Invoked Function Expression)

Самовызывающаяся функция.

```javascript
(function () {
  console.log("Executed");
})();
```

Результат:

```text
Executed
```

---

#### Замыкания

```javascript
function createCounter() {
  let count = 0;

  return function () {
    return ++count;
  };
}
```

Внутренняя функция является анонимной.

---

#### Promise

```javascript
fetch("/users")
  .then(function (response) {
    return response.json();
  });
```

---

#### Современный вариант

Чаще используются стрелочные функции:

```javascript
fetch("/users")
  .then(response => response.json());
```

---

#### Когда применяются

* Callback-функции.
* Обработчики событий.
* Promise.
* Замыкания.
* IIFE.
* Методы массивов (`map`, `filter`, `reduce`).

---

### Что такое функция высшего порядка (Higher-Order Function)?

Функция высшего порядка (Higher-Order Function) — это функция, которая:

1. Принимает другую функцию в качестве аргумента.
2. Возвращает функцию как результат.

Достаточно выполнения любого из этих условий.

---

#### Принимает функцию как аргумент

```javascript
function execute(callback) {
  callback();
}

execute(() => {
  console.log("Hello");
});
```

---

#### Возвращает функцию

```javascript
function multiply(multiplier) {
  return function (value) {
    return value * multiplier;
  };
}

const double = multiply(2);

console.log(double(5));
```

Результат:

```text
10
```

---

#### Примеры встроенных Higher-Order Functions

##### map

```javascript
const numbers = [1, 2, 3];

const doubled = numbers.map(x => x * 2);
```

---

##### filter

```javascript
const adults = users.filter(
  user => user.age >= 18
);
```

---

##### reduce

```javascript
const sum = numbers.reduce(
  (acc, value) => acc + value,
  0
);
```

---

#### Зачем нужны

Позволяют:

* Писать более гибкий код.
* Избегать дублирования.
* Реализовывать функциональное программирование.
* Создавать переиспользуемую логику.

---

#### Определение для собеседования

> Функция высшего порядка (Higher-Order Function) — это функция, которая принимает другую функцию в качестве аргумента или возвращает функцию как результат своей работы.

---

### Что такое WebGL?

WebGL (Web Graphics Library) — это JavaScript API для отображения интерактивной 2D и 3D графики в браузере без использования дополнительных плагинов.

WebGL работает через элемент `<canvas>` и использует возможности видеокарты (GPU).

---

#### Возможности WebGL

Позволяет создавать:

* 3D-модели.
* Игры.
* Визуализации данных.
* CAD-системы.
* AR/VR-приложения.
* Интерактивные карты.

---

#### Пример получения контекста

```javascript
const canvas = document.getElementById("canvas");

const gl = canvas.getContext("webgl");
```

---

#### Если WebGL поддерживается

```javascript
if (gl) {
  console.log("WebGL supported");
}
```

---

#### Технологии поверх WebGL

Чаще всего напрямую WebGL не используют.

Популярные библиотеки:

* Three.js
* Babylon.js
* PlayCanvas

Пример на Three.js:

```javascript
const scene = new THREE.Scene();

const camera = new THREE.PerspectiveCamera();

const renderer = new THREE.WebGLRenderer();
```

---

#### WebGL и OpenGL

WebGL основан на спецификации:

OpenGL ES

По сути это браузерная реализация возможностей OpenGL ES.

---

#### Преимущества

* Аппаратное ускорение через GPU.
* Работает во всех современных браузерах.
* Не требует установки плагинов.
* Поддерживает сложную 3D-графику.

---

### Как работает Boxing / Unboxing в JavaScript?

Boxing и Unboxing — это автоматическое преобразование между примитивами и объектами-обертками.

---

#### Boxing (упаковка)

Когда у примитива вызывается метод, JavaScript временно создает объект-обертку.

Пример:

```javascript
const str = "hello";

console.log(str.toUpperCase());
```

Фактически движок делает примерно следующее:

```javascript
const temp = new String("hello");

temp.toUpperCase();
```

После выполнения временный объект удаляется.

---

#### Примитивы с обертками

| Примитив | Обертка |
| -------- | ------- |
| string   | String  |
| number   | Number  |
| boolean  | Boolean |
| bigint   | BigInt  |
| symbol   | Symbol  |

---

#### Пример Boxing

```javascript
const num = 123;

console.log(num.toFixed(2));
```

Хотя `num` — примитив, метод доступен благодаря временной объектной обертке.

---

#### Unboxing (распаковка)

Обратный процесс — получение примитивного значения из объекта-обертки.

Пример:

```javascript
const str = new String("hello");

console.log(str.valueOf());
```

Результат:

```text
hello
```

---

#### Неявный Unboxing

```javascript
const num = new Number(5);

console.log(num + 1);
```

Результат:

```text
6
```

JavaScript автоматически извлекает примитивное значение из объекта.

---

#### Почему не рекомендуется создавать обертки вручную?

```javascript
const str = new String("hello");
```

Теперь это объект:

```javascript
console.log(typeof str);
```

Результат:

```text
object
```

Сравнение:

```javascript
console.log("hello" === new String("hello"));
```

Результат:

```text
false
```

Поскольку сравниваются примитив и объект.

---

#### Итог

**Boxing** — автоматическое создание временного объекта-обертки для примитива.

```javascript
"hello".toUpperCase();
```

**Unboxing** — получение примитивного значения из объекта-обертки.

```javascript
new Number(5).valueOf();
```

Этот механизм позволяет примитивам использовать методы и свойства так, как будто они являются полноценными объектами.

---

### Опишите назначение и принципы работы с коллекциями WeakMap и WeakSet. Чем они отличаются от Map и Set?

`WeakMap` и `WeakSet` — специальные коллекции, которые позволяют хранить объекты по слабым ссылкам (Weak References).

Основная цель — избежать утечек памяти.

---

### WeakMap

`WeakMap` похож на `Map`, но имеет ряд ограничений.

Пример:

```javascript
const weakMap = new WeakMap();

const user = {
  name: "John"
};

weakMap.set(user, "admin");

console.log(weakMap.get(user));
```

Результат:

```text
admin
```

---

#### Главное отличие от Map

Ключами в `WeakMap` могут быть только объекты.

Корректно:

```javascript
const obj = {};

weakMap.set(obj, "value");
```

Ошибка:

```javascript
weakMap.set("key", "value");
```

Результат:

```text
TypeError
```

---

#### Слабая ссылка

Если объект больше нигде не используется:

```javascript
let user = {
  name: "John"
};

weakMap.set(user, "admin");

user = null;
```

После этого объект может быть удален сборщиком мусора (Garbage Collector).

Запись в `WeakMap` также исчезнет автоматически.

---

#### Отсутствие итерации

Для WeakMap недоступны:

```javascript
weakMap.keys();
weakMap.values();
weakMap.entries();
weakMap.forEach();
```

Также отсутствует:

```javascript
weakMap.size;
```

Причина — невозможно гарантировать существование объекта в памяти.

---

### WeakSet

`WeakSet` работает аналогично `WeakMap`.

Пример:

```javascript
const weakSet = new WeakSet();

const user = {
  name: "John"
};

weakSet.add(user);

console.log(weakSet.has(user));
```

Результат:

```text
true
```

---

#### Ограничение

Можно хранить только объекты:

```javascript
weakSet.add({});
```

Ошибка:

```javascript
weakSet.add("hello");
```

---

#### Слабая ссылка

Если объект станет недоступным:

```javascript
let user = {
  name: "John"
};

weakSet.add(user);

user = null;
```

Запись автоматически удалится сборщиком мусора.

---

### Сравнение Map и WeakMap

| Возможность       | Map | WeakMap |
| ----------------- | --- | ------- |
| Ключи любого типа | Да  | Нет     |
| Ключи-объекты     | Да  | Да      |
| Перебор элементов | Да  | Нет     |
| size              | Да  | Нет     |
| Автоудаление GC   | Нет | Да      |

---

### Сравнение Set и WeakSet

| Возможность       | Set | WeakSet |
| ----------------- | --- | ------- |
| Любые значения    | Да  | Нет     |
| Только объекты    | Нет | Да      |
| Перебор элементов | Да  | Нет     |
| size              | Да  | Нет     |
| Автоудаление GC   | Нет | Да      |

---

### Когда использовать WeakMap и WeakSet?

Наиболее частые сценарии:

* Хранение приватных данных объектов.
* Кэширование.
* Метаданные для DOM-элементов.
* Отслеживание объектов без риска утечки памяти.

---

### Расскажите о генераторах и итераторах

---

### Итератор (Iterator)

Итератор — это объект, позволяющий последовательно получать элементы коллекции.

Он реализует метод:

```javascript
next()
```

который возвращает объект:

```javascript
{
  value,
  done
}
```

Пример:

```javascript
const arr = [10, 20, 30];

const iterator = arr[Symbol.iterator]();

console.log(iterator.next());
console.log(iterator.next());
console.log(iterator.next());
```

Результат:

```javascript
{ value: 10, done: false }
{ value: 20, done: false }
{ value: 30, done: false }
```

Следующий вызов:

```javascript
console.log(iterator.next());
```

Результат:

```javascript
{ value: undefined, done: true }
```

---

### Итерируемые объекты

Объект считается итерируемым, если содержит:

```javascript
Symbol.iterator
```

Например:

```javascript
Array
String
Map
Set
```

---

### Генераторы (Generators)

Генератор — специальная функция, которая может приостанавливать выполнение и продолжать его позже.

Объявляется через `function*`.

Пример:

```javascript
function* generator() {
  yield 1;
  yield 2;
  yield 3;
}
```

---

Создание генератора:

```javascript
const gen = generator();
```

---

Получение значений:

```javascript
console.log(gen.next());
console.log(gen.next());
console.log(gen.next());
```

Результат:

```javascript
{ value: 1, done: false }
{ value: 2, done: false }
{ value: 3, done: false }
```

---

После завершения:

```javascript
console.log(gen.next());
```

Результат:

```javascript
{ value: undefined, done: true }
```

---

### Ключевое слово yield

`yield` приостанавливает выполнение функции.

```javascript
function* numbers() {
  console.log("Start");

  yield 1;

  console.log("Middle");

  yield 2;

  console.log("End");
}
```

---

### Перебор генератора

```javascript
for (const value of numbers()) {
  console.log(value);
}
```

Результат:

```text
Start
1
Middle
2
End
```

---

### Бесконечный генератор

```javascript
function* counter() {
  let i = 0;

  while (true) {
    yield i++;
  }
}
```

---

### Для чего используются генераторы

* Создание собственных итераторов.
* Ленивые вычисления (Lazy Evaluation).
* Работа с большими объемами данных.
* Реализация последовательностей.
* Управление асинхронностью (до появления async/await).

---

### Что такое чейнинг функций (Function Chaining)?

Чейнинг (Chaining) — техника, позволяющая вызывать несколько методов подряд через точечную нотацию.

Пример:

```javascript
obj.method1()
   .method2()
   .method3();
```

---

### Пример встроенного чейнинга

```javascript
const result =
  " hello "
    .trim()
    .toUpperCase()
    .replace("HELLO", "WORLD");

console.log(result);
```

Результат:

```text
WORLD
```

---

### Как реализовать собственный чейнинг

Метод должен возвращать объект через `this`.

```javascript
class Calculator {
  constructor() {
    this.value = 0;
  }

  add(n) {
    this.value += n;
    return this;
  }

  multiply(n) {
    this.value *= n;
    return this;
  }
}
```

Использование:

```javascript
const result = new Calculator()
  .add(5)
  .multiply(2);

console.log(result.value);
```

Результат:

```text
10
```

---

### Примеры чейнинга

Promise:

```javascript
fetch("/users")
  .then(response => response.json())
  .then(data => console.log(data))
  .catch(error => console.error(error));
```

---

Массивы:

```javascript
const result = users
  .filter(user => user.age >= 18)
  .map(user => user.name)
  .sort();
```

---

### Что дает чейнинг

* Более читаемый код.
* Уменьшение количества промежуточных переменных.
* Fluent API (текучий интерфейс).

---

### Какие есть подходы оптимизации производительности веб-страницы?

Оптимизация веб-приложения включает работу с сетью, JavaScript, DOM, CSS и ресурсами.

---

### 1. Минимизация количества запросов

Объединение ресурсов:

```text
app.js
vendor.js
styles.css
```

Вместо десятков отдельных файлов.

---

### 2. Сжатие ресурсов

Использование:

```text
Gzip
Brotli
```

Позволяет уменьшить объем передаваемых данных.

---

### 3. Минификация

Удаление пробелов и комментариев:

```javascript
function sum(a,b){return a+b}
```

Вместо:

```javascript
function sum(a, b) {
  return a + b;
}
```

---

### 4. Lazy Loading

Загрузка ресурсов только при необходимости.

Для изображений:

```html
<img src="image.jpg" loading="lazy">
```

Для модулей:

```javascript
const Page = React.lazy(() =>
  import("./Page")
);
```

---

### 5. Оптимизация работы с DOM

Плохо:

```javascript
for (let i = 0; i < 1000; i++) {
  element.innerHTML += "<div></div>";
}
```

Лучше:

```javascript
let html = "";

for (let i = 0; i < 1000; i++) {
  html += "<div></div>";
}

element.innerHTML = html;
```

---

### 6. Debounce и Throttle

Для событий:

```javascript
scroll
resize
mousemove
input
```

Debounce:

```javascript
debounce(search, 300);
```

Throttle:

```javascript
throttle(updateScroll, 100);
```

---

### 7. Виртуализация списков

Вместо рендера 10 000 элементов:

```text
React Window
React Virtualized
```

отрисовываются только видимые элементы.

---

### 8. Использование мемоизации

```javascript
useMemo()
useCallback()
React.memo()
```

Позволяет избежать лишних вычислений и ререндеров.

---

### 9. Кэширование

Использование:

* HTTP Cache
* Service Worker
* CDN
* LocalStorage
* IndexedDB

---

### 10. Оптимизация изображений

Использовать современные форматы:

```text
WebP
AVIF
```

Вместо:

```text
PNG
JPEG
```

при возможности.

---

### 11. Code Splitting

Разделение приложения на чанки.

```javascript
import("./AdminPage");
```

Пользователь загружает только необходимый код.

---

### 12. Оптимизация React-приложений

* React.memo
* useMemo
* useCallback
* Virtualization
* Lazy Loading
* Suspense
* Правильные key в списках

---
