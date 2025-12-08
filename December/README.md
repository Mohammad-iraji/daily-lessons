# CSS Grid

### 1. What is Grid?
**Grid** is a two-dimensional layout system for the web.  
Unlike **Flexbox** (which is primarily one-dimensional — either a row or a column), **Grid** allows you to control layout in both **rows and columns**.

> *This feature prevents you from using too many properties and keeps your code clean.*

---

### 2. When to use Grid?
You decide where to use it — but Grid is ideal for:  
- Page layouts  
- Complex two-dimensional designs  
- Components with rows + columns  

---

### 3. Core concepts and terminology (very important)

- The grid must be applied to a **container** (such as a `<div>`).
- `display: grid;` or `display: inline-grid;` — creates a grid formatting context.
- **Grid items**: the direct children of the grid container.
- `grid-template-rows` — defines row tracks.
- `grid-template-columns` — defines column tracks.
- **Grid gap** — space between rows/columns (`row-gap`, `column-gap`).

---

### 4. Essential container properties

- `display: grid;`
- `grid-template-columns: <track-size> ...;` — defines columns.  
  Examples: `1fr 2fr 100px`, `repeat(3, 1fr)`
- `fr` means **fractional unit** — a share of the free available space.


<img width="1898" height="905" alt="image" src="https://github.com/user-attachments/assets/803c66d1-6b12-4f34-a19b-b5dadf2e5586" />
