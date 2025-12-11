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

---
---
---
---

# Flexbox vs. CSS Grid: A Practical Comparison

CSS provides two powerful layout modules — **Flexbox** and **CSS Grid** — each designed to solve different types of layout challenges. This document explains the core concepts of both tools, highlights their strengths, and offers guidance on when to use each one.

---

## 🚀 What Is Flexbox?

Flexbox (Flexible Box Layout) is a one-dimensional layout system that excels at arranging items **in a single row or a single column**.

### Key Features
- One-dimensional: manages layout in *either* horizontal **or** vertical direction.
- Automatic space distribution and alignment.
- Great for dynamic and small-scale layouts.
- Ideal for navigation bars, buttons, toolbars, small component lists.
---
### Flexbox Container Properties
- `display: flex`
- `justify-content`:flex-start;|flex-end;|center;|space-between;|space-around; 
- `align-items` : flex-start;|flex-end;|center;|stretch;|
