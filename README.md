### Содержание

| №   | Вопрос                                                                                                                                                                                                       |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 1   |[В чем разница между `null` и `undefined`?](#в-чем-разница-между-null-и-undefined)                                                                                                                            |
| 2  |[s](#является-ли-использование-унарного-плюса-оператор--самым-быстрым-способом-преобразования-строки-в-число)

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
