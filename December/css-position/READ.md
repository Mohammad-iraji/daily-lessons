## CSS `position` Explained
The `position` property in CSS defines **how an element is positioned** in the browser window,page and  how it interacts with other elements.
--- 
## Position Values

```css
position: relative | absolute | fixed |
```
---
## 2. `position: relative`
- Stays in the normal flow
- Can be moved relative to its original position
- Other elements keep their space
```

### Why `relative` is Important
`position: relative` is commonly used to create a **positioning context** for absolutely positioned children
```
---

## 3. `position: absolute` place on the page
- Removed from the normal document flow
- Positioned relative to the **nearest positioned ancestor**
- Falls back to the `<html>` element if no parent is positioned.

> **Rule of Thumb:**  
> Always use `position: relative` on a parent when using `position: absolute` on a child.

```css
.parent {
  position: relative;
}

.child {
  position: absolute;
  top: 0;
  left: 0;
}
```
---

## 4. `position: fixed` place in the browser window
- Positioned relative to the viewport
- Stays in place while scrolling
- Removed from document flow
