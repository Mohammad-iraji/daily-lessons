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
```
---

# JavaScript String Basics

## 1. Terminology & Naming

**Terminology** refers to technical words used in programming.  
**Naming** means how we name variables, functions, and identifiers.

### Naming Rules in JavaScript
- Names must be descriptive
- Names cannot start with a number
- Allowed characters: letters, numbers, `_`, `$`
- JavaScript convention: **camelCase**

```js
let userName;
let totalPrice;
let isLoggedIn;
```
---
2. JavaScript Is Case Sensitive

JavaScript treats uppercase and lowercase letters as different characters.
```Js
let name = "Ali";
let Name = "Reza";

console.log(name); // Ali
console.log(Name); // Reza
```
---

3. String Syntax (Text Style Rules)

A string is a sequence of characters used to represent text.

JavaScript supports three string syntaxes:
* Single quotes: 'text'

* Double quotes: "text"

* Backticks (template strings): `text`


```js
let a = 'Hello';
let b = "Hello";
let c = `Hello`;
```
---
4. String Concatenation

Concatenation means joining multiple strings together.
```js
let firstName = "Ali";
let lastName = "Ahmadi";

let fullName = firstName + " " + lastName;
console.log(fullName); // Ali Ahmadi
```
---

6. Characters in a String
* One letter

* Numbers

* Symbols

* Mixed characters
```js
let letter = "A";
let numbers = "12";
let symbol = "@#";
let mixed = "A1@";
```
---

7. Escape Characters

An escape character allows special characters to be used inside strings.
Escape characters start with a backslash (\).

| Escape | Description  |
| ------ | ------------ |
| `\'`   | Single quote |
| `\"`   | Double quote |
| `\n`   | New line     |
| `\\`   | Backslash    |

---
8. Template Strings (Backticks)

Template strings use backticks ` and provide extra features.
They support:

* Interpolation

* Multi-line strings

---
9. Interpolation (${})
Interpolation allows embedding variables or expressions inside strings.
```js
let name = "Ali";
let age = 25;

let sentence = `My name is ${name} and I am ${age} years old.`;
console.log(sentence);
```
Interpolation only works with template strings.
---
10. Multi-line Strings

Template strings allow writing strings across multiple lines.
```js
let multiLineText = `This is line one
This is line two
This is line three`;
```

