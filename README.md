# masc-reset

A modern, lightweight, and customizable CSS reset that provides a clean and consistent foundation for any web project.

`masc-reset` removes browser default styles, normalizes typography, improves media rendering, and includes useful CSS custom properties for colors and fonts.

---

## ✨ Features

- ✅ Removes default margins, paddings, and borders
- ✅ Applies `box-sizing: border-box` globally
- ✅ Enables smooth scrolling
- ✅ Improves font rendering
- ✅ Resets headings, paragraphs, links, and lists
- ✅ Makes images, videos, and iframes responsive
- ✅ Normalizes form elements
- ✅ Resets tables and SVG behavior
- ✅ Includes customizable CSS variables
- ✅ Works with HTML, CSS, JavaScript, React, Vue, Angular, and more

---

## 📦 Installation

```bash
npm i masc-reset
```

---

## 🚀 Usage

### Import in CSS

```css
@import "masc-reset";
```

### Include in HTML

```html
<link rel="stylesheet" href="node_modules/masc-reset/reset.css" />
```

---

## 🎨 Included CSS Variables

```css
:root {
  /* Colors */
  --primary-color: #02161f;
  --secondary-color: #021b28;
  --thirty-color: #03283c;
  --black-color: #393939;
  --white-color: #ffffff;

  /* Typography */
  --primary-typography:
    system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
    Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;

  --secondary-typography: Verdana;
}
```

You can override these variables in your own stylesheet to match your design system.

---

## 📋 What This Reset Covers

### Global Reset

- Removes default `margin`, `padding`, and `border`
- Sets `box-sizing: border-box`

### Typography

- Normalizes headings, paragraphs, and inline text elements
- Improves font smoothing and hyphenation

### Links

- Removes default text decoration and inherited colors

### Lists

- Removes bullets and numbering

### Media

- Makes images, videos, iframes, and figures responsive

### Forms

- Normalizes inputs, buttons, textareas, and selects

### Tables

- Collapses borders and removes spacing

### SVG

- Sets `fill: currentColor`

### Text Selection

- Customizes selected text colors

---

## 💡 Example

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <link rel="stylesheet" href="node_modules/masc-reset/reset.css" />
  </head>
  <body>
    <h1>Hello World</h1>
    <p>Your project starts with a clean CSS foundation.</p>
  </body>
</html>
```

---

## 📁 Package Structure

```text
masc-reset/
├── reset.css
├── package.json
└── README.md
```

---

## 🌐 Browser Support

Compatible with all modern browsers:

- Google Chrome
- Mozilla Firefox
- Safari
- Microsoft Edge
- Opera

---

## 🛠️ Use Cases

`masc-reset` is ideal for:

- Landing pages
- Portfolios
- Corporate websites
- Web applications
- UI component libraries
- Design systems

---

## 📄 License

MIT License

---

## 👨‍💻 Author

Created by **MASC - Melvin Antonio Santana Cueto**

- GitHub: https://github.com/melvinsantanac
- npm: https://www.npmjs.com/~melvinsantanac

---

## ⭐ Support

If you find this package useful:

- Give it a ⭐ on GitHub
- Share it with other developers
- Use it in your projects

## ☕ Donate

If `masc-reset` has helped you and you'd like to support its development, you can buy me a coffee via PayPal:

- PayPal: https://paypal.me/melvinsantanac

---

## 🔗 npm Package

https://www.npmjs.com/package/masc-reset
