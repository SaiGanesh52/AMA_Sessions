# JavaScript Quick Questions and Answers

### 1. Name some array methods in JavaScript.

`map()`, `filter()`, `reduce()`, `find()`, `forEach()`, `push()`, `pop()`, `slice()`, `splice()`, `sort()`.

### 2. What is the difference between `map()` and `filter()`?

`map()` transforms every element and returns a new array, while `filter()` returns a new array containing only elements that satisfy a condition.

### 3. Is JavaScript compiled or interpreted?

JavaScript is generally considered an interpreted language, but modern engines use **JIT (Just-In-Time) compilation** to improve performance.

### 4. What is the `const` keyword?

`const` declares a block-scoped variable that cannot be reassigned after initialization.

### 5. What is the difference between a JavaScript object and a JSON object?

A JavaScript object is a native JavaScript data structure, while JSON is a **text-based data format** used for storing and exchanging data.

### 6. What is the JavaScript engine used by Google Chrome?

**V8**.

### 7. What is a formatted string in Python?

A formatted string uses an **f-string** to insert values into a string.

```python
name = "Sai"
print(f"Hello {name}")
```

### 8. What are primitive and non-primitive data types?

Primitive types store simple values, such as `string`, `number`, and `boolean`; non-primitive types include `objects`, `arrays`, and `functions`.

### 9. What is a microtask queue?

The microtask queue stores tasks such as **Promise callbacks** that are executed after the current synchronous code finishes and before the next macrotask.

### 10. What is the difference between `find()` and `filter()`?

`find()` returns the **first matching element**, while `filter()` returns **all matching elements in a new array**.

### 11. What is the rest operator?

The rest operator `...` collects multiple arguments or remaining elements into an array.

```javascript
function add(...numbers) {
    console.log(numbers);
}
```

### 12. What is the spread operator?

The spread operator `...` expands the elements of an array or properties of an object.

```javascript
const a = [1, 2];
const b = [...a, 3];

console.log(b); // [1, 2, 3]
```

### 13. What does `find()` return if it does not find a matching element?

It returns **`undefined`**.