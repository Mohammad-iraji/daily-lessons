# Numbers & Math Basics in JavaScript


---

## Order of Operations (`+ - * /`)

JavaScript follows standard mathematical **order of operations** (also known as operator precedence):

1. **Multiplication (`*`) and Division (`/`)**
2. **Addition (`+`) and Subtraction (`-`)**
3. Operations with the same priority are evaluated **from left to right**
4. Parentheses `()` are evaluated first

### Example
```js
let result = 2 + 3 * 4;
console.log(result); // 14
