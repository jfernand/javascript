# Declaring Functions

Functions like variables must be declared. Lets declare a function `double` which accepts an **argument** called `x` and **returns** the double of x :

```javascript
function double(x) {
    return 2 * x;
}
```

Functions are also values in JavaScript, they can be stored in variables (just like numbers, strings, etc ...) and given to other functions as arguments :

```javascript
var double = function(x) {
    return 2 * x;
};
```

---

Declare a function named `triple` that takes and argument and returns it's triple.

```js

```

```js
var triple = function(x) {
    return x * 3;
}
```

```js
assert(triple);
assert(triple(4) === 12);
assert(triple(10) === 30);
```

---

