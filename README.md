### 📄 `README.md`

````markdown
# 🛒 Shopping Card (Tailwind CSS)

A simple shopping card UI built using **HTML** and **Tailwind CSS**, displaying stylish product cards like headphones and laptops.

---

## 🚀 What I Learned

- How to use **Tailwind CSS utility classes** to build modern UI.
- Designed responsive product cards with:
  - Product images
  - Title, description, price
  - Star ratings
  - Hover effects using `scale`, `shadow`, and `transition`
- Applied Tailwind’s responsive grid (`grid-cols-1`, `md:grid-cols-2`)
- Added animated hover effects to entire cards.

---

## 🛠️ How to Install Tailwind CSS (Locally)

> If you're starting from scratch:

1. **Initialize your project**
```bash
npm init -y
````

2. **Install Tailwind via npm**

```bash
npm install -D tailwindcss
```

3. **Create Tailwind config file**

```bash
npx tailwindcss init
```

4. **Set up `tailwind.config.js`**

```js
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./*.html"],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

5. **Create your input CSS file (`input.css`)**

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

6. **Build your CSS**

```bash
npx tailwindcss -i ./input.css -o ./output.css --watch
```

7. **Link `output.css` in your HTML**

```html
<link rel="stylesheet" href="./output.css">
```



